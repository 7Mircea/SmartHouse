# SMART HOUSE
Proiectul este mai larg fiind realizat in echipa. Aici se afla partea de captare a luminii solare.
## Energie solara
Partea de energie solară este reprezentată de o platformă cu plăcuțe fotovoltaice(simbolice) care 
are în centru 4 fotorezistoare și o structură în formă de cruce ce are rolul de a ajuta în stabilirea 
cantității de lumină ce cade de pe fiecare fotorezistor aflat la bază. Fiecare fotorezistor este 
conectat la un pin diferit analogic care măsoară tensiunea de pe fiecare rezistor. Aceste elemente 
își schimbă rezistența în funcție de cantitatea de lumină care cade pe ele și ca atare se modifică 
tensiunea măsurată de Arduino pentru fiecare dintre ele. Atunci când cantitatea de lumină care cade
 pe fiecare element este egală și tensiunile măsurate sunt egale(în limita unei toleranțe). Pentru 
 aducerea platformei solare în poziția optimă sunt folosite două servomotoare care oferă astfel
 două grade de libertate și care sunt comandate de pe pinii digitali.<br/>
 Programul este scris in C++ si ruleaza pe un Arduino Uno. Avantejele acestui proiect sunt date de 
 consumul redus al microcontrolerului comparativ cu faptul ca se permite utilizarea la maxima luminii
 solare.