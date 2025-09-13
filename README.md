# KIND&HUND Club Management and Website

Die Extension wird von der [conPassione gmbh](https://www.conpassione.ch) zur Verfügung gestellt.

KIND&HUND ist ein Verein, welcher sich um den Themenkomplex Kinder und Hunde
kümmert. Er organisiert Präventionseinsätze in Schulen, Einzelinterventionen
für Kinder mit Hundeangst und Lesehundeinsätze für Kinder mit Leseschwäche.
Zudem bildet der Verein Klassenhunde und Besuchshunde aus, welche mit ihrer
Präsenz in der Klasse zur Verbesserung des sozialen Klimas beitragen, die
Klasse ruhiger und konzentrierter machen.

Um die verschiedenen Ausbildungen und Einsätze von KIND&HUND zu unterstützen
wurde das KIND&HUND Club Management and Website erstellt.

Die erste Version stammt aus dem Jahre 2010. Seither wurde das System und
die Website kontinuierlich weiterentwickelt.

# Architektur
Die Architektur wurde mit der C4-Methode erstellt.
![Systemarchitektur KuH-CMaW](Systemuebersicht.webp)

# Komponenten
Für jede Komponente gibt es eine individuelle Extension.
## TeamManagement
Hier wird alles, was ein Team betrifft abgearbeitet. Von der Anmeldung als
neues Team über die Ausbildung, die Anmeldung für Weiterbildungen, die
Verwaltung des Profils und der Skills, etc.
## InterventionsManagement
Erstellen von Interventionen mit unterschiedlichen Typen
## ZuordnungsManagement
Zuordnen von Teams zu Interventionen inkl. der Aufgaben
## KalenderServices
Verwaltet alle Termine von Interventionen, QS, Ausbildung, Vereinstermine, etc.
## FinanzManagement
Stellt die Grundlagen für die jährliche oder halbjährliche Abrechnung mit
den Teams bereit. Zudem können über das FinanzManagement auch Rechnungen für
die verschiedenen Interventionen ausgelöst werden.
## QS-Management
Erstellt die QS-Termine und überwacht die Teams, damit sie genügend
QS-Termine besuchen.
## RS-Services
Stellt Statistiken und Reports zur Verfügung
