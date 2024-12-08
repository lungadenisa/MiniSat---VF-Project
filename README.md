# MiniSat - VF Project

Acest proiect oferă o analiză detaliată a solverului SAT MiniSat, incluzând procesul de instalare, configurare și utilizare pentru rezolvarea problemelor de satisfiabilitate propozițională (SAT). Obiectivul principal este evaluarea performanței MiniSat prin rularea unui benchmark selectat din competiția SAT 2024.

## Pasi pentru instalarea Minisat - Windows

1. Instalarea celei mai recente versiuni a WSL si Ubuntu :
```
wsl --install
```
2. Deschiderea terminalului WSL si rularea comenzilor :
```
sudo apt-get update
sudo apt-get install minisat
```
3. Dupa instalare, se verifica functionarea Minisat-ului cu urmatoarea comanda :
```
minisat input.cnf output.txt
```
## Saptamana 10
* Am avut un meeting in care am discutat problemele identificate in cadrul raportului si modificarile pe care trebuie sa le facem.
* Am modificat o parte din problemele din raport
  
## Membrii echipei si sarcinile fiecaruia
* Potopea Mihaela:
  * Probleme intampinate la rulare si alte probleme
  * Latex Report
* Boeriu Lavinia:
  * Abstract
  * Documentarea codului
  * Explicatii prin comentarii in cod
* Stan Anamaria
  * Introducere
  * Descrierea problemei
  * Diagrame UML
  * Latex Report
* Lunga Denisa
  * Instalare Minisat
  * Rulare benchmark
  * Incarcare cod pe GitHub

## Referinte

* Minisat - http://minisat.se/
* Cod Minisat - https://github.com/niklasso/minisat
* Benchmark competitia SAT 2024 - https://benchmark-database.de/?track=main_2024
