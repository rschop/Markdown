# (instroom) Instroom

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Instroom (Business Service)](#instroom-(business-service))
  * [Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))
  * [Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))
    * [Overplaatsen medewerker (Business Process)](#overplaatsen-medewerker-(business-process))
    * [Administratieve aanstelling nieuwe medewerker (Business Process)](#administratieve-aanstelling-nieuwe-medewerker-(business-process))
    * [Juridische aanstelling nieuwe medewerker (Business Process)](#juridische-aanstelling-nieuwe-medewerker-(business-process))
  * [Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))
  * [Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))
  * [Manager (Business Role)](#manager-(business-role))
  * [Namens manager (Business Role)](#namens-manager-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [HRO (Business Role)](#hro-(business-role))
  * [Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))
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
  * [Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))
  * [Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))
  * [Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))
  * [Registreren arbeidsverleden (Application Service)](#registreren-arbeidsverleden-(application-service))
  * [Registratie arbeidsverleden (Application Function)](#registratie-arbeidsverleden-(application-function))
  * [Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))
  * [Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))
  * [Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))

## Introduction

![(instroom) Instroom][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Instroom (Business Service)

WNRA gaat hier wijzigingen in aanbrengen

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#(instroom)-instroom)

### Registreren nieuwe medewerker (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Triggering Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))|Serving Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||

[Up](#(instroom)-instroom)

### Aanstellen nieuwe medewerker (Business Process)

Gaan meldingen naar UWV

VOG, WID-scan

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Overplaatsen medewerker (Business Process)](#overplaatsen-medewerker-(business-process))|Specialization Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Administratieve aanstelling nieuwe medewerker (Business Process)](#administratieve-aanstelling-nieuwe-medewerker-(business-process))|Specialization Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Juridische aanstelling nieuwe medewerker (Business Process)](#juridische-aanstelling-nieuwe-medewerker-(business-process))|Specialization Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))|Serving Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Triggering Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#(instroom)-instroom)

#### Overplaatsen medewerker (Business Process)

Overplaatsing binnen departement

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Overplaatsen medewerker (Business Process)](#overplaatsen-medewerker-(business-process))|Specialization Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#(instroom)-instroom)

#### Administratieve aanstelling nieuwe medewerker (Business Process)

Interdepartementale overplaatsing

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Administratieve aanstelling nieuwe medewerker (Business Process)](#administratieve-aanstelling-nieuwe-medewerker-(business-process))|Specialization Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#(instroom)-instroom)

#### Juridische aanstelling nieuwe medewerker (Business Process)

Nieuwe aanstelling van buiten Rijksoverheid

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Juridische aanstelling nieuwe medewerker (Business Process)](#juridische-aanstelling-nieuwe-medewerker-(business-process))|Specialization Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#(instroom)-instroom)

### Registreren Arbeidsverleden (Business Process)

Wordt meegenomen in bepalen ambtsjubileum

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Registreren arbeidsverleden (Application Service)](#registreren-arbeidsverleden-(application-service))|Serving Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||
|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|Serving Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||

[Up](#(instroom)-instroom)

### Corrigeren aanstellingsgegevens (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||
|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|Serving Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||

[Up](#(instroom)-instroom)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|||

[Up](#(instroom)-instroom)

### Namens manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[Namens manager (Business Role)](#namens-manager-(business-role))|Assignment Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#(instroom)-instroom)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|||

[Up](#(instroom)-instroom)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||

[Up](#(instroom)-instroom)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||

[Up](#(instroom)-instroom)

### Aanstelling verwijderen (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|||
|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|Serving Relationship|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|||

[Up](#(instroom)-instroom)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie arbeidsverleden (Application Function)](#registratie-arbeidsverleden-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|||

[Up](#(instroom)-instroom)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(instroom)-instroom)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(instroom)-instroom)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[Brievengenerator (Application Component)](#brievengenerator-(application-component))|||

[Up](#(instroom)-instroom)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(instroom)-instroom)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(instroom)-instroom)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(instroom)-instroom)

#### Brievengenerator (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[Brievengenerator (Application Component)](#brievengenerator-(application-component))|||

[Up](#(instroom)-instroom)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||

[Up](#(instroom)-instroom)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(instroom)-instroom)

### Registratie personeelsgegevens (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|Realization Relationship|[Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|||

[Up](#(instroom)-instroom)

### Registreren nieuwe medewerker (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))|Serving Relationship|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|||
|[Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))|Serving Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||
|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|Realization Relationship|[Registreren nieuwe medewerker (Application Service)](#registreren-nieuwe-medewerker-(application-service))|||

[Up](#(instroom)-instroom)

### Wijzigen aanstellingsgegevens (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|Serving Relationship|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|||
|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|Serving Relationship|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||
|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||

[Up](#(instroom)-instroom)

### Registreren arbeidsverleden (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren arbeidsverleden (Application Service)](#registreren-arbeidsverleden-(application-service))|Serving Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||
|[Registratie arbeidsverleden (Application Function)](#registratie-arbeidsverleden-(application-function))|Realization Relationship|[Registreren arbeidsverleden (Application Service)](#registreren-arbeidsverleden-(application-service))|||

[Up](#(instroom)-instroom)

### Registratie arbeidsverleden (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie arbeidsverleden (Application Function)](#registratie-arbeidsverleden-(application-function))|Realization Relationship|[Registreren arbeidsverleden (Application Service)](#registreren-arbeidsverleden-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie arbeidsverleden (Application Function)](#registratie-arbeidsverleden-(application-function))|||

[Up](#(instroom)-instroom)

### Registratie personeelsdossier (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|Realization Relationship|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|||

[Up](#(instroom)-instroom)

### Bewerken personeelsdossier (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|Serving Relationship|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|||
|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|Realization Relationship|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|||

[Up](#(instroom)-instroom)

### Wijzigen aanstelling (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|Realization Relationship|[Wijzigen aanstellingsgegevens (Application Service)](#wijzigen-aanstellingsgegevens-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Wijzigen aanstelling (Application Function)](#wijzigen-aanstelling-(application-function))|||

[Up](#(instroom)-instroom)

[embedView]: img-HR en PY service realisatie-instroom-Instroom.png
Generated: Fri Jan 31 2020 10:28:44 GMT+0100 (CET)
