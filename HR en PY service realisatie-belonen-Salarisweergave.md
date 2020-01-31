# (belonen) Salarisweergave

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [HRO (Business Role)](#hro-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))
  * [Uitvoeren correcties jaaropgaaf (Business Process)](#uitvoeren-correcties-jaaropgaaf-(business-process))
  * [Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))
  * [Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))
  * [Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))
  * [Verzenden salarisstroken (Business Process)](#verzenden-salarisstroken-(business-process))
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
  * [Simulatie salaris (Application Function)](#simulatie-salaris-(application-function))
  * [Salarissimulatie (Application Service)](#salarissimulatie-(application-service))
  * [Pardon (Application Component)](#pardon-(application-component))
  * [Genereren salarisstrook (Application Service)](#genereren-salarisstrook-(application-service))
  * [Registreren verzendwijze salarisstrook (Application Service)](#registreren-verzendwijze-salarisstrook-(application-service))
  * [Mobile Platform (Application Component)](#mobile-platform-(application-component))
  * [Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))
  * [Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))
  * [Genereren salarisstrook (Application Function)](#genereren-salarisstrook-(application-function))
  * [Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))
  * [Aanvragen werkgeversverklaring (Application Service)](#aanvragen-werkgeversverklaring-(application-service))
  * [Documentum (Application Component)](#documentum-(application-component))
    * [Pandora (Application Component)](#pandora-(application-component))
  * [Vastleggen documenten (Application Function)](#vastleggen-documenten-(application-function))
  * [Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))

## Introduction

![(belonen) Salarisweergave][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Uitvoeren correcties jaaropgaaf (Business Process)](#uitvoeren-correcties-jaaropgaaf-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Verzenden salarisstroken (Business Process)](#verzenden-salarisstroken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-salarisweergave)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|||

[Up](#(belonen)-salarisweergave)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Uitvoeren correcties jaaropgaaf (Business Process)](#uitvoeren-correcties-jaaropgaaf-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Simulatie salarisberekening (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[Salarissimulatie (Application Service)](#salarissimulatie-(application-service))|Serving Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Uitvoeren correcties jaaropgaaf (Business Process)

Handmatig proces

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitvoeren correcties jaaropgaaf (Business Process)](#uitvoeren-correcties-jaaropgaaf-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Uitvoeren correcties jaaropgaaf (Business Process)](#uitvoeren-correcties-jaaropgaaf-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Inzien salarisstrook(en) en jaaropgave (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Genereren salarisstrook (Application Service)](#genereren-salarisstrook-(application-service))|Serving Relationship|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Aanvragen werkgeversverklaring (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|Triggering Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|||
|[Aanvragen werkgeversverklaring (Application Service)](#aanvragen-werkgeversverklaring-(application-service))|Serving Relationship|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Aanvragen/beëindigen papieren salarisstrook (Business Process)

Alternatief per e-mail

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren verzendwijze salarisstrook (Application Service)](#registreren-verzendwijze-salarisstrook-(application-service))|Serving Relationship|[Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Opstellen werkgeversverklaring (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|Triggering Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||
|[Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))|Serving Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||

[Up](#(belonen)-salarisweergave)

### Verzenden salarisstroken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verzenden salarisstroken (Business Process)](#verzenden-salarisstroken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))|Triggering Relationship|[Verzenden salarisstroken (Business Process)](#verzenden-salarisstroken-(business-process))|||

[Up](#(belonen)-salarisweergave)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Realization Relationship|[Salarissimulatie (Application Service)](#salarissimulatie-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Genereren salarisstrook (Application Function)](#genereren-salarisstrook-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Realization Relationship|[Registreren verzendwijze salarisstrook (Application Service)](#registreren-verzendwijze-salarisstrook-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Realization Relationship|[Aanvragen werkgeversverklaring (Application Service)](#aanvragen-werkgeversverklaring-(application-service))|||

[Up](#(belonen)-salarisweergave)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-salarisweergave)

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

[Up](#(belonen)-salarisweergave)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-salarisweergave)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-salarisweergave)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-salarisweergave)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Assignment Relationship|[Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-salarisweergave)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Simulatie salaris (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Simulatie salaris (Application Function)](#simulatie-salaris-(application-function))|Realization Relationship|[Salarissimulatie (Application Service)](#salarissimulatie-(application-service))|||
|[Pardon (Application Component)](#pardon-(application-component))|Assignment Relationship|[Simulatie salaris (Application Function)](#simulatie-salaris-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Salarissimulatie (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Salarissimulatie (Application Service)](#salarissimulatie-(application-service))|Serving Relationship|[Simulatie salarisberekening (Business Process)](#simulatie-salarisberekening-(business-process))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Realization Relationship|[Salarissimulatie (Application Service)](#salarissimulatie-(application-service))|||
|[Simulatie salaris (Application Function)](#simulatie-salaris-(application-function))|Realization Relationship|[Salarissimulatie (Application Service)](#salarissimulatie-(application-service))|||

[Up](#(belonen)-salarisweergave)

### Pardon (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Pardon (Application Component)](#pardon-(application-component))|Assignment Relationship|[Simulatie salaris (Application Function)](#simulatie-salaris-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Genereren salarisstrook (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Genereren salarisstrook (Application Service)](#genereren-salarisstrook-(application-service))|Serving Relationship|[Inzien salarisstrook(en) en jaaropgave (Business Process)](#inzien-salarisstrook(en)-en-jaaropgave-(business-process))|||
|[Genereren salarisstrook (Application Function)](#genereren-salarisstrook-(application-function))|Realization Relationship|[Genereren salarisstrook (Application Service)](#genereren-salarisstrook-(application-service))|||

[Up](#(belonen)-salarisweergave)

### Registreren verzendwijze salarisstrook (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verzendwijze salarisstrook (Application Service)](#registreren-verzendwijze-salarisstrook-(application-service))|Serving Relationship|[Aanvragen/beëindigen papieren salarisstrook (Business Process)](#aanvragenbeëindigen-papieren-salarisstrook-(business-process))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Realization Relationship|[Registreren verzendwijze salarisstrook (Application Service)](#registreren-verzendwijze-salarisstrook-(application-service))|||

[Up](#(belonen)-salarisweergave)

### Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Autoriseren mutaties App (generiek) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|Realization Relationship|[Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Autoriseren mutaties Portaal (generiek) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|Realization Relationship|[Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Genereren salarisstrook (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Genereren salarisstrook (Application Function)](#genereren-salarisstrook-(application-function))|Realization Relationship|[Genereren salarisstrook (Application Service)](#genereren-salarisstrook-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Genereren salarisstrook (Application Function)](#genereren-salarisstrook-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Autoriseren werkgeversverklaring (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))|Serving Relationship|[Opstellen werkgeversverklaring (Business Process)](#opstellen-werkgeversverklaring-(business-process))|||
|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|Realization Relationship|[Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))|||
|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|Realization Relationship|[Autoriseren werkgeversverklaring (Application Service)](#autoriseren-werkgeversverklaring-(application-service))|||

[Up](#(belonen)-salarisweergave)

### Aanvragen werkgeversverklaring (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen werkgeversverklaring (Application Service)](#aanvragen-werkgeversverklaring-(application-service))|Serving Relationship|[Aanvragen werkgeversverklaring (Business Process)](#aanvragen-werkgeversverklaring-(business-process))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Realization Relationship|[Aanvragen werkgeversverklaring (Application Service)](#aanvragen-werkgeversverklaring-(application-service))|||

[Up](#(belonen)-salarisweergave)

### Documentum (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Documentum (Application Component)](#documentum-(application-component))|Composition Relationship|[Pandora (Application Component)](#pandora-(application-component))|||

[Up](#(belonen)-salarisweergave)

#### Pandora (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Pandora (Application Component)](#pandora-(application-component))|Assignment Relationship|[Vastleggen documenten (Application Function)](#vastleggen-documenten-(application-function))|||
|[Documentum (Application Component)](#documentum-(application-component))|Composition Relationship|[Pandora (Application Component)](#pandora-(application-component))|||

[Up](#(belonen)-salarisweergave)

### Vastleggen documenten (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Pandora (Application Component)](#pandora-(application-component))|Assignment Relationship|[Vastleggen documenten (Application Function)](#vastleggen-documenten-(application-function))|||
|[Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))|Triggering Relationship|[Vastleggen documenten (Application Function)](#vastleggen-documenten-(application-function))|||

[Up](#(belonen)-salarisweergave)

### Genereren salarisstroken (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))|Triggering Relationship|[Vastleggen documenten (Application Function)](#vastleggen-documenten-(application-function))|||
|[Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))|Triggering Relationship|[Verzenden salarisstroken (Business Process)](#verzenden-salarisstroken-(business-process))|||
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Assignment Relationship|[Genereren salarisstroken (Application Function)](#genereren-salarisstroken-(application-function))|||

[Up](#(belonen)-salarisweergave)

[embedView]: img-HR en PY service realisatie-belonen-Salarisweergave.png
Generated: Fri Jan 31 2020 10:28:42 GMT+0100 (CET)
