# (verlof) Verzuimregistratie

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))
  * [Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))
  * [Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))
  * [Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))
  * [Vastleggen en verwerken vangnetsituaties (Business Process)](#vastleggen-en-verwerken-vangnetsituaties-(business-process))
  * [?? Registreren werkgeversverklaring UWV ziektenaangifte (Business Process)](#??-registreren-werkgeversverklaring-uwv-ziektenaangifte-(business-process))
  * [Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))
  * [HRO (Business Role)](#hro-(business-role))
  * [Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))
  * [Casemanager Verzuim (Business Role)](#casemanager-verzuim-(business-role))
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
  * [Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))
  * [Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))
  * [Registratie casemanager (Application Function)](#registratie-casemanager-(application-function))
  * [Registreren casemanager (Application Service)](#registreren-casemanager-(application-service))
  * [Beheren poortwachter (Application Service)](#beheren-poortwachter-(application-service))
  * [Registratie poortwachter (Application Function)](#registratie-poortwachter-(application-function))
  * [Aanvragen WIA (Application Service)](#aanvragen-wia-(application-service))
  * [Registratie WIA (Application Function)](#registratie-wia-(application-function))
  * [Inzage verzuim (Application Service)](#inzage-verzuim-(application-service))

## Introduction

![(verlof) Verzuimregistratie][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Verlof en verzuim (Business Service)

Betreft alles rondom tijdsadministratie.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#(verlof)-verzuimregistratie)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Registreren verzuim (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))|Serving Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Corrigeren verzuimgegevens (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|||
|[Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))|Serving Relationship|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Corrigeren casemanager (Business Process)

Manager is de standaard casemanager, dit proces voor afwijkingen

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|||
|[Registreren casemanager (Application Service)](#registreren-casemanager-(application-service))|Serving Relationship|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Poortwachter beheren (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Casemanager Verzuim (Business Role)](#casemanager-verzuim-(business-role))|Assignment Relationship|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|||
|[Beheren poortwachter (Application Service)](#beheren-poortwachter-(application-service))|Serving Relationship|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Vastleggen en verwerken vangnetsituaties (Business Process)

Handmatig proces, vervangen door UWV Interface. Wordt gebruikt indien vergeten bij aanstelling.

Als ik het goed begrijp:
- Post komt binnen van het UWV
- Medewerker berekent SV-loon (handmatig)
- Vier ogen controle
- Mail naar P-Direkt P-dossier exchange
- Opnemen in P-dossier (ander proces)

### ?? Registreren werkgeversverklaring UWV ziektenaangifte (Business Process)

Staat niets over in kennistool

### Aanvragen WIA uitkering (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|||
|[Aanvragen WIA (Application Service)](#aanvragen-wia-(application-service))|Serving Relationship|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Raadplegen verzuim (Business Process)

Als los proces opgenomen omdat sommige mutaties in de SAP-backend worden gedaan. Er wordt hier actief verwezen naar het inzien van de huidige stand van zaken via het portaal.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|||
|[Inzage verzuim (Application Service)](#inzage-verzuim-(application-service))|Serving Relationship|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

### Casemanager Verzuim (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Casemanager Verzuim (Business Role)](#casemanager-verzuim-(business-role))|Assignment Relationship|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|||

[Up](#(verlof)-verzuimregistratie)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie casemanager (Application Function)](#registratie-casemanager-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie poortwachter (Application Function)](#registratie-poortwachter-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie WIA (Application Function)](#registratie-wia-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(verlof)-verzuimregistratie)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(verlof)-verzuimregistratie)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(verlof)-verzuimregistratie)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(verlof)-verzuimregistratie)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Registreren verzuim (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))|Serving Relationship|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|||
|[Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))|Serving Relationship|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|||
|[Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))|Realization Relationship|[Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))|||

[Up](#(verlof)-verzuimregistratie)

### Registratie verzuim (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))|Realization Relationship|[Registreren verzuim (Application Service)](#registreren-verzuim-(application-service))|||
|[Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))|Realization Relationship|[Inzage verzuim (Application Service)](#inzage-verzuim-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Registratie casemanager (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie casemanager (Application Function)](#registratie-casemanager-(application-function))|Realization Relationship|[Registreren casemanager (Application Service)](#registreren-casemanager-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie casemanager (Application Function)](#registratie-casemanager-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Registreren casemanager (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren casemanager (Application Service)](#registreren-casemanager-(application-service))|Serving Relationship|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|||
|[Registratie casemanager (Application Function)](#registratie-casemanager-(application-function))|Realization Relationship|[Registreren casemanager (Application Service)](#registreren-casemanager-(application-service))|||

[Up](#(verlof)-verzuimregistratie)

### Beheren poortwachter (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beheren poortwachter (Application Service)](#beheren-poortwachter-(application-service))|Serving Relationship|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|||
|[Registratie poortwachter (Application Function)](#registratie-poortwachter-(application-function))|Realization Relationship|[Beheren poortwachter (Application Service)](#beheren-poortwachter-(application-service))|||

[Up](#(verlof)-verzuimregistratie)

### Registratie poortwachter (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie poortwachter (Application Function)](#registratie-poortwachter-(application-function))|Realization Relationship|[Beheren poortwachter (Application Service)](#beheren-poortwachter-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie poortwachter (Application Function)](#registratie-poortwachter-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Aanvragen WIA (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen WIA (Application Service)](#aanvragen-wia-(application-service))|Serving Relationship|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|||
|[Registratie WIA (Application Function)](#registratie-wia-(application-function))|Realization Relationship|[Aanvragen WIA (Application Service)](#aanvragen-wia-(application-service))|||

[Up](#(verlof)-verzuimregistratie)

### Registratie WIA (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie WIA (Application Function)](#registratie-wia-(application-function))|Realization Relationship|[Aanvragen WIA (Application Service)](#aanvragen-wia-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie WIA (Application Function)](#registratie-wia-(application-function))|||

[Up](#(verlof)-verzuimregistratie)

### Inzage verzuim (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Inzage verzuim (Application Service)](#inzage-verzuim-(application-service))|Serving Relationship|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|||
|[Registratie verzuim (Application Function)](#registratie-verzuim-(application-function))|Realization Relationship|[Inzage verzuim (Application Service)](#inzage-verzuim-(application-service))|||

[Up](#(verlof)-verzuimregistratie)

[embedView]: img-HR en PY service realisatie-verlof-Verzuimregistratie.png
Generated: Fri Jan 31 2020 10:28:43 GMT+0100 (CET)
