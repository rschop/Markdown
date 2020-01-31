# (verlof) Verlofregistratie

* [Introduction](#introduction)
* [Applicatie (Diagram Model Group)](#applicatie-(diagram-model-group))
  * [Registreren verlof (Application Service)](#registreren-verlof-(application-service))
  * [ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))
  * [Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))
  * [Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))
  * [Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))
  * [Mobile Platform (Application Component)](#mobile-platform-(application-component))
  * [Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))
  * [Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))
  * [Verlof registreren App (Application Function)](#verlof-registreren-app-(application-function))
  * [Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))
  * [Verlof aanvragen Portaal (Application Function)](#verlof-aanvragen-portaal-(application-function))
  * [Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))
  * [SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))
    * [SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))
    * [SAP Time Management (Application Component)](#sap-time-management-(application-component))
    * [SAP Payroll (Application Component)](#sap-payroll-(application-component))
  * [SAP GUI (Application Component)](#sap-gui-(application-component))
  * [Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))
  * [Corrigeren compensatieverlof (Application Service)](#corrigeren-compensatieverlof-(application-service))
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Registreren verlof (Business Process)](#registreren-verlof-(business-process))
  * [Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))
  * [Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))
  * [Manager (Business Role)](#manager-(business-role))
  * [Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))
  * [Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))
  * [Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))
  * [Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))
  * [Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))

## Introduction

![(verlof) Verlofregistratie][embedView]

- Hardship verlof nog niet meegenomen

- twee andere bronnen: bulkmutatie en via interfaces


Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Applicatie (Diagram Model Group)

### Registreren verlof (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|Serving Relationship|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|||
|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|Serving Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||
|[Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))|Realization Relationship|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|||
|[Verlof registreren App (Application Function)](#verlof-registreren-app-(application-function))|Realization Relationship|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|||

[Up](#(verlof)-verlofregistratie)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Verlof aanvragen Portaal (Application Function)](#verlof-aanvragen-portaal-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Verlof registreren Portaal (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))|Realization Relationship|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|||
|[Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))|Realization Relationship|[Corrigeren compensatieverlof (Application Service)](#corrigeren-compensatieverlof-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Autoriseren mutaties Portaal (generiek) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|Realization Relationship|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Aanvragen verlof (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Verlof aanvragen Portaal (Application Function)](#verlof-aanvragen-portaal-(application-function))|Realization Relationship|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|||

[Up](#(verlof)-verlofregistratie)

### Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Verlof registreren App (Application Function)](#verlof-registreren-app-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Autoriseren mutaties App (generiek) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|Realization Relationship|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Verlof registreren App (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verlof registreren App (Application Function)](#verlof-registreren-app-(application-function))|Realization Relationship|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Verlof registreren App (Application Function)](#verlof-registreren-app-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Autoriseren verlof (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|Realization Relationship|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|||
|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|Realization Relationship|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|||

[Up](#(verlof)-verlofregistratie)

### Verlof aanvragen Portaal (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verlof aanvragen Portaal (Application Function)](#verlof-aanvragen-portaal-(application-function))|Realization Relationship|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Verlof aanvragen Portaal (Application Function)](#verlof-aanvragen-portaal-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(verlof)-verlofregistratie)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(verlof)-verlofregistratie)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(verlof)-verlofregistratie)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(verlof)-verlofregistratie)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(verlof)-verlofregistratie)

### Corrigeren compensatieverlof (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren compensatieverlof (Application Service)](#corrigeren-compensatieverlof-(application-service))|Serving Relationship|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|||
|[Verlof registreren Portaal (Application Function)](#verlof-registreren-portaal-(application-function))|Realization Relationship|[Corrigeren compensatieverlof (Application Service)](#corrigeren-compensatieverlof-(application-service))|||

[Up](#(verlof)-verlofregistratie)

## Business (Diagram Model Group)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Registreren verlof (Business Process)

Bevat meerdere typen verlof, al dan niet op basis van contigent

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|||
|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|Serving Relationship|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Aanvragen Zwangerschapsverlof (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Triggering Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Verlof en verzuim (Business Service)

Betreft alles rondom tijdsadministratie.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#(verlof)-verlofregistratie)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Aanvragen Ouderschapsverlof (Business Process)

Verschillende regelingen
- Gebaseerd op CAO of organisatie
- Afhankelijk van tijd geboorte (2015, 2017, etc)
- Heeft gevolgen voor salaris

Heeft 'Registreren kindgegevens' ingebouwd


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Aanvragen langdurig buitengewoon verlof (Business Process)

Regelingen afhankelijk van organisatie
Gevolg voor salaris & aanwezigheid

Niet zelf registreren

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Aanvragen Adoptie-/pleegzorgverlof (Business Process)

Heeft 'Registreren kindgegevens' ingebouwd

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Registreren Bevallingsdatum (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Triggering Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||
|[Registreren verlof (Application Service)](#registreren-verlof-(application-service))|Serving Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Verminderen verlofrecht (Business Process)

Trigger vanuit andere processen (zoals disciplinaire staf)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen verlof (Application Service)](#aanvragen-verlof-(application-service))|Serving Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Autoriseren verlof (Application Service)](#autoriseren-verlof-(application-service))|Serving Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|||

[Up](#(verlof)-verlofregistratie)

### Corrigeren compensatieverlof (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|||
|[Corrigeren compensatieverlof (Application Service)](#corrigeren-compensatieverlof-(application-service))|Serving Relationship|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|||

[Up](#(verlof)-verlofregistratie)

[embedView]: img-HR en PY service realisatie-verlof-Verlofregistratie.png
Generated: Fri Jan 31 2020 10:28:37 GMT+0100 (CET)
