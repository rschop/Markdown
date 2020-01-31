# Business services en functies

* [Introduction](#introduction)
* [P-Direkt services en functies (Diagram Model Group)](#p-direkt-services-en-functies-(diagram-model-group))
  * [HR en PY (Business Service)](#hr-en-py-(business-service))
  * [Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))
  * [Roosteradministratie (Business Service)](#roosteradministratie-(business-service))
  * [App services (Business Service)](#app-services-(business-service))
  * [Proces facilitering (Business Function)](#proces-facilitering-(business-function))
  * [Proces uitvoering (Business Function)](#proces-uitvoering-(business-function))
  * [Proces ondersteuning (Business Function)](#proces-ondersteuning-(business-function))
  * [Data levering/consumptie (Business Function)](#data-leveringconsumptie-(business-function))
  * [(Strategische) informatievoorziening (Business Function)](#(strategische)-informatievoorziening-(business-function))
  * [Proces ontwikkeling/functioneel beheer (Business Function)](#proces-ontwikkelingfunctioneel-beheer-(business-function))
  * [Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))

## Introduction

![Business services en functies][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## P-Direkt services en functies (Diagram Model Group)

Deze view geeft de functies weer die voor de verschillende business services worden ingezet.

Procesfacilitering: 
* functionele ICT-voorzieningen zoals kanalen van dienstverlening: P-Direkt portaal, Rijksportaal Personeel, contact center
* de technische uitwerking van de ICT componenten wordt beschreven in de technische architectuur
* operationele informatievoorziening die inzicht geeft in tussen- en eindresultaten van het proces en wettelijke rapportages en tevens kan dienen voor control doeleinden
* procesgerelateerde documentatie zoals: - gebruikershandleidingen, werkinstructies, proces- en systeemtrainingen,  procestekeningen en –beschrijvingen

Procesuitvoering:
* uitvoering proces ten behoeve van medewerker, manager of ketenpartner
* verwerking gegevens als HRS
* beheer P-dossier
* adhoc rapportages

Procesondersteuning
Diverse vormen van ondersteuning van de gebruiker zoals:
* een informatievoorzieningsfunctie die via verschillende kanalen (telefonische hulp, Rijksportaal Personeel en andere kanalen) wordt ontsloten waardoor klanten: 
   - informatie kunnen krijgen over uit te voeren processen; 
   - informatie kunnen krijgen over de beschikbare procesfaciliteiten en hoe ze gebruikt kunnen worden; 
   - melding kunnen maken van fouten in processen of systemen; 
   - bestaande dienstverlening kunnen aanvragen of activeren, 
   - nieuwe ideeën voor (verbetering van) dienstverlening kunnen melden.
- opleidingen voor eindgebruikers, zoals een training P-Direktportaal ter ondersteuning van managers

Data levering/consumptie:
P-Direkt voorziet hierin door het beschikbaar stellen van interfaces naar diverse systemen van aangesloten organisaties, externe dienstverleners of ketenpartners die voor één of meerdere afnemers werken (bijvoorbeeld Arbo-diensten).

(Strategische) informatievoorziening:
Produkten gericht op de informatiebehoefte die van strategische aard is. Tevens informatie voor management- en beleidsondersteunende vraagstukken binnen het aandachtsgebied personeel en salaris.

### HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Proces uitvoering (Business Function)](#proces-uitvoering-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Proces ondersteuning (Business Function)](#proces-ondersteuning-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Data levering/consumptie (Business Function)](#data-leveringconsumptie-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[(Strategische) informatievoorziening (Business Function)](#(strategische)-informatievoorziening-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Proces ontwikkeling/functioneel beheer (Business Function)](#proces-ontwikkelingfunctioneel-beheer-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Proces facilitering (Business Function)](#proces-facilitering-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||

[Up](#business-services-en-functies)

### Services tbv UBR Personeel (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|||

[Up](#business-services-en-functies)

### Roosteradministratie (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|||
|[Data levering/consumptie (Business Function)](#data-leveringconsumptie-(business-function))|Realization Relationship|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|||

[Up](#business-services-en-functies)

### App services (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-en-functies)

### Proces facilitering (Business Function)

**Properties**
|status|
|---|
|definitief|

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Proces facilitering (Business Function)](#proces-facilitering-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||

[Up](#business-services-en-functies)

### Proces uitvoering (Business Function)

**Properties**
|status|
|---|
|concept|

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Proces uitvoering (Business Function)](#proces-uitvoering-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||

[Up](#business-services-en-functies)

### Proces ondersteuning (Business Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Proces ondersteuning (Business Function)](#proces-ondersteuning-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||

[Up](#business-services-en-functies)

### Data levering/consumptie (Business Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Data levering/consumptie (Business Function)](#data-leveringconsumptie-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Data levering/consumptie (Business Function)](#data-leveringconsumptie-(business-function))|Realization Relationship|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|||

[Up](#business-services-en-functies)

### (Strategische) informatievoorziening (Business Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[(Strategische) informatievoorziening (Business Function)](#(strategische)-informatievoorziening-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||

[Up](#business-services-en-functies)

### Proces ontwikkeling/functioneel beheer (Business Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Proces ontwikkeling/functioneel beheer (Business Function)](#proces-ontwikkelingfunctioneel-beheer-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||

[Up](#business-services-en-functies)

### Applicatie ontwikkeling/beheer (Business Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[HR en PY (Business Service)](#hr-en-py-(business-service))|||
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|||
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|||
|[Applicatie ontwikkeling/beheer (Business Function)](#applicatie-ontwikkelingbeheer-(business-function))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-en-functies)

[embedView]: img-Business-services-en-functies.png
Generated: Fri Jan 31 2020 10:28:50 GMT+0100 (CET)
