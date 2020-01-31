# Processen Roosterplanning

* [Introduction](#introduction)
* [Roosterplanning (Business Service)](#roosterplanning-(business-service))
* [HR en PY (Business Service)](#hr-en-py-(business-service))
* [Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))
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
* [Roosteradministratie (Business Service)](#roosteradministratie-(business-service))

## Introduction

![Processen Roosterplanning][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Roosterplanning (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
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
|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Beheren werkplekken (Business Process)

•	Indiener: HRO O&F . 
•	Contact Center P-Direkt – Team O&F: Dit team behandelt alle wijzigingen in de organisatiestructuur binnen ECC P-Direkt.

Binnen de Belastingdienst wordt gebruik gemaakt van werkplekken om teams te vormen die specifieke werkzaamheden uitvoeren. Doordat de werkplekken aan organisatorische eenheden gekoppeld zijn, worden via de relatie medewerker - organisatorische eenheid ook de medewerkers aan een werkplek gekoppeld. Het proces Beheren Werkplekken maakt het mogelijk de werkplekken op een eenduidige manier aan te maken, te wijzigen en/of te begrenzen.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren werkplekken (Business Process)](#beheren-werkplekken-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Beheren kwalificatiecatalogus (Business Process)

•	Indiener: HR O&F 
•	Contact Center P-Direkt – Team O&F: Dit team behandeld alle wijzigingen in de organisatiestructuur binnen ECC P-Direkt.

Binnen de belastingdienst wordt gebruik gemaakt van kwalificaties om speciale behoeftes in de planning te kunnen vervullen.De kwalificaties kunnen zowel aan een behoefte als aan een medewerker gekoppeld worden.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren kwalificatiecatalogus (Business Process)](#beheren-kwalificatiecatalogus-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Beheren medewerkerkwalificaties (Business Process)

Wanneer de kwalificaties van een medewerker wijzigen, dienen deze door de manager in het systeem gewijzigd te worden. De manager kan contact opnemen met het Contact Center van P-Direkt om de kwalificatie voor de medewerker in het systeem te laten registreren.
Vervolgens worden deze gegevens via het formulier in ECC P-Direkt weggeschreven en krijgen de medewerker en manager een bevestiging van de wijziging.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren medewerkerkwalificaties (Business Process)](#beheren-medewerkerkwalificaties-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Beheren additionele informatie (Business Process)

In sommige gevallen dient de planner additionele informatie te registeren bij een medewerker, bijvoorbeeld over de functionaliteit van de medewerker. Deze informatie registreert de planner in een maatwerk infotype behorende bij de medewerker voorzien van een begin en einddatum. De mogelijkheid tot vastleggen van de additionele informatie dient maximaal 15 karakters te bevatten. Wanneer deze informatie is vastgelegd, dient deze informatie getoond te worden via transactie PP60 en PP61. 

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren additionele informatie (Business Process)](#beheren-additionele-informatie-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Beheren behoefte (Business Process)

•	Manager: Geeft aan welke behoefte noodzakelijk is (buiten P-Direkt dienstverlening)
•	Planner: Registreert de behoefte in SAP

Start: De manager heeft een verandering van de werkvraag gesignaleerd.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren behoefte (Business Process)](#beheren-behoefte-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Opstellen normrooster (Business Process)

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

[Up](#processen-roosterplanning)

## Terugnemen normrooster (Business Process)

Dit proces wordt gestart wanneer een fout in het normrooster is geconstateerd. Het normrooster is de basis voor de berekeningen uit de tijdevaluatie. Wanneer het normrooster niet correct is, dient dit gecorrigeerd te worden.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Terugnemen normrooster (Business Process)](#terugnemen-normrooster-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Beheren werkelijk rooster (Business Process)

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

[Up](#processen-roosterplanning)

## Raadplegen rooster en afrekening (Business Process)

Wanneer de medewerker behoefte heeft om inzicht te krijgen in informatie over zijn dienstplanning start hij één van de voor hem beschikbare rapporten.

Formulieren:
- Tijdformulier ZT03 (salarisstrook in uren)
- PP6A: Persoonlijk dienstrooster 
- ZDP_TEAM (PP6B): Team rooster

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen rooster en afrekening (Business Process)](#raadplegen-rooster-en-afrekening-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Raadplegen stuurinformatie (manager) (Business Process)

Wanneer de manager behoefte heeft om inzicht te krijgen in informatie over zijn dienstplanning start hij één van de voor hem beschikbare rapporten

- ZHR_PTSP_ATW_CHECK - ATW Conflicten 
- ZDP_TEAM_ALL (PP6B): Teamrooster

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen stuurinformatie (manager) (Business Process)](#raadplegen-stuurinformatie-(manager)-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Raadplegen stuurinformatie (regiekamer) (Business Process)

- PP6A: Persoonlijk dienstrooster
- ZDP_TEAM_ALL (PP6B): Teamrooster
- PPPE_SEARCH_FOR_Q: Naar kwalificaties zoeken
- PP6I

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen stuurinformatie (regiekamer) (Business Process)](#raadplegen-stuurinformatie-(regiekamer)-(business-process))|Realization Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

## Roosteradministratie (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#processen-roosterplanning)

[embedView]: img-Overzicht processen per business service-Processen-Roosterplanning.png
Generated: Fri Jan 31 2020 10:28:48 GMT+0100 (CET)
