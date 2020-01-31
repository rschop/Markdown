# Portaaldiensten generiek

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Contact opnemen portaalformulier (Business Process)](#contact-opnemen-portaalformulier-(business-process))
  * [Bekijken taken en meldingen (Business Process)](#bekijken-taken-en-meldingen-(business-process))
  * [Activeren P-Direkt app (Business Process)](#activeren-p-direkt-app-(business-process))
  * [Terugbelverzoek (Business Process)](#terugbelverzoek-(business-process))
  * [Notificatie per e-mail (Business Process)](#notificatie-per-e-mail-(business-process))
  * [Track & Trace procesvoortgang (Business Process)](#track-&-trace-procesvoortgang-(business-process))
  * [?? Contact per chat (Business Process)](#??-contact-per-chat-(business-process))
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
  * [Registratie contact (Application Function)](#registratie-contact-(application-function))
  * [Contactformulier (Application Service)](#contactformulier-(application-service))
  * [Registratie taken en meldingen (Application Function)](#registratie-taken-en-meldingen-(application-function))
  * [Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))
  * [Mobile Platform (Application Component)](#mobile-platform-(application-component))
  * [Activatie app (mobiel) (Application Function)](#activatie-app-(mobiel)-(application-function))
  * [Activatie P-Direkt app (Application Service)](#activatie-p-direkt-app-(application-service))
  * [Activatie app (portaal) (Application Function)](#activatie-app-(portaal)-(application-function))
  * [Activatiecodes opleveren (Application Service)](#activatiecodes-opleveren-(application-service))
* [?? (Mijn) ingediende (medewerkers)aanvragen (Business Process)](#??-(mijn)-ingediende-(medewerkers)aanvragen-(business-process))

## Introduction

![Portaaldiensten generiek][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Contact opnemen portaalformulier (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Contactformulier (Application Service)](#contactformulier-(application-service))|Serving Relationship|[Contact opnemen portaalformulier (Business Process)](#contact-opnemen-portaalformulier-(business-process))|||

[Up](#portaaldiensten-generiek)

### Bekijken taken en meldingen (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))|Serving Relationship|[Bekijken taken en meldingen (Business Process)](#bekijken-taken-en-meldingen-(business-process))|||

[Up](#portaaldiensten-generiek)

### Activeren P-Direkt app (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Activatie P-Direkt app (Application Service)](#activatie-p-direkt-app-(application-service))|Serving Relationship|[Activeren P-Direkt app (Business Process)](#activeren-p-direkt-app-(business-process))|||
|[Activatiecodes opleveren (Application Service)](#activatiecodes-opleveren-(application-service))|Serving Relationship|[Activeren P-Direkt app (Business Process)](#activeren-p-direkt-app-(business-process))|||

[Up](#portaaldiensten-generiek)

### Terugbelverzoek (Business Process)

### Notificatie per e-mail (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))|Serving Relationship|[Notificatie per e-mail (Business Process)](#notificatie-per-e-mail-(business-process))|||

[Up](#portaaldiensten-generiek)

### Track & Trace procesvoortgang (Business Process)

### ?? Contact per chat (Business Process)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie contact (Application Function)](#registratie-contact-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie taken en meldingen (Application Function)](#registratie-taken-en-meldingen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Activatie app (portaal) (Application Function)](#activatie-app-(portaal)-(application-function))|||

[Up](#portaaldiensten-generiek)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#portaaldiensten-generiek)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#portaaldiensten-generiek)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#portaaldiensten-generiek)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#portaaldiensten-generiek)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#portaaldiensten-generiek)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#portaaldiensten-generiek)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#portaaldiensten-generiek)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#portaaldiensten-generiek)

### Registratie contact (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie contact (Application Function)](#registratie-contact-(application-function))|Realization Relationship|[Contactformulier (Application Service)](#contactformulier-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie contact (Application Function)](#registratie-contact-(application-function))|||

[Up](#portaaldiensten-generiek)

### Contactformulier (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Contactformulier (Application Service)](#contactformulier-(application-service))|Serving Relationship|[Contact opnemen portaalformulier (Business Process)](#contact-opnemen-portaalformulier-(business-process))|||
|[Registratie contact (Application Function)](#registratie-contact-(application-function))|Realization Relationship|[Contactformulier (Application Service)](#contactformulier-(application-service))|||

[Up](#portaaldiensten-generiek)

### Registratie taken en meldingen (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie taken en meldingen (Application Function)](#registratie-taken-en-meldingen-(application-function))|Realization Relationship|[Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie taken en meldingen (Application Function)](#registratie-taken-en-meldingen-(application-function))|||

[Up](#portaaldiensten-generiek)

### Mijn taken en meldingen (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))|Serving Relationship|[Bekijken taken en meldingen (Business Process)](#bekijken-taken-en-meldingen-(business-process))|||
|[Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))|Serving Relationship|[Notificatie per e-mail (Business Process)](#notificatie-per-e-mail-(business-process))|||
|[Registratie taken en meldingen (Application Function)](#registratie-taken-en-meldingen-(application-function))|Realization Relationship|[Mijn taken en meldingen (Application Service)](#mijn-taken-en-meldingen-(application-service))|||

[Up](#portaaldiensten-generiek)

### Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Activatie app (mobiel) (Application Function)](#activatie-app-(mobiel)-(application-function))|||

[Up](#portaaldiensten-generiek)

### Activatie app (mobiel) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Activatie app (mobiel) (Application Function)](#activatie-app-(mobiel)-(application-function))|Realization Relationship|[Activatie P-Direkt app (Application Service)](#activatie-p-direkt-app-(application-service))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Activatie app (mobiel) (Application Function)](#activatie-app-(mobiel)-(application-function))|||

[Up](#portaaldiensten-generiek)

### Activatie P-Direkt app (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Activatie P-Direkt app (Application Service)](#activatie-p-direkt-app-(application-service))|Serving Relationship|[Activeren P-Direkt app (Business Process)](#activeren-p-direkt-app-(business-process))|||
|[Activatie app (mobiel) (Application Function)](#activatie-app-(mobiel)-(application-function))|Realization Relationship|[Activatie P-Direkt app (Application Service)](#activatie-p-direkt-app-(application-service))|||

[Up](#portaaldiensten-generiek)

### Activatie app (portaal) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Activatie app (portaal) (Application Function)](#activatie-app-(portaal)-(application-function))|Realization Relationship|[Activatiecodes opleveren (Application Service)](#activatiecodes-opleveren-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Activatie app (portaal) (Application Function)](#activatie-app-(portaal)-(application-function))|||

[Up](#portaaldiensten-generiek)

### Activatiecodes opleveren (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Activatiecodes opleveren (Application Service)](#activatiecodes-opleveren-(application-service))|Serving Relationship|[Activeren P-Direkt app (Business Process)](#activeren-p-direkt-app-(business-process))|||
|[Activatie app (portaal) (Application Function)](#activatie-app-(portaal)-(application-function))|Realization Relationship|[Activatiecodes opleveren (Application Service)](#activatiecodes-opleveren-(application-service))|||

[Up](#portaaldiensten-generiek)

## ?? (Mijn) ingediende (medewerkers)aanvragen (Business Process)

[embedView]: img-HR en PY service realisatie-Portaaldiensten-generiek.png
Generated: Fri Jan 31 2020 10:28:40 GMT+0100 (CET)
