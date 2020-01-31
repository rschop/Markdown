# (doorstroom) Doorstroom

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Doorstroom (Business Service)](#doorstroom-(business-service))
  * [Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))
  * [Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))
  * [Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Namens manager (Business Role)](#namens-manager-(business-role))
  * [Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))
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
  * [Mobile Platform (Application Component)](#mobile-platform-(application-component))
  * [Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))
  * [Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))
  * [Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))
  * [Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))

## Introduction

![(doorstroom) Doorstroom][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Doorstroom (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#(doorstroom)-doorstroom)

### Beëindigen dienstverband (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Triggering Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|Serving Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### Nabewerkingsprocessen portaal met financiële impact (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Triggering Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|Serving Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### Wijzigen/intrekken beëindigen dienstverband (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|Serving Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### Namens manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||

[Up](#(doorstroom)-doorstroom)

### Wijzigen aanstellingsgegevens (Business Process)

Op moment dat bijv. tijdelijk contract afloopt moet de aanstelling gewijzigd worden.

Wordt automatisch ontslag gegenereerd wanneer geen actie wordt ondernomen.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||
|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|Serving Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||

[Up](#(doorstroom)-doorstroom)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|||

[Up](#(doorstroom)-doorstroom)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(doorstroom)-doorstroom)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(doorstroom)-doorstroom)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[Brievengenerator (Application Component)](#brievengenerator-(application-component))|||

[Up](#(doorstroom)-doorstroom)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(doorstroom)-doorstroom)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(doorstroom)-doorstroom)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(doorstroom)-doorstroom)

#### Brievengenerator (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[Brievengenerator (Application Component)](#brievengenerator-(application-component))|||

[Up](#(doorstroom)-doorstroom)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||

[Up](#(doorstroom)-doorstroom)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(doorstroom)-doorstroom)

### Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(doorstroom)-doorstroom)

### Beëindigen dienstverband (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|Serving Relationship|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|||
|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|Serving Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|Serving Relationship|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|||
|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|Realization Relationship|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|||

[Up](#(doorstroom)-doorstroom)

### Registratie personeelsgegevens (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|Realization Relationship|[Beëindigen dienstverband (Application Service)](#beëindigen-dienstverband-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|||

[Up](#(doorstroom)-doorstroom)

### Wijzigen aanstellingsgegevens (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|Serving Relationship|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||
|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||

[Up](#(doorstroom)-doorstroom)

### Wijzigen aanstelling (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|||

[Up](#(doorstroom)-doorstroom)

[embedView]: img-HR en PY service realisatie-doorstroom-Doorstroom.png
Generated: Fri Jan 31 2020 10:28:40 GMT+0100 (CET)
