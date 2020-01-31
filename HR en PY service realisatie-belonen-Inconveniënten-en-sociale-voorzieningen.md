# (belonen) Inconveniënten en sociale voorzieningen

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [HRO (Business Role)](#hro-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))
  * [Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))
  * [Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))
  * [Handmatige check gemoedsbezwaarde (Business Process)](#handmatige-check-gemoedsbezwaarde-(business-process))
  * [Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))
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
  * [Mobile Platform (Application Component)](#mobile-platform-(application-component))
  * [Registreren pensioen (Application Service)](#registreren-pensioen-(application-service))
  * [Registratie pensioen (Application Function)](#registratie-pensioen-(application-function))
  * [Registreren gemoedsbezwaarde (Application Service)](#registreren-gemoedsbezwaarde-(application-service))
  * [Registratie gemoedsbezwaarde (Application Function)](#registratie-gemoedsbezwaarde-(application-function))
  * [Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))
  * [Emailen doelgroepverklaring (Application Function)](#emailen-doelgroepverklaring-(application-function))
  * [Correctie jaarinkomen pensioen (Application Service)](#correctie-jaarinkomen-pensioen-(application-service))

## Introduction

![(belonen) Inconveniënten en sociale voorzieningen][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### HRO (Business Role)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Handmatige check gemoedsbezwaarde (Business Process)](#handmatige-check-gemoedsbezwaarde-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registreren extra pensioen (Business Process)

Ook partnerplus pensioen, maar die term bestaat niet binnen Kennis Direct Tool.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|||
|[Registreren pensioen (Application Service)](#registreren-pensioen-(application-service))|Serving Relationship|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Corrigeren jaarinkomen pensioen (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))|||
|[Correctie jaarinkomen pensioen (Application Service)](#correctie-jaarinkomen-pensioen-(application-service))|Serving Relationship|[Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registreren gemoedsbezwaarde (Business Process)

Tekstveld in portaal. Handmatige check.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|Triggering Relationship|[Handmatige check gemoedsbezwaarde (Business Process)](#handmatige-check-gemoedsbezwaarde-(business-process))|||
|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|||
|[Registreren gemoedsbezwaarde (Application Service)](#registreren-gemoedsbezwaarde-(application-service))|Serving Relationship|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Handmatige check gemoedsbezwaarde (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|Triggering Relationship|[Handmatige check gemoedsbezwaarde (Business Process)](#handmatige-check-gemoedsbezwaarde-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Handmatige check gemoedsbezwaarde (Business Process)](#handmatige-check-gemoedsbezwaarde-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registreren doelgroepverklaring (Business Process)

Dit is een email met onderwerp "registreren doelgroepverklaring" en bijlage UWV-formulier

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))|Serving Relationship|[Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie pensioen (Application Function)](#registratie-pensioen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie gemoedsbezwaarde (Application Function)](#registratie-gemoedsbezwaarde-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Emailen doelgroepverklaring (Application Function)](#emailen-doelgroepverklaring-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Correctie jaarinkomen pensioen (Application Service)](#correctie-jaarinkomen-pensioen-(application-service))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registreren pensioen (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren pensioen (Application Service)](#registreren-pensioen-(application-service))|Serving Relationship|[Registreren extra pensioen (Business Process)](#registreren-extra-pensioen-(business-process))|||
|[Registratie pensioen (Application Function)](#registratie-pensioen-(application-function))|Realization Relationship|[Registreren pensioen (Application Service)](#registreren-pensioen-(application-service))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registratie pensioen (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie pensioen (Application Function)](#registratie-pensioen-(application-function))|Realization Relationship|[Registreren pensioen (Application Service)](#registreren-pensioen-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie pensioen (Application Function)](#registratie-pensioen-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registreren gemoedsbezwaarde (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren gemoedsbezwaarde (Application Service)](#registreren-gemoedsbezwaarde-(application-service))|Serving Relationship|[Registreren gemoedsbezwaarde (Business Process)](#registreren-gemoedsbezwaarde-(business-process))|||
|[Registratie gemoedsbezwaarde (Application Function)](#registratie-gemoedsbezwaarde-(application-function))|Realization Relationship|[Registreren gemoedsbezwaarde (Application Service)](#registreren-gemoedsbezwaarde-(application-service))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registratie gemoedsbezwaarde (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie gemoedsbezwaarde (Application Function)](#registratie-gemoedsbezwaarde-(application-function))|Realization Relationship|[Registreren gemoedsbezwaarde (Application Service)](#registreren-gemoedsbezwaarde-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie gemoedsbezwaarde (Application Function)](#registratie-gemoedsbezwaarde-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Registreren doelgroepverklaring (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))|Serving Relationship|[Registreren doelgroepverklaring (Business Process)](#registreren-doelgroepverklaring-(business-process))|||
|[Emailen doelgroepverklaring (Application Function)](#emailen-doelgroepverklaring-(application-function))|Realization Relationship|[Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Emailen doelgroepverklaring (Application Function)

Dit is een email met onderwerp "registreren doelgroepverklaring" en bijlage UWV-formulier

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Emailen doelgroepverklaring (Application Function)](#emailen-doelgroepverklaring-(application-function))|Realization Relationship|[Registreren doelgroepverklaring (Application Service)](#registreren-doelgroepverklaring-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Emailen doelgroepverklaring (Application Function)](#emailen-doelgroepverklaring-(application-function))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

### Correctie jaarinkomen pensioen (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Correctie jaarinkomen pensioen (Application Service)](#correctie-jaarinkomen-pensioen-(application-service))|Serving Relationship|[Corrigeren jaarinkomen pensioen (Business Process)](#corrigeren-jaarinkomen-pensioen-(business-process))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Correctie jaarinkomen pensioen (Application Service)](#correctie-jaarinkomen-pensioen-(application-service))|||

[Up](#(belonen)-inconveniënten-en-sociale-voorzieningen)

[embedView]: img-HR en PY service realisatie-belonen-Inconveniënten-en-sociale-voorzieningen.png
Generated: Fri Jan 31 2020 10:28:37 GMT+0100 (CET)
