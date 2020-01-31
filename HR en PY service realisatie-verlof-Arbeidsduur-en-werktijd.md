# (verlof) Arbeidsduur en werktijd

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))
  * [Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))
  * [Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [HRO (Business Role)](#hro-(business-role))
  * [Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))
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
  * [Registratie arbeidsduur en werktijd (Application Function)](#registratie-arbeidsduur-en-werktijd-(application-function))
  * [Registratie PAS (Application Function)](#registratie-pas-(application-function))
  * [Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))
  * [Registreren PAS (Application Service)](#registreren-pas-(application-service))

## Introduction

![(verlof) Arbeidsduur en werktijd][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Registreren arbeidsduur, werktijd en rooster (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))|Serving Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Registreren PAS-regeling (Business Process)

Partiële Arbeidsparticipatie Senioren

Uitzonderingen PAS (documentatie CC):
- Rechterlijke macht/Rechtspraak: 2 PAS-regelingen. Voor 57+ (kleine PAS) en 61+ (grote PAS).
- 1e & 2e kamer: Personenchauffeurs ontvangen een periodieke toelage
- MinDef: voor hen geld burgerlijk ambtenarenreglement Defensie met soortgelijke regeling. Medewerkers die met Rijksvastgoed naar BZK zijn gegaan vallen nu onder ARAR
- I&M: PAS-formulier gaat eerst langs roosterbeheerder

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||
|[Registreren PAS (Application Service)](#registreren-pas-(application-service))|Serving Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Corrigeren arbeidsduur/werktijd/PAS (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))|Serving Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[Registreren PAS (Application Service)](#registreren-pas-(application-service))|Serving Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Verlof en verzuim (Business Service)

Betreft alles rondom tijdsadministratie.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie arbeidsduur en werktijd (Application Function)](#registratie-arbeidsduur-en-werktijd-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie PAS (Application Function)](#registratie-pas-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Registratie arbeidsduur en werktijd (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie arbeidsduur en werktijd (Application Function)](#registratie-arbeidsduur-en-werktijd-(application-function))|Realization Relationship|[Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie arbeidsduur en werktijd (Application Function)](#registratie-arbeidsduur-en-werktijd-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Registratie PAS (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie PAS (Application Function)](#registratie-pas-(application-function))|Realization Relationship|[Registreren PAS (Application Service)](#registreren-pas-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie PAS (Application Function)](#registratie-pas-(application-function))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Registreren arbeidsduur en werktijd (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))|Serving Relationship|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|||
|[Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))|Serving Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[Registratie arbeidsduur en werktijd (Application Function)](#registratie-arbeidsduur-en-werktijd-(application-function))|Realization Relationship|[Registreren arbeidsduur en werktijd (Application Service)](#registreren-arbeidsduur-en-werktijd-(application-service))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

### Registreren PAS (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren PAS (Application Service)](#registreren-pas-(application-service))|Serving Relationship|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|||
|[Registreren PAS (Application Service)](#registreren-pas-(application-service))|Serving Relationship|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|||
|[Registratie PAS (Application Function)](#registratie-pas-(application-function))|Realization Relationship|[Registreren PAS (Application Service)](#registreren-pas-(application-service))|||

[Up](#(verlof)-arbeidsduur-en-werktijd)

[embedView]: img-HR en PY service realisatie-verlof-Arbeidsduur-en-werktijd.png
Generated: Fri Jan 31 2020 10:28:39 GMT+0100 (CET)
