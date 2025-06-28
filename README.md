# Aplicatie_Practica_Licenta - Implementarea unui control automat HVAC utilizand automate programabile Siemens
## Repository GIT
Adresa Repository: https://github.com/Andrei10445/Aplicatie_Practica_Licenta
## Pași de instalare , compilare și lansare a aplicației
1.Se descarcă fișierul `Project1.rar` din repository și extrageți conținutul acestuia.
2.Deschideți programul TIA Portal v15.1 ( Versiune recomandată) .
3.În TIA Portal se selectează optiunea **Open existing project**, dupa care navigati catre folderul extras si deschideti fisierul `Aplicatie.ap15_1`.
4.In fereastra urmatoare , selectati optiunea **Open the project view** , din partea de jos.
5.In panoul din stanga , selectati 'PLC_1 [CPU 1214C DC/DC/DC], click dreapta pe el , si selectati **"Start simulation"**.
6. În fereastra de simulare, apăsați **"Load"**, modificați câmpul `Start modules` din `No action` în `Start module`, apoi apăsați **"Finish"**.
7. Selectați `HMI_1 [KTP700 Basic PN]` și apăsați din nou în bara de sus **"Start simulation"**.
8.In intefata HMI , apasati butonul **Ecran Setari**, in acel ecran in partea din colt stanga sus, introduceti valorile pentru controlul PID al temperaturii  ( ex. P 2.0, I 0.05, D 0.01 , partea din stanga) si controlul PID al umiditatii ( ex. P 1.8, I 0.04, D 0.02 , in partea dreapta a celor de la temperatura) cat si controlul P al CO2 , (ex P 0.01) . Se introduc valorile de referinta( SetPoint) pentru temperatura ( ex. 19) , umiditate ( ex. 50) si CO2 (ex. 800) , dupa care se pot introduce si valorile simulate ale acestora ( ex: 24 temperatura , 40 umiditatea si 840 CO2) . In momentul in care apasam pe buton ON/OFF HVAC , acest sistem incepe sa functioneze si sa se stabilizeze in jurul valorilor de referinta setate de dvs. , se pot vizualiza alarmele , viteza ventilatorui . iar in ecranul principal se pot vizualiza starea valvelor , clapeta de aerisire .Totodata se pot introduce valori de temperatura ,umiditate si CO2 si in ecranul principal unde avem si un buton ON/OFF HVAC . La apasarea butonului "Senzor prezenta" , se poate observa cum luminile se aprind iar usile se gliseaza.In cel de-al treilea ecran TrendView se poate vizualiza cum Output-ul pentru PID al temperaturii si umiditatii se stabilizeaza.
