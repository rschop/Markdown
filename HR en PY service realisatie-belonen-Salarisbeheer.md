# (belonen) Salarisbeheer

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))
  * [Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))
  * [Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))
  * [Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))
  * [Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))
  * [HRO (Business Role)](#hro-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
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
  * [Registratie salaris (Application Function)](#registratie-salaris-(application-function))
  * [Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))
  * [Registratie extra beloning (Application Function)](#registratie-extra-beloning-(application-function))
  * [Bewerken extra beloning (Application Service)](#bewerken-extra-beloning-(application-service))
  * [Registratie blokkade salaris (Application Function)](#registratie-blokkade-salaris-(application-function))
  * [Bewerken blokkade salaris (Application Service)](#bewerken-blokkade-salaris-(application-service))

## Introduction

![(belonen) Salarisbeheer][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-salarisbeheer)

### Wijzigen salarisschaal (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|||
|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|Serving Relationship|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### Wijzigen salaristrede (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|||
|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|Serving Relationship|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### Toekennen/wijzigen extra beloning (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|||
|[Bewerken extra beloning (Application Service)](#bewerken-extra-beloning-(application-service))|Serving Relationship|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### Wijzigen basissalaris (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|||
|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|Serving Relationship|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### Salaris (de)blokkeren (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|||
|[Bewerken blokkade salaris (Application Service)](#bewerken-blokkade-salaris-(application-service))|Serving Relationship|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|||

[Up](#(belonen)-salarisbeheer)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|||

[Up](#(belonen)-salarisbeheer)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie extra beloning (Application Function)](#registratie-extra-beloning-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie blokkade salaris (Application Function)](#registratie-blokkade-salaris-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-salarisbeheer)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-salarisbeheer)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-salarisbeheer)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-salarisbeheer)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Registratie salaris (Application Function)

Verzamelfunctie voor salarisregistratie

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Bewerken salaris (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|Serving Relationship|[Wijzigen salarisschaal (Business Process)](#wijzigen-salarisschaal-(business-process))|||
|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|Serving Relationship|[Wijzigen salaristrede (Business Process)](#wijzigen-salaristrede-(business-process))|||
|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|Serving Relationship|[Wijzigen basissalaris (Business Process)](#wijzigen-basissalaris-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Bewerken salaris (Application Service)](#bewerken-salaris-(application-service))|||

[Up](#(belonen)-salarisbeheer)

### Registratie extra beloning (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie extra beloning (Application Function)](#registratie-extra-beloning-(application-function))|Realization Relationship|[Bewerken extra beloning (Application Service)](#bewerken-extra-beloning-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie extra beloning (Application Function)](#registratie-extra-beloning-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Bewerken extra beloning (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken extra beloning (Application Service)](#bewerken-extra-beloning-(application-service))|Serving Relationship|[Toekennen/wijzigen extra beloning (Business Process)](#toekennenwijzigen-extra-beloning-(business-process))|||
|[Registratie extra beloning (Application Function)](#registratie-extra-beloning-(application-function))|Realization Relationship|[Bewerken extra beloning (Application Service)](#bewerken-extra-beloning-(application-service))|||

[Up](#(belonen)-salarisbeheer)

### Registratie blokkade salaris (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie blokkade salaris (Application Function)](#registratie-blokkade-salaris-(application-function))|Realization Relationship|[Bewerken blokkade salaris (Application Service)](#bewerken-blokkade-salaris-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie blokkade salaris (Application Function)](#registratie-blokkade-salaris-(application-function))|||

[Up](#(belonen)-salarisbeheer)

### Bewerken blokkade salaris (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken blokkade salaris (Application Service)](#bewerken-blokkade-salaris-(application-service))|Serving Relationship|[Salaris (de)blokkeren (Business Process)](#salaris-(de)blokkeren-(business-process))|||
|[Registratie blokkade salaris (Application Function)](#registratie-blokkade-salaris-(application-function))|Realization Relationship|[Bewerken blokkade salaris (Application Service)](#bewerken-blokkade-salaris-(application-service))|||

[Up](#(belonen)-salarisbeheer)

[embedView]: img-HR en PY service realisatie-belonen-Salarisbeheer.png
Generated: Fri Jan 31 2020 10:28:44 GMT+0100 (CET)
