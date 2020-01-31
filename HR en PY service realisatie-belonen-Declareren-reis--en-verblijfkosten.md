# (belonen) Declareren reis- en verblijfkosten

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))
  * [Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))
  * [Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))
  * [Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))
  * [Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))
  * [Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))
  * [Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))
  * [Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))
  * [Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))
  * [Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))
  * [Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))
  * [?? Besluiten verplaatsingskosten (Business Process)](#??-besluiten-verplaatsingskosten-(business-process))
  * [Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))
  * [Manager (Business Role)](#manager-(business-role))
  * [HRO (Business Role)](#hro-(business-role))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
* [Applicatie (Diagram Model Group)](#applicatie-(diagram-model-group))
  * [ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))
  * [Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))
  * [Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))
  * [SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))
    * [SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))
    * [SAP Time Management (Application Component)](#sap-time-management-(application-component))
    * [SAP Payroll (Application Component)](#sap-payroll-(application-component))
  * [SAP GUI (Application Component)](#sap-gui-(application-component))
  * [Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))
  * [Registratie vaste reiskostenvergoeding (Application Function)](#registratie-vaste-reiskostenvergoeding-(application-function))
  * [Registratie mobiliteitskaart (Application Function)](#registratie-mobiliteitskaart-(application-function))
  * [Registratie onkostenvergoeding dienstreizen (Application Function)](#registratie-onkostenvergoeding-dienstreizen-(application-function))
  * [Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))
  * [Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))
  * [Registreren mobiliteitskaart (Application Service)](#registreren-mobiliteitskaart-(application-service))
  * [AND (Application Component)](#and-(application-component))
  * [Afstandberekening (Application Function)](#afstandberekening-(application-function))

## Introduction

![(belonen) Declareren reis- en verblijfkosten][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registreren vaste reiskostenvergoeding (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Aanvragen dienstreis buitenland (Business Process)

Aanvragen dienstreis is gebaseerd op ministerie of dat wel/niet kan via portaal

Wordt afgeschaft per 2020

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|Triggering Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Declareren dienstreis buitenland (Business Process)

Wordt afgeschaft per 2020

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|Triggering Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|Triggering Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Declareren dienstreis binnenland (Business Process)

Meereizers (bijv. passagiers in de auto) kunnen ook worden gedeclareerd.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|Triggering Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Beheren mobiliteitskaart (Business Process)

- Aanvragen
- Stopzetten
- Wijzigen

Moet verklaren wel/geen woon-werkverkeer met mobiliteitskaart.
Zorgt voor controle op ander woon-werkverkeer (bijv. dat je niet woon-werk met auto declareert)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[Registreren mobiliteitskaart (Application Service)](#registreren-mobiliteitskaart-(application-service))|Serving Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Snel invoeren meerdere dienstreizen (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|Triggering Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Aanvragen vaste vergoeding voor- en/of natraject (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Afkeuring van goedgekeurde reisdeclaraties (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### ?? Besluiten verplaatsingskosten (Business Process)

Misschien BuZa? Geen portaalproces

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[?? Besluiten verplaatsingskosten (Business Process)](#??-besluiten-verplaatsingskosten-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Beoordelen reisdeclaraties in behandeling (Business Process)

Terechtheid reis wordt beoordeeld door manager.
Bonnen/financiële correctheid wordt gecontroleerd door P-Direkt.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|Triggering Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|Triggering Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|Triggering Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen dienstreis buitenland (Business Process)](#aanvragen-dienstreis-buitenland-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[?? Besluiten verplaatsingskosten (Business Process)](#??-besluiten-verplaatsingskosten-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie vaste reiskostenvergoeding (Application Function)](#registratie-vaste-reiskostenvergoeding-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie onkostenvergoeding dienstreizen (Application Function)](#registratie-onkostenvergoeding-dienstreizen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie mobiliteitskaart (Application Function)](#registratie-mobiliteitskaart-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registratie vaste reiskostenvergoeding (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie vaste reiskostenvergoeding (Application Function)](#registratie-vaste-reiskostenvergoeding-(application-function))|Realization Relationship|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie vaste reiskostenvergoeding (Application Function)](#registratie-vaste-reiskostenvergoeding-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registratie mobiliteitskaart (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie mobiliteitskaart (Application Function)](#registratie-mobiliteitskaart-(application-function))|Realization Relationship|[Registreren mobiliteitskaart (Application Service)](#registreren-mobiliteitskaart-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie mobiliteitskaart (Application Function)](#registratie-mobiliteitskaart-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registratie onkostenvergoeding dienstreizen (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie onkostenvergoeding dienstreizen (Application Function)](#registratie-onkostenvergoeding-dienstreizen-(application-function))|Realization Relationship|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie onkostenvergoeding dienstreizen (Application Function)](#registratie-onkostenvergoeding-dienstreizen-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registreren vaste reiskostenvergoeding (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Registreren vaste reiskostenvergoeding (Business Process)](#registreren-vaste-reiskostenvergoeding-(business-process))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Aanvragen aanvullende vergoeding woon-werkverkeer (Business Process)](#aanvragen-aanvullende-vergoeding-woon-werkverkeer-(business-process))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|Serving Relationship|[Aanvragen vaste vergoeding voor- en/of natraject (Business Process)](#aanvragen-vaste-vergoeding-voor--enof-natraject-(business-process))|||
|[Registratie vaste reiskostenvergoeding (Application Function)](#registratie-vaste-reiskostenvergoeding-(application-function))|Realization Relationship|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|||
|[Afstandberekening (Application Function)](#afstandberekening-(application-function))|Realization Relationship|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registreren onkostenvergoeding dienstreizen (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Beoordelen reisdeclaraties in behandeling (Business Process)](#beoordelen-reisdeclaraties-in-behandeling-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Inzien (concept) ingediende reisaanvragen en -declaraties (Business Process)](#inzien-(concept)-ingediende-reisaanvragen-en--declaraties-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Aanvragen incidentele vergoeding woon-werkverkeer (Business Process)](#aanvragen-incidentele-vergoeding-woon-werkverkeer-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Afkeuring van goedgekeurde reisdeclaraties (Business Process)](#afkeuring-van-goedgekeurde-reisdeclaraties-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Snel invoeren meerdere dienstreizen (Business Process)](#snel-invoeren-meerdere-dienstreizen-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Declareren dienstreis buitenland (Business Process)](#declareren-dienstreis-buitenland-(business-process))|||
|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|Serving Relationship|[Declareren dienstreis binnenland (Business Process)](#declareren-dienstreis-binnenland-(business-process))|||
|[Registratie onkostenvergoeding dienstreizen (Application Function)](#registratie-onkostenvergoeding-dienstreizen-(application-function))|Realization Relationship|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|||
|[Afstandberekening (Application Function)](#afstandberekening-(application-function))|Realization Relationship|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Registreren mobiliteitskaart (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren mobiliteitskaart (Application Service)](#registreren-mobiliteitskaart-(application-service))|Serving Relationship|[Beheren mobiliteitskaart (Business Process)](#beheren-mobiliteitskaart-(business-process))|||
|[Registratie mobiliteitskaart (Application Function)](#registratie-mobiliteitskaart-(application-function))|Realization Relationship|[Registreren mobiliteitskaart (Application Service)](#registreren-mobiliteitskaart-(application-service))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### AND (Application Component)

Routeplanner


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[AND (Application Component)](#and-(application-component))|Assignment Relationship|[Afstandberekening (Application Function)](#afstandberekening-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

### Afstandberekening (Application Function)

Tussen twee adressen in NL/BE

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afstandberekening (Application Function)](#afstandberekening-(application-function))|Realization Relationship|[Registreren vaste reiskostenvergoeding (Application Service)](#registreren-vaste-reiskostenvergoeding-(application-service))|||
|[Afstandberekening (Application Function)](#afstandberekening-(application-function))|Realization Relationship|[Registreren onkostenvergoeding dienstreizen (Application Service)](#registreren-onkostenvergoeding-dienstreizen-(application-service))|||
|[AND (Application Component)](#and-(application-component))|Assignment Relationship|[Afstandberekening (Application Function)](#afstandberekening-(application-function))|||

[Up](#(belonen)-declareren-reis--en-verblijfkosten)

[embedView]: img-HR en PY service realisatie-belonen-Declareren-reis--en-verblijfkosten.png
Generated: Fri Jan 31 2020 10:28:43 GMT+0100 (CET)
