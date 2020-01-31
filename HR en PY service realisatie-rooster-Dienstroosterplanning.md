# (rooster) Dienstroosterplanning

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Roosterplanning (Business Service)](#roosterplanning-(business-service))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Regiekamer (Business Role)](#regiekamer-(business-role))
  * [Planner (Business Role)](#planner-(business-role))
  * [Supervisor plannen (Business Role)](#supervisor-plannen-(business-role))
  * [Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))
  * [HRS (Business Role)](#hrs-(business-role))
  * [HRO (Business Role)](#hro-(business-role))
  * [Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))
  * [Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))
  * [Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))
  * [Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))
  * [Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))
  * [Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))
  * [Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))
  * [Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))
  * [Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))
  * [Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))
* [Applicatie (Diagram Model Group)](#applicatie-(diagram-model-group))
  * [ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))
  * [Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))
  * [Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))
  * [SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))
    * [SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))
    * [SAP Time Management (Application Component)](#sap-time-management-(application-component))
    * [SAP Payroll (Application Component)](#sap-payroll-(application-component))
    * [Brievengenerator (Application Component)](#brievengenerator-(application-component))
  * [SAP GUI (Application Component)](#sap-gui-(application-component))
  * [Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))
  * [Registreren werkplekken (Application Service)](#registreren-werkplekken-(application-service))
  * [Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))
  * [Registreren additionele informatie (Application Service)](#registreren-additionele-informatie-(application-service))
  * [Registreren behoefte (Application Service)](#registreren-behoefte-(application-service))
  * [Registreren normrooster (Application Service)](#registreren-normrooster-(application-service))
  * [ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))
  * [ATW controle (Application Function)](#atw-controle-(application-function))
  * [Terugnemen normrooster (Application Service)](#terugnemen-normrooster-(application-service))
  * [Registreren werkelijk rooster (Application Service)](#registreren-werkelijk-rooster-(application-service))
  * [[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))

## Introduction

![(rooster) Dienstroosterplanning][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Roosterplanning (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Regiekamer (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Regiekamer (Business Role)](#regiekamer-(business-role))|Assignment Relationship|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Planner (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Supervisor plannen (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Supervisor plannen (Business Role)](#supervisor-plannen-(business-role))|Assignment Relationship|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Beheren werkplekken (Business Process)

•	Indiener: HRO O&F . 
•	Contact Center P-Direkt – Team O&F: Dit team behandelt alle wijzigingen in de organisatiestructuur binnen ECC P-Direkt.

Binnen de Belastingdienst wordt gebruik gemaakt van werkplekken om teams te vormen die specifieke werkzaamheden uitvoeren. Doordat de werkplekken aan organisatorische eenheden gekoppeld zijn, worden via de relatie medewerker - organisatorische eenheid ook de medewerkers aan een werkplek gekoppeld. Het proces Beheren Werkplekken maakt het mogelijk de werkplekken op een eenduidige manier aan te maken, te wijzigen en/of te begrenzen.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|||
|[Registreren werkplekken (Application Service)](#registreren-werkplekken-(application-service))|Serving Relationship|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Beheren kwalificatiecatalogus (Business Process)

•	Indiener: HR O&F 
•	Contact Center P-Direkt – Team O&F: Dit team behandeld alle wijzigingen in de organisatiestructuur binnen ECC P-Direkt.

Binnen de belastingdienst wordt gebruik gemaakt van kwalificaties om speciale behoeftes in de planning te kunnen vervullen.De kwalificaties kunnen zowel aan een behoefte als aan een medewerker gekoppeld worden.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|||
|[Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))|Serving Relationship|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Beheren medewerkerkwalificaties (Business Process)

Wanneer de kwalificaties van een medewerker wijzigen, dienen deze door de manager in het systeem gewijzigd te worden. De manager kan contact opnemen met het Contact Center van P-Direkt om de kwalificatie voor de medewerker in het systeem te laten registreren.
Vervolgens worden deze gegevens via het formulier in ECC P-Direkt weggeschreven en krijgen de medewerker en manager een bevestiging van de wijziging.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))|Serving Relationship|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Beheren additionele informatie (Business Process)

In sommige gevallen dient de planner additionele informatie te registeren bij een medewerker, bijvoorbeeld over de functionaliteit van de medewerker. Deze informatie registreert de planner in een maatwerk infotype behorende bij de medewerker voorzien van een begin en einddatum. De mogelijkheid tot vastleggen van de additionele informatie dient maximaal 15 karakters te bevatten. Wanneer deze informatie is vastgelegd, dient deze informatie getoond te worden via transactie PP60 en PP61. 

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|||
|[Registreren additionele informatie (Application Service)](#registreren-additionele-informatie-(application-service))|Serving Relationship|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Beheren behoefte (Business Process)

•	Manager: Geeft aan welke behoefte noodzakelijk is (buiten P-Direkt dienstverlening)
•	Planner: Registreert de behoefte in SAP

Start: De manager heeft een verandering van de werkvraag gesignaleerd.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|||
|[Registreren behoefte (Application Service)](#registreren-behoefte-(application-service))|Serving Relationship|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Opstellen normrooster (Business Process)

•	Planner: de persoon die verantwoordelijk is voor het matchen van vraag (behoefte) en aanbod (beschikbaarheid medewerkers).
•	Manager: de persoon die verantwoordelijk is voor de uit te voeren werkzaamheden en de daarbij behorende werkvraag en medewerkers
•	Medewerker: de persoon die werkzaamheden uitvoert volgens een bepaald rooster

Het doel van het proces is het inplannen van medewerkers zodat aan de behoefte van de werkplek voldaan wordt en duidelijk wordt op basis van welke werktijdregeling de medewerkers in die periode gaan werken.

Proces bevat verschillende stappen:
- Opstellen
- Voorkeur aangeven
- Validatie (tegen arbeidstijdenwet (ATW))
- Afsluiten


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[Registreren normrooster (Application Service)](#registreren-normrooster-(application-service))|Serving Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))|Serving Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Terugnemen normrooster (Business Process)

Dit proces wordt gestart wanneer een fout in het normrooster is geconstateerd. Het normrooster is de basis voor de berekeningen uit de tijdevaluatie. Wanneer het normrooster niet correct is, dient dit gecorrigeerd te worden.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|||
|[Supervisor plannen (Business Role)](#supervisor-plannen-(business-role))|Assignment Relationship|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|||
|[Terugnemen normrooster (Application Service)](#terugnemen-normrooster-(application-service))|Serving Relationship|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Beheren werkelijk rooster (Business Process)

Wanneer het normrooster is afgesloten, wordt gesproken van het werkelijke rooster. Dit werkelijk rooster wordt gebruikt voor het bepalen van diverse toelagen voor medewerkers in de onregelmatige dienst. Hierbij wordt een berekeningstijdvak van een kalendermaand gehanteerd. Minimaal 28 kalenderdagen voor het begin van een kalendermaand is het normrooster definitief gemaakt en afgesloten (= werkelijk rooster).

Proces heeft een aantal ingangen:
- Door wijziging van een werksituatie kan het voorkomen dat een manager opdracht geeft aan de planner om het werkelijk rooster aan te passen. De verandering van de werkvraag is daarbij de input van deze stap.
- De medewerker heeft een reden om een dienst te willen wijzigen.
- Wijzigingen die de planner van de manager en medewerkers heeft doorgekregen
 - 	Overwerk, meer- en minder uren
 - Verschuivingen
 - Vaartoelage
 - Ziekteregistratie



**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||
|[Planner (Business Role)](#planner-(business-role))|Assignment Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||
|[Registreren werkelijk rooster (Application Service)](#registreren-werkelijk-rooster-(application-service))|Serving Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||
|[ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))|Serving Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Raadplegen rooster en afrekening (Business Process)

Wanneer de medewerker behoefte heeft om inzicht te krijgen in informatie over zijn dienstplanning start hij één van de voor hem beschikbare rapporten.

Formulieren:
- Tijdformulier ZT03 (salarisstrook in uren)
- PP6A: Persoonlijk dienstrooster 
- ZDP_TEAM (PP6B): Team rooster

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|||
|[[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))|Serving Relationship|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Raadplegen stuurinformatie (manager) (Business Process)

Wanneer de manager behoefte heeft om inzicht te krijgen in informatie over zijn dienstplanning start hij één van de voor hem beschikbare rapporten

- ZHR_PTSP_ATW_CHECK - ATW Conflicten 
- ZDP_TEAM_ALL (PP6B): Teamrooster

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|||
|[[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))|Serving Relationship|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

### Raadplegen stuurinformatie (regiekamer) (Business Process)

- PP6A: Persoonlijk dienstrooster
- ZDP_TEAM_ALL (PP6B): Teamrooster
- PPPE_SEARCH_FOR_Q: Naar kwalificaties zoeken
- PP6I

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[Regiekamer (Business Role)](#regiekamer-(business-role))|Assignment Relationship|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|||
|[[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))|Serving Relationship|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[ATW controle (Application Function)](#atw-controle-(application-function))|||

[Up](#(rooster)-dienstroosterplanning)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(rooster)-dienstroosterplanning)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(rooster)-dienstroosterplanning)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[Brievengenerator (Application Component)](#brievengenerator-(application-component))|||

[Up](#(rooster)-dienstroosterplanning)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(rooster)-dienstroosterplanning)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(rooster)-dienstroosterplanning)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(rooster)-dienstroosterplanning)

#### Brievengenerator (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[Brievengenerator (Application Component)](#brievengenerator-(application-component))|||

[Up](#(rooster)-dienstroosterplanning)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren werkplekken (Application Service)](#registreren-werkplekken-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren additionele informatie (Application Service)](#registreren-additionele-informatie-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren behoefte (Application Service)](#registreren-behoefte-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren normrooster (Application Service)](#registreren-normrooster-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Terugnemen normrooster (Application Service)](#terugnemen-normrooster-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren werkelijk rooster (Application Service)](#registreren-werkelijk-rooster-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(rooster)-dienstroosterplanning)

### Registreren werkplekken (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren werkplekken (Application Service)](#registreren-werkplekken-(application-service))|Serving Relationship|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren werkplekken (Application Service)](#registreren-werkplekken-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Registreren kwalificaties (Application Service)

Registratie kwalificaties kan plaatsvinden op medewerkers of op behoeftes, welke aan elkaar gematcht kunnen worden

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))|Serving Relationship|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|||
|[Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))|Serving Relationship|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren kwalificaties (Application Service)](#registreren-kwalificaties-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Registreren additionele informatie (Application Service)

- transactie ZJDW
- maatwerkinfotype 9600


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren additionele informatie (Application Service)](#registreren-additionele-informatie-(application-service))|Serving Relationship|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren additionele informatie (Application Service)](#registreren-additionele-informatie-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Registreren behoefte (Application Service)

Behoefte wordt geregistreerd in SAP dienstplanning

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren behoefte (Application Service)](#registreren-behoefte-(application-service))|Serving Relationship|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren behoefte (Application Service)](#registreren-behoefte-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Registreren normrooster (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren normrooster (Application Service)](#registreren-normrooster-(application-service))|Serving Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren normrooster (Application Service)](#registreren-normrooster-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### ATW controleren rooster (Application Service)

Controle van rooster(s) tegen de arbeidsteidenwet

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))|Serving Relationship|[Opstellen normrooster (Business Process)](#opstellen-normrooster-(business-process))|||
|[ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))|Serving Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||
|[ATW controle (Application Function)](#atw-controle-(application-function))|Realization Relationship|[ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### ATW controle (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ATW controle (Application Function)](#atw-controle-(application-function))|Realization Relationship|[ATW controleren rooster (Application Service)](#atw-controleren-rooster-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[ATW controle (Application Function)](#atw-controle-(application-function))|||

[Up](#(rooster)-dienstroosterplanning)

### Terugnemen normrooster (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Terugnemen normrooster (Application Service)](#terugnemen-normrooster-(application-service))|Serving Relationship|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Terugnemen normrooster (Application Service)](#terugnemen-normrooster-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### Registreren werkelijk rooster (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren werkelijk rooster (Application Service)](#registreren-werkelijk-rooster-(application-service))|Serving Relationship|[Beheren werkelijk rooster (Business Process)](#beheren-werkelijk-rooster-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren werkelijk rooster (Application Service)](#registreren-werkelijk-rooster-(application-service))|||

[Up](#(rooster)-dienstroosterplanning)

### [placeholder] Portaalformulieren (Application Service)

Invulling hiervan volgt.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))|Serving Relationship|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|||
|[[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))|Serving Relationship|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|||
|[[placeholder] Portaalformulieren (Application Service)](#placeholder-portaalformulieren-(application-service))|Serving Relationship|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|||

[Up](#(rooster)-dienstroosterplanning)

[embedView]: img-HR en PY service realisatie-rooster-Dienstroosterplanning.png
Generated: Fri Jan 31 2020 10:28:45 GMT+0100 (CET)
