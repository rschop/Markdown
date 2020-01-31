# (belonen) Voorschotten, vorderingen en korting

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [HRO (Business Role)](#hro-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))
  * [Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))
  * [Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))
  * [Vordering salaris (Business Process)](#vordering-salaris-(business-process))
  * [Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))
  * [Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))
  * [Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))
  * [Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))
  * [Beslaglegger (Business Role)](#beslaglegger-(business-role))
* [Applicatie (Diagram Model Group)](#applicatie-(diagram-model-group))
  * [Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))
  * [Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))
  * [SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))
    * [SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))
    * [SAP Time Management (Application Component)](#sap-time-management-(application-component))
    * [SAP Payroll (Application Component)](#sap-payroll-(application-component))
  * [SAP GUI (Application Component)](#sap-gui-(application-component))
  * [Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))
  * [Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))
  * [ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))
  * [Registreren vordering (Application Service)](#registreren-vordering-(application-service))
  * [Registreren salariskorting (Application Service)](#registreren-salariskorting-(application-service))
  * [Registratie salaris (Application Function)](#registratie-salaris-(application-function))
  * [Registreren disciplinaire straf/ordemaatregel (Application Service)](#registreren-disciplinaire-strafordemaatregel-(application-service))
  * [Registreren inhoudingen en contributies (Application Service)](#registreren-inhoudingen-en-contributies-(application-service))
  * [Registreren loonbeslag (Application Service)](#registreren-loonbeslag-(application-service))

## Introduction

![(belonen) Voorschotten, vorderingen en korting][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Voorschot verstrekken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|||
|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|Serving Relationship|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Voorschot afrekenen (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|||
|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|Serving Relationship|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Voorschot afrekenen intrekken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|||
|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|Serving Relationship|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Vordering salaris (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[Registreren vordering (Application Service)](#registreren-vordering-(application-service))|Serving Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Korten salaris wegens ziekte (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|||
|[Registreren salariskorting (Application Service)](#registreren-salariskorting-(application-service))|Serving Relationship|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren disciplinaire straf/ordemaatregel (Business Process)

De volgende subprocessen kunnen hiervoor worden geïdentificeerd, maar wordt gezien als één proces:
Extra beloning corrigeren-Disciplinaire straf salarisschaal/periodiek
Extra beloning corrigeren-Disciplinaire straf salaris
Disciplinaire straf salarisschaal/periodiek
Salaris overige mutaties-Aanvragen disciplinaire straf
Functievervulling overige mutaties-Disciplinaire straf salarisschaal/periodiek
Functievervulling overige mutaties-Disciplinaire straf salaris

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))|||
|[Registreren disciplinaire straf/ordemaatregel (Application Service)](#registreren-disciplinaire-strafordemaatregel-(application-service))|Serving Relationship|[Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren inhoudingen en contributies (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren inhoudingen en contributies (Application Service)](#registreren-inhoudingen-en-contributies-(application-service))|Serving Relationship|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren loonbeslag (Business Process)

https://www.p-direkt.nl/informatie-rijkspersoneel/financien/salaris/schulden-en-loonbeslag

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|||
|[Beslaglegger (Business Role)](#beslaglegger-(business-role))|Assignment Relationship|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|||
|[Registreren loonbeslag (Application Service)](#registreren-loonbeslag-(application-service))|Serving Relationship|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Beslaglegger (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beslaglegger (Business Role)](#beslaglegger-(business-role))|Assignment Relationship|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

## Applicatie (Diagram Model Group)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren voorschotten (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|Serving Relationship|[Voorschot verstrekken (Business Process)](#voorschot-verstrekken-(business-process))|||
|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|Serving Relationship|[Voorschot afrekenen (Business Process)](#voorschot-afrekenen-(business-process))|||
|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|Serving Relationship|[Voorschot afrekenen intrekken (Business Process)](#voorschot-afrekenen-intrekken-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren vordering (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren vordering (Application Service)](#registreren-vordering-(application-service))|Serving Relationship|[Vordering salaris (Business Process)](#vordering-salaris-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren vordering (Application Service)](#registreren-vordering-(application-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren salariskorting (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren salariskorting (Application Service)](#registreren-salariskorting-(application-service))|Serving Relationship|[Korten salaris wegens ziekte (Business Process)](#korten-salaris-wegens-ziekte-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren salariskorting (Application Service)](#registreren-salariskorting-(application-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registratie salaris (Application Function)

Verzamelfunctie voor salarisregistratie

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren salariskorting (Application Service)](#registreren-salariskorting-(application-service))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren voorschotten (Application Service)](#registreren-voorschotten-(application-service))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren vordering (Application Service)](#registreren-vordering-(application-service))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren disciplinaire straf/ordemaatregel (Application Service)](#registreren-disciplinaire-strafordemaatregel-(application-service))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren inhoudingen en contributies (Application Service)](#registreren-inhoudingen-en-contributies-(application-service))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren loonbeslag (Application Service)](#registreren-loonbeslag-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren disciplinaire straf/ordemaatregel (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren disciplinaire straf/ordemaatregel (Application Service)](#registreren-disciplinaire-strafordemaatregel-(application-service))|Serving Relationship|[Registreren disciplinaire straf/ordemaatregel (Business Process)](#registreren-disciplinaire-strafordemaatregel-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren disciplinaire straf/ordemaatregel (Application Service)](#registreren-disciplinaire-strafordemaatregel-(application-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren inhoudingen en contributies (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren inhoudingen en contributies (Application Service)](#registreren-inhoudingen-en-contributies-(application-service))|Serving Relationship|[Registreren inhoudingen en contributies (Business Process)](#registreren-inhoudingen-en-contributies-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren inhoudingen en contributies (Application Service)](#registreren-inhoudingen-en-contributies-(application-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

### Registreren loonbeslag (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren loonbeslag (Application Service)](#registreren-loonbeslag-(application-service))|Serving Relationship|[Registreren loonbeslag (Business Process)](#registreren-loonbeslag-(business-process))|||
|[Registratie salaris (Application Function)](#registratie-salaris-(application-function))|Realization Relationship|[Registreren loonbeslag (Application Service)](#registreren-loonbeslag-(application-service))|||

[Up](#(belonen)-voorschotten,-vorderingen-en-korting)

[embedView]: img-HR en PY service realisatie-belonen-Voorschotten,-vorderingen-en-korting.png
Generated: Fri Jan 31 2020 10:28:39 GMT+0100 (CET)
