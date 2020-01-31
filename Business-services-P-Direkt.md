# Business services P-Direkt

* [Introduction](#introduction)
* [P-Direkt dienstverlening (Grouping)](#p-direkt-dienstverlening-(grouping))
  * [Bedrijfszorg (Business Service)](#bedrijfszorg-(business-service))
  * [Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))
  * [Arbeidsjuridische dienstverlening (Business Service)](#arbeidsjuridische-dienstverlening-(business-service))
  * [Loopbaan, ontwikkeling en mobiliteit (Business Service)](#loopbaan,-ontwikkeling-en-mobiliteit-(business-service))
  * [Arbeidsmarkt communicatie (Business Service)](#arbeidsmarkt-communicatie-(business-service))
  * [Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))
  * [Roosteradministratie (Business Service)](#roosteradministratie-(business-service))
  * [Roosterplanning (Business Service)](#roosterplanning-(business-service))
  * [App services (Business Service)](#app-services-(business-service))
  * [Functieruil (Product)](#functieruil-(product))
  * [SCIO (Product)](#scio-(product))
  * [Exit enquetes (Product)](#exit-enquetes-(product))
  * [Warm welkom (Product)](#warm-welkom-(product))
  * [CAO app (Product)](#cao-app-(product))
  * [Afkortingen app (Product)](#afkortingen-app-(product))
  * [Uitstroom (Business Service)](#uitstroom-(business-service))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [Instroom (Business Service)](#instroom-(business-service))
  * [Doorstroom (Business Service)](#doorstroom-(business-service))
  * [Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))
  * [Roosterplanning (Business Service) 2](#roosterplanning-(business-service)-2)
  * [Werving en Selectie (Business Service)](#werving-en-selectie-(business-service))
* [HR en PY (Business Service)](#hr-en-py-(business-service))
* [Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))

## Introduction

![Business services P-Direkt][embedView]

Deze view geeft de verschillende business services weer die P-Direkt op vlak van HR ondersteunt. De app services zijn onderverdeeld in producten, aangezien zij feitelijk producten zijn die een deel van de HR services realiseren.

Bedrijfszorg (is live, muv WW casemanagement) :
Bedrijfsmaatschappelijk werk
Financieel loket
ERD ziektewet en werkhervatting gedeeltelijk arbeidsgeschikten
Re-integratie advies
WW casemanagement

Arbeids juridisch (procesbeschrijvingen worden uitgewerkt door de business, nog niet live):
Generiek advies
Conflictbemiddeling
Geschillen commissie
Klachtbehandeling

Loopbaan, ontwikkeling en mobiliteit:
Workflow (bouw 1e proces en procesbeschrijvingen overige processen zijn nu gestart):
- Van werk naar werk
- Losse instrumenten
- Vrijwillige organisatiegestuurde mobiliteit
- Begeleiding instroom arbeidsbeperkten


Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## P-Direkt dienstverlening (Grouping)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[P-Direkt dienstverlening (Grouping)](#p-direkt-dienstverlening-(grouping))|Aggregation Relationship|[Werving en Selectie (Business Service)](#werving-en-selectie-(business-service))|||

[Up](#business-services-p-direkt)

### Bedrijfszorg (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Bedrijfszorg (Business Service)](#bedrijfszorg-(business-service))|||

[Up](#business-services-p-direkt)

### Verlof en verzuim (Business Service)

Betreft alles rondom tijdsadministratie.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#business-services-p-direkt)

### Arbeidsjuridische dienstverlening (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Arbeidsjuridische dienstverlening (Business Service)](#arbeidsjuridische-dienstverlening-(business-service))|||

[Up](#business-services-p-direkt)

### Loopbaan, ontwikkeling en mobiliteit (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Loopbaan, ontwikkeling en mobiliteit (Business Service)](#loopbaan,-ontwikkeling-en-mobiliteit-(business-service))|||

[Up](#business-services-p-direkt)

### Arbeidsmarkt communicatie (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Arbeidsmarkt communicatie (Business Service)](#arbeidsmarkt-communicatie-(business-service))|||

[Up](#business-services-p-direkt)

### Services tbv UBR Personeel (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Bedrijfszorg (Business Service)](#bedrijfszorg-(business-service))|||
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Arbeidsjuridische dienstverlening (Business Service)](#arbeidsjuridische-dienstverlening-(business-service))|||
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Arbeidsmarkt communicatie (Business Service)](#arbeidsmarkt-communicatie-(business-service))|||
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Loopbaan, ontwikkeling en mobiliteit (Business Service)](#loopbaan,-ontwikkeling-en-mobiliteit-(business-service))|||
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Werving en Selectie (Business Service)](#werving-en-selectie-(business-service))|||

[Up](#business-services-p-direkt)

### Roosteradministratie (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#business-services-p-direkt)

### Roosterplanning (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Roosteradministratie (Business Service)](#roosteradministratie-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#business-services-p-direkt)

### App services (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Functieruil (Product)](#functieruil-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||
|[SCIO (Product)](#scio-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||
|[Exit enquetes (Product)](#exit-enquetes-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||
|[Warm welkom (Product)](#warm-welkom-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||
|[CAO app (Product)](#cao-app-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||
|[Afkortingen app (Product)](#afkortingen-app-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### Functieruil (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Functieruil (Product)](#functieruil-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### SCIO (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SCIO (Product)](#scio-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### Exit enquetes (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Exit enquetes (Product)](#exit-enquetes-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### Warm welkom (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Warm welkom (Product)](#warm-welkom-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### CAO app (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[CAO app (Product)](#cao-app-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### Afkortingen app (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afkortingen app (Product)](#afkortingen-app-(product))|Realization Relationship|[App services (Business Service)](#app-services-(business-service))|||

[Up](#business-services-p-direkt)

### Uitstroom (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#business-services-p-direkt)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#business-services-p-direkt)

### Instroom (Business Service)

WNRA gaat hier wijzigingen in aanbrengen

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#business-services-p-direkt)

### Doorstroom (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#business-services-p-direkt)

### Ontwikkelen personeel (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#business-services-p-direkt)

### Roosterplanning (Business Service) 2

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||

[Up](#business-services-p-direkt)

### Werving en Selectie (Business Service)

Het proces Werving & Selectie beschrijft de dienstverlening die P-Direkt biedt bij het  zoeken en vinden van een geschikte kandidaat voor een vastgestelde personele behoefte.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Services tbv UBR Personeel (Business Service)](#services-tbv-ubr-personeel-(business-service))|Aggregation Relationship|[Werving en Selectie (Business Service)](#werving-en-selectie-(business-service))|||
|[P-Direkt dienstverlening (Grouping)](#p-direkt-dienstverlening-(grouping))|Aggregation Relationship|[Werving en Selectie (Business Service)](#werving-en-selectie-(business-service))|||

[Up](#business-services-p-direkt)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Roosterplanning (Business Service)](#roosterplanning-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#business-services-p-direkt)

## Beheersing personeel en organisatie (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||

[Up](#business-services-p-direkt)

[embedView]: img-Business-services-P-Direkt.png
Generated: Fri Jan 31 2020 10:28:50 GMT+0100 (CET)
