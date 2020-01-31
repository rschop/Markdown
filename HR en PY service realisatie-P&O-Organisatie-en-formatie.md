# (P&O) Organisatie en formatie

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [HRO (Business Role)](#hro-(business-role))
  * [Beheren organisatiestructuur (Business Process)](#beheren-organisatiestructuur-(business-process))
  * [Beheren formatie (Business Process)](#beheren-formatie-(business-process))
  * [Registreren afwijkende plaats tewerkstelling (Business Process)](#registreren-afwijkende-plaats-tewerkstelling-(business-process))
  * [Reorganisatie (Business Process)](#reorganisatie-(business-process))
  * [HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))
  * [Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))
  * [Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))
  * [Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))
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
  * [Nakisa (Application Component)](#nakisa-(application-component))
* [Klant (Grouping)](#klant-(grouping))
  * [Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))
  * [Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))
  * [Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))
  * [Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))
  * [Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))
  * [Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))

## Introduction

![(P&O) Organisatie en formatie][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Beheersing personeel en organisatie (Business Service)

### Medewerker (Business Role)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

### Beheren organisatiestructuur (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren organisatiestructuur (Business Process)](#beheren-organisatiestructuur-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Beheren organisatiestructuur (Business Process)](#beheren-organisatiestructuur-(business-process))|Serving Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Beheren formatie (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren formatie (Business Process)](#beheren-formatie-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Beheren formatie (Business Process)](#beheren-formatie-(business-process))|Serving Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Registreren afwijkende plaats tewerkstelling (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren afwijkende plaats tewerkstelling (Business Process)](#registreren-afwijkende-plaats-tewerkstelling-(business-process))|Serving Relationship|[Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Reorganisatie (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Reorganisatie (Business Process)](#reorganisatie-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### HR authorisaties toekennen (Business Process)

Authorisaties worden aangevraagd via portaal of per e-mail naar CC O&F.



**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))|Serving Relationship|[Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

### Instellen vervanging manager (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))|Serving Relationship|[Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

### Beheren formatieplaats (Business Process)

Samengevoegd proces voor het toevoegen, wijzigen en beëindigen formatieplaatsen

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

### Beheren leidinggevende formatieplaats (Business Process)

Het beheren van de A012 leidinggevende relatie op een formatieplaats

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))|||

[Up](#(p&o)-organisatie-en-formatie)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(p&o)-organisatie-en-formatie)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(p&o)-organisatie-en-formatie)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(p&o)-organisatie-en-formatie)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(p&o)-organisatie-en-formatie)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(p&o)-organisatie-en-formatie)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(p&o)-organisatie-en-formatie)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(p&o)-organisatie-en-formatie)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(p&o)-organisatie-en-formatie)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(p&o)-organisatie-en-formatie)

### Nakisa (Application Component)

## Klant (Grouping)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Organisatie en Formatie (Business Service)

Het proces Organisatie & Formatie beschrijft de dienstverlening die P-Direkt biedt bij het ontwerpen, vastleggen en beheren van een bij de organisatiedoelstellingen passende organisatiestructuur inclusief de daarbij behorende functies en formatieplaatsen. Deze organisatiestructuur is aan verandering onderhevig.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))|||
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))|||
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Beheren O&F structuur (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Beheren organisatiestructuur (Business Process)](#beheren-organisatiestructuur-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Beheren formatie (Business Process)](#beheren-formatie-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Reorganisatie (Business Process)](#reorganisatie-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Beheren formatieplaats (Business Process)](#beheren-formatieplaats-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||
|[Beheren leidinggevende formatieplaats (Business Process)](#beheren-leidinggevende-formatieplaats-(business-process))|Serving Relationship|[Beheren O&F structuur (Business Service)](#beheren-o&f-structuur-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Ondersteunen flexibele organisaties (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||
|[Beheren organisatiestructuur (Business Process)](#beheren-organisatiestructuur-(business-process))|Serving Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||
|[Beheren formatie (Business Process)](#beheren-formatie-(business-process))|Serving Relationship|[Ondersteunen flexibele organisaties (Business Service)](#ondersteunen-flexibele-organisaties-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Registreren afwijkende plaats tewerkstelling (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))|||
|[Registreren afwijkende plaats tewerkstelling (Business Process)](#registreren-afwijkende-plaats-tewerkstelling-(business-process))|Serving Relationship|[Registreren afwijkende plaats tewerkstelling (Business Service)](#registreren-afwijkende-plaats-tewerkstelling-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Registreren vervangingen (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))|||
|[Instellen vervanging manager (Business Process)](#instellen-vervanging-manager-(business-process))|Serving Relationship|[Registreren vervangingen (Business Service)](#registreren-vervangingen-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

### Beheren autorisaties (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie en Formatie (Business Service)](#organisatie-en-formatie-(business-service))|Aggregation Relationship|[Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))|||
|[Klant (Grouping)](#klant-(grouping))|Aggregation Relationship|[Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))|||
|[HR authorisaties toekennen (Business Process)](#hr-authorisaties-toekennen-(business-process))|Serving Relationship|[Beheren autorisaties (Business Service)](#beheren-autorisaties-(business-service))|||

[Up](#(p&o)-organisatie-en-formatie)

[embedView]: img-HR en PY service realisatie-P&O-Organisatie-en-formatie.png
Generated: Fri Jan 31 2020 10:28:38 GMT+0100 (CET)
