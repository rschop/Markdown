# Applicaties en informatiestromen

* [Introduction](#introduction)
* [Uitgaand HR (Diagram Model Group)](#uitgaand-hr-(diagram-model-group))
  * [Gegevensintegratie ministeries (outbound) (Application Interface)](#gegevensintegratie-ministeries-(outbound)-(application-interface))
  * [SPX (outbound) (Application Interface)](#spx-(outbound)-(application-interface))
  * [ARBO (Application Interface)](#arbo-(application-interface))
  * [UWV (outbound) (Application Interface)](#uwv-(outbound)-(application-interface))
  * [IDM1 ministeries (outbound) (Application Interface)](#idm1-ministeries-(outbound)-(application-interface))
  * [IDM2 ministeries (outbound) (Application Interface)](#idm2-ministeries-(outbound)-(application-interface))
  * [LNV (outbound) (Application Interface)](#lnv-(outbound)-(application-interface))
  * [3W (outbound) (Application Interface)](#3w-(outbound)-(application-interface))
  * [Shuttel (Application Interface)](#shuttel-(application-interface))
  * [RBO/RSO (Application Interface)](#rborso-(application-interface))
* [Transactiekanalen (Diagram Model Group)](#transactiekanalen-(diagram-model-group))
  * [SAP GUI (Application Component)](#sap-gui-(application-component))
  * [ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))
  * [Genesys (Application Component)](#genesys-(application-component))
  * [E-mail (Application Component)](#e-mail-(application-component))
  * [Webbrowser (Application Component)](#webbrowser-(application-component))
  * [RPA Robotics Blue Prism (Application Component)](#rpa-robotics-blue-prism-(application-component))
  * [Kofax (Application Component)](#kofax-(application-component))
  * [P-Direkt app (Application Component)](#p-direkt-app-(application-component))
* [Uitgaand BW (Diagram Model Group)](#uitgaand-bw-(diagram-model-group))
  * [J&V (Application Interface)](#j&v-(application-interface))
  * [Rechtspraak (Application Interface)](#rechtspraak-(application-interface))
  * [Openbaar Min. (Application Interface)](#openbaar-min.-(application-interface))
  * [Justitie (Application Interface)](#justitie-(application-interface))
  * [3F (Application Interface)](#3f-(application-interface))
* [Uitgaand PY (Diagram Model Group)](#uitgaand-py-(diagram-model-group))
  * [Audit bestanden (Application Interface)](#audit-bestanden-(application-interface))
  * [Jaaropgaven (Application Interface)](#jaaropgaven-(application-interface))
  * [Afschrift 2e betaalmoment (Application Interface)](#afschrift-2e-betaalmoment-(application-interface))
  * [Verwerkings overzicht (Application Interface)](#verwerkings-overzicht-(application-interface))
  * [Afrekenresultaten (Application Interface)](#afrekenresultaten-(application-interface))
  * [Loonstroken (Application Interface)](#loonstroken-(application-interface))
  * [Collectieve afdrachten (Application Interface)](#collectieve-afdrachten-(application-interface))
  * [Afschrift 1e betaalmoment (Application Interface)](#afschrift-1e-betaalmoment-(application-interface))
  * [Werkkosten regeling (Application Interface)](#werkkosten-regeling-(application-interface))
  * [Blokkade overzicht (Application Interface)](#blokkade-overzicht-(application-interface))
  * [Afschrift 3e betaalmoment (Application Interface)](#afschrift-3e-betaalmoment-(application-interface))
  * [Jaarloon BZT (Application Interface)](#jaarloon-bzt-(application-interface))
  * [PCP (alleen MinFin) (Application Interface)](#pcp-(alleen-minfin)-(application-interface))
* [Inkomend HR (Diagram Model Group)](#inkomend-hr-(diagram-model-group))
  * [3W (inbound) (Application Interface)](#3w-(inbound)-(application-interface))
  * [LNV (inbound) (Application Interface)](#lnv-(inbound)-(application-interface))
  * [SPX (inbound) (Application Interface)](#spx-(inbound)-(application-interface))
  * [Gegevensintegratie ministeries (inbound) (Application Interface)](#gegevensintegratie-ministeries-(inbound)-(application-interface))
  * [IDM2 ministeries (inbound) (Application Interface)](#idm2-ministeries-(inbound)-(application-interface))
  * [IDM1 ministeries (inbound) (Application Interface)](#idm1-ministeries-(inbound)-(application-interface))
* [Tooling (Diagram Model Group)](#tooling-(diagram-model-group))
  * [ACL (Application Component)](#acl-(application-component))
  * [Query Manager (Application Component)](#query-manager-(application-component))
  * [REO-tool (oud) (Application Component)](#reo-tool-(oud)-(application-component))
  * [Pardon (Application Component)](#pardon-(application-component))
  * [Trello (handmatig) (Application Component)](#trello-(handmatig)-(application-component))
  * [Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))
  * [Kennis-Direkt Tool CC (handmatig) (Application Component)](#kennis-direkt-tool-cc-(handmatig)-(application-component))
  * [Data Sync Manager (clone&test) (Application Component)](#data-sync-manager-(clone&test)-(application-component))
  * [AND (Application Component)](#and-(application-component))
* [Inkomend PY (Diagram Model Group)](#inkomend-py-(diagram-model-group))
  * [Raad van State (inbound) (Application Interface)](#raad-van-state-(inbound)-(application-interface))
* [SAP Payroll (Application Component)](#sap-payroll-(application-component))
* [Documentum (Application Component)](#documentum-(application-component))
  * [Pandora (Application Component)](#pandora-(application-component))
  * [InBeeld (Application Component)](#inbeeld-(application-component))
  * [REO (Application Component)](#reo-(application-component))
  * [Workflow (Application Component)](#workflow-(application-component))
* [CRM (Application Component)](#crm-(application-component))
* [WFM Nice (Application Component)](#wfm-nice-(application-component))
* [Solution Manager (Application Component)](#solution-manager-(application-component))
* [Excel (Application Component)](#excel-(application-component))
* [Mobile Platform (Application Component)](#mobile-platform-(application-component))
* [SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))
* [PI (outbound) (Application Component)](#pi-(outbound)-(application-component))
* [Uitgaand HR (Diagram Model Group) 2](#uitgaand-hr-(diagram-model-group)-2)
  * [Jaartotaalbestand ministeries (Application Interface)](#jaartotaalbestand-ministeries-(application-interface))
  * [DUO (Application Interface)](#duo-(application-interface))
  * [Roosterdump EZ (Application Interface)](#roosterdump-ez-(application-interface))
  * [SZW legacy (Application Interface)](#szw-legacy-(application-interface))
* [Uitgaand PY (Diagram Model Group) 2](#uitgaand-py-(diagram-model-group)-2)
  * [BZK SMTP (Application Interface)](#bzk-smtp-(application-interface))
  * [RDW (Application Interface)](#rdw-(application-interface))
  * [Raad van State (outbound) (Application Interface)](#raad-van-state-(outbound)-(application-interface))
  * [RBS batch betaling (Application Interface)](#rbs-batch-betaling-(application-interface))
  * [Printstraat Belastingdienst (Application Interface)](#printstraat-belastingdienst-(application-interface))
  * [Fiscus Loonaangifte (Application Interface)](#fiscus-loonaangifte-(application-interface))
  * [APG pensioen (Application Interface)](#apg-pensioen-(application-interface))
* [QlicView (Application Component)](#qlicview-(application-component))
* [BW (Application Component)](#bw-(application-component))
* [Jopi (Application Component)](#jopi-(application-component))
* [SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))
* [SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))
* [Inkomend Jopi (Diagram Model Group)](#inkomend-jopi-(diagram-model-group))
  * [ABP (Etniciteit) (Application Interface)](#abp-(etniciteit)-(application-interface))
  * [1e/2e kamer personeelsbestand (Application Interface)](#1e2e-kamer-personeelsbestand-(application-interface))
  * [Ministerie van BZK (Enquetes) (Application Interface)](#ministerie-van-bzk-(enquetes)-(application-interface))
  * [Mobiliteitsbank (BOSS, Tangram, Vacatures) (Application Interface)](#mobiliteitsbank-(boss,-tangram,-vacatures)-(application-interface))
* [Tooling (Diagram Model Group) 2](#tooling-(diagram-model-group)-2)
  * [PivotalTracker (Application Component)](#pivotaltracker-(application-component))
  * [Reveille, monitoring (Application Component)](#reveille,-monitoring-(application-component))
  * [Migration Center (Application Component)](#migration-center-(application-component))
  * [Document Generator-MDPT (Application Component)](#document-generator-mdpt-(application-component))
  * [MyInsight (toekomstig) (Application Component)](#myinsight-(toekomstig)-(application-component))
* [Uitgaand BW (Junction)](#uitgaand-bw-(junction))
* [Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))
* [Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))
* [Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))
* [Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))
* [Inkomend Jopi (Junction)](#inkomend-jopi-(junction))
* [PI (inbound) (Application Component)](#pi-(inbound)-(application-component))
* [Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))
* [Junction (Junction)](#junction-(junction))
* [Junction (Junction) 2](#junction-(junction)-2)
* [Junction (Junction) 3](#junction-(junction)-3)
* [BW (inbound) (Junction)](#bw-(inbound)-(junction))
* [SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))

## Introduction

![Applicaties en informatiestromen][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Uitgaand HR (Diagram Model Group)

### Gegevensintegratie ministeries (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[Gegevensintegratie ministeries (outbound) (Application Interface)](#gegevensintegratie-ministeries-(outbound)-(application-interface))|06, 07, 08, 09||

[Up](#applicaties-en-informatiestromen)

### SPX (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[SPX (outbound) (Application Interface)](#spx-(outbound)-(application-interface))|23||

[Up](#applicaties-en-informatiestromen)

### ARBO (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[ARBO (Application Interface)](#arbo-(application-interface))|04||

[Up](#applicaties-en-informatiestromen)

### UWV (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[UWV (outbound) (Application Interface)](#uwv-(outbound)-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### IDM1 ministeries (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[IDM1 ministeries (outbound) (Application Interface)](#idm1-ministeries-(outbound)-(application-interface))|15||

[Up](#applicaties-en-informatiestromen)

### IDM2 ministeries (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[IDM2 ministeries (outbound) (Application Interface)](#idm2-ministeries-(outbound)-(application-interface))|14||

[Up](#applicaties-en-informatiestromen)

### LNV (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[LNV (outbound) (Application Interface)](#lnv-(outbound)-(application-interface))|19||

[Up](#applicaties-en-informatiestromen)

### 3W (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[3W (outbound) (Application Interface)](#3w-(outbound)-(application-interface))|27||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[3W (outbound) (Application Interface)](#3w-(outbound)-(application-interface))|25||

[Up](#applicaties-en-informatiestromen)

### Shuttel (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[Shuttel (Application Interface)](#shuttel-(application-interface))|21||

[Up](#applicaties-en-informatiestromen)

### RBO/RSO (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[RBO/RSO (Application Interface)](#rborso-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

## Transactiekanalen (Diagram Model Group)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Flow Relationship|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|||
|[Excel (Application Component)](#excel-(application-component))|Flow Relationship|[SAP GUI (Application Component)](#sap-gui-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Flow Relationship|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Genesys (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Genesys (Application Component)](#genesys-(application-component))|Flow Relationship|[WFM Nice (Application Component)](#wfm-nice-(application-component))|||
|[Genesys (Application Component)](#genesys-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[Genesys (Application Component)](#genesys-(application-component))|Flow Relationship|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|||

[Up](#applicaties-en-informatiestromen)

### E-mail (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[E-mail (Application Component)](#e-mail-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Webbrowser (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Webbrowser (Application Component)](#webbrowser-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### RPA Robotics Blue Prism (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[RPA Robotics Blue Prism (Application Component)](#rpa-robotics-blue-prism-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Kofax (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Kofax (Application Component)](#kofax-(application-component))|Flow Relationship|[Pandora (Application Component)](#pandora-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### P-Direkt app (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[P-Direkt app (Application Component)](#p-direkt-app-(application-component))|Flow Relationship|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand BW (Diagram Model Group)

### J&V (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[J&V (Application Interface)](#j&v-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Rechtspraak (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[Rechtspraak (Application Interface)](#rechtspraak-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Openbaar Min. (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[Openbaar Min. (Application Interface)](#openbaar-min.-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Justitie (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[Justitie (Application Interface)](#justitie-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### 3F (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[3F (Application Interface)](#3f-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand PY (Diagram Model Group)

### Audit bestanden (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Audit bestanden (Application Interface)](#audit-bestanden-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Jaaropgaven (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Jaaropgaven (Application Interface)](#jaaropgaven-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Afschrift 2e betaalmoment (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afschrift 2e betaalmoment (Application Interface)](#afschrift-2e-betaalmoment-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Verwerkings overzicht (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Verwerkings overzicht (Application Interface)](#verwerkings-overzicht-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Afrekenresultaten (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afrekenresultaten (Application Interface)](#afrekenresultaten-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Loonstroken (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Loonstroken (Application Interface)](#loonstroken-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Collectieve afdrachten (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Collectieve afdrachten (Application Interface)](#collectieve-afdrachten-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Afschrift 1e betaalmoment (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afschrift 1e betaalmoment (Application Interface)](#afschrift-1e-betaalmoment-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Werkkosten regeling (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Werkkosten regeling (Application Interface)](#werkkosten-regeling-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Blokkade overzicht (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Blokkade overzicht (Application Interface)](#blokkade-overzicht-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Afschrift 3e betaalmoment (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afschrift 3e betaalmoment (Application Interface)](#afschrift-3e-betaalmoment-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Jaarloon BZT (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Jaarloon BZT (Application Interface)](#jaarloon-bzt-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### PCP (alleen MinFin) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[PCP (alleen MinFin) (Application Interface)](#pcp-(alleen-minfin)-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

## Inkomend HR (Diagram Model Group)

### 3W (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[3W (inbound) (Application Interface)](#3w-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|26||

[Up](#applicaties-en-informatiestromen)

### LNV (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[LNV (inbound) (Application Interface)](#lnv-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|20||

[Up](#applicaties-en-informatiestromen)

### SPX (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SPX (inbound) (Application Interface)](#spx-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Gegevensintegratie ministeries (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gegevensintegratie ministeries (inbound) (Application Interface)](#gegevensintegratie-ministeries-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|10, 11, 12, 13||

[Up](#applicaties-en-informatiestromen)

### IDM2 ministeries (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[IDM2 ministeries (inbound) (Application Interface)](#idm2-ministeries-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|16||

[Up](#applicaties-en-informatiestromen)

### IDM1 ministeries (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[IDM1 ministeries (inbound) (Application Interface)](#idm1-ministeries-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|17||

[Up](#applicaties-en-informatiestromen)

## Tooling (Diagram Model Group)

### ACL (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ACL (Application Component)](#acl-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Query Manager (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Query Manager (Application Component)](#query-manager-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### REO-tool (oud) (Application Component)

MS Access

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[REO-tool (oud) (Application Component)](#reo-tool-(oud)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Pardon (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Pardon (Application Component)](#pardon-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Trello (handmatig) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Trello (handmatig) (Application Component)](#trello-(handmatig)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Jira (handmatig) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))|Flow Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))|Flow Relationship|[REO (Application Component)](#reo-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Kennis-Direkt Tool CC (handmatig) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Kennis-Direkt Tool CC (handmatig) (Application Component)](#kennis-direkt-tool-cc-(handmatig)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Data Sync Manager (clone&test) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Data Sync Manager (clone&test) (Application Component)](#data-sync-manager-(clone&test)-(application-component))|Flow Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Data Sync Manager (clone&test) (Application Component)](#data-sync-manager-(clone&test)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### AND (Application Component)

Routeplanner


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[AND (Application Component)](#and-(application-component))|Flow Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[AND (Application Component)](#and-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Inkomend PY (Diagram Model Group)

### Raad van State (inbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raad van State (inbound) (Application Interface)](#raad-van-state-(inbound)-(application-interface))|Flow Relationship|[SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Flow Relationship|[Pandora (Application Component)](#pandora-(application-component))|||
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Flow Relationship|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|||
|[SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))|Flow Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Data Sync Manager (clone&test) (Application Component)](#data-sync-manager-(clone&test)-(application-component))|Flow Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Documentum (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Documentum (Application Component)](#documentum-(application-component))|Composition Relationship|[Pandora (Application Component)](#pandora-(application-component))|||
|[Documentum (Application Component)](#documentum-(application-component))|Aggregation Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[Documentum (Application Component)](#documentum-(application-component))|Aggregation Relationship|[REO (Application Component)](#reo-(application-component))|||
|[Documentum (Application Component)](#documentum-(application-component))|Composition Relationship|[Workflow (Application Component)](#workflow-(application-component))|||
|[Junction (Junction)](#junction-(junction))|Flow Relationship|[Documentum (Application Component)](#documentum-(application-component))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[Documentum (Application Component)](#documentum-(application-component))|18||

[Up](#applicaties-en-informatiestromen)

### Pandora (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Pandora (Application Component)](#pandora-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Documentum (Application Component)](#documentum-(application-component))|Composition Relationship|[Pandora (Application Component)](#pandora-(application-component))|||
|[Kofax (Application Component)](#kofax-(application-component))|Flow Relationship|[Pandora (Application Component)](#pandora-(application-component))|||
|[CRM (Application Component)](#crm-(application-component))|Flow Relationship|[Pandora (Application Component)](#pandora-(application-component))|||
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Flow Relationship|[Pandora (Application Component)](#pandora-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### InBeeld (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Documentum (Application Component)](#documentum-(application-component))|Aggregation Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[Junction (Junction)](#junction-(junction))|Flow Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[AND (Application Component)](#and-(application-component))|Flow Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))|Flow Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### REO (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Documentum (Application Component)](#documentum-(application-component))|Aggregation Relationship|[REO (Application Component)](#reo-(application-component))|||
|[Junction (Junction)](#junction-(junction))|Flow Relationship|[REO (Application Component)](#reo-(application-component))|||
|[Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))|Flow Relationship|[REO (Application Component)](#reo-(application-component))|||

[Up](#applicaties-en-informatiestromen)

### Workflow (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Documentum (Application Component)](#documentum-(application-component))|Composition Relationship|[Workflow (Application Component)](#workflow-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## CRM (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[CRM (Application Component)](#crm-(application-component))|Flow Relationship|[Pandora (Application Component)](#pandora-(application-component))|||
|[CRM (Application Component)](#crm-(application-component))|Flow Relationship|[Solution Manager (Application Component)](#solution-manager-(application-component))|||
|[CRM (Application Component)](#crm-(application-component))|Flow Relationship|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|||
|[Genesys (Application Component)](#genesys-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[E-mail (Application Component)](#e-mail-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[Webbrowser (Application Component)](#webbrowser-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[RPA Robotics Blue Prism (Application Component)](#rpa-robotics-blue-prism-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[Solution Manager (Application Component)](#solution-manager-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|03||

[Up](#applicaties-en-informatiestromen)

## WFM Nice (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Genesys (Application Component)](#genesys-(application-component))|Flow Relationship|[WFM Nice (Application Component)](#wfm-nice-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Solution Manager (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Solution Manager (Application Component)](#solution-manager-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|||
|[Solution Manager (Application Component)](#solution-manager-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[CRM (Application Component)](#crm-(application-component))|Flow Relationship|[Solution Manager (Application Component)](#solution-manager-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Excel (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Excel (Application Component)](#excel-(application-component))|Flow Relationship|[SAP GUI (Application Component)](#sap-gui-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Flow Relationship|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|||
|[P-Direkt app (Application Component)](#p-direkt-app-(application-component))|Flow Relationship|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## SAP HR transactiekanalen (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Flow Relationship|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Flow Relationship|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Flow Relationship|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|||

[Up](#applicaties-en-informatiestromen)

## PI (outbound) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|Flow Relationship|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|||
|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|Flow Relationship|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|||
|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|Flow Relationship|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand HR (Diagram Model Group) 2

### Jaartotaalbestand ministeries (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[Jaartotaalbestand ministeries (Application Interface)](#jaartotaalbestand-ministeries-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### DUO (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[DUO (Application Interface)](#duo-(application-interface))|05||

[Up](#applicaties-en-informatiestromen)

### Roosterdump EZ (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[Roosterdump EZ (Application Interface)](#roosterdump-ez-(application-interface))|22||

[Up](#applicaties-en-informatiestromen)

### SZW legacy (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[SZW legacy (Application Interface)](#szw-legacy-(application-interface))|24||

[Up](#applicaties-en-informatiestromen)

## Uitgaand PY (Diagram Model Group) 2

### BZK SMTP (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[BZK SMTP (Application Interface)](#bzk-smtp-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### RDW (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[RDW (Application Interface)](#rdw-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Raad van State (outbound) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[Raad van State (outbound) (Application Interface)](#raad-van-state-(outbound)-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### RBS batch betaling (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[RBS batch betaling (Application Interface)](#rbs-batch-betaling-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Printstraat Belastingdienst (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[Printstraat Belastingdienst (Application Interface)](#printstraat-belastingdienst-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### Fiscus Loonaangifte (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[Fiscus Loonaangifte (Application Interface)](#fiscus-loonaangifte-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

### APG pensioen (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[APG pensioen (Application Interface)](#apg-pensioen-(application-interface))|||

[Up](#applicaties-en-informatiestromen)

## QlicView (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[BW (Application Component)](#bw-(application-component))|Flow Relationship|[QlicView (Application Component)](#qlicview-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## BW (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[BW (Application Component)](#bw-(application-component))|Flow Relationship|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|||
|[BW (Application Component)](#bw-(application-component))|Flow Relationship|[QlicView (Application Component)](#qlicview-(application-component))|||
|[BW (Application Component)](#bw-(application-component))|Flow Relationship|[Jopi (Application Component)](#jopi-(application-component))|||
|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|Flow Relationship|[BW (Application Component)](#bw-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Jopi (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[BW (Application Component)](#bw-(application-component))|Flow Relationship|[Jopi (Application Component)](#jopi-(application-component))|||
|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|Flow Relationship|[Jopi (Application Component)](#jopi-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## SBI (GIS) (outbound) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|Flow Relationship|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|||
|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|Flow Relationship|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|||
|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|02||
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Flow Relationship|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## SBI (GIS) (inbound) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))|Flow Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Raad van State (inbound) (Application Interface)](#raad-van-state-(inbound)-(application-interface))|Flow Relationship|[SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))|01||

[Up](#applicaties-en-informatiestromen)

## Inkomend Jopi (Diagram Model Group)

### ABP (Etniciteit) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ABP (Etniciteit) (Application Interface)](#abp-(etniciteit)-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||

[Up](#applicaties-en-informatiestromen)

### 1e/2e kamer personeelsbestand (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[1e/2e kamer personeelsbestand (Application Interface)](#1e2e-kamer-personeelsbestand-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Ministerie van BZK (Enquetes) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Ministerie van BZK (Enquetes) (Application Interface)](#ministerie-van-bzk-(enquetes)-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Mobiliteitsbank (BOSS, Tangram, Vacatures) (Application Interface)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobiliteitsbank (BOSS, Tangram, Vacatures) (Application Interface)](#mobiliteitsbank-(boss,-tangram,-vacatures)-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Tooling (Diagram Model Group) 2

### PivotalTracker (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[PivotalTracker (Application Component)](#pivotaltracker-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Reveille, monitoring (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Reveille, monitoring (Application Component)](#reveille,-monitoring-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Migration Center (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Migration Center (Application Component)](#migration-center-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

### Document Generator-MDPT (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Document Generator-MDPT (Application Component)](#document-generator-mdpt-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||
|[Document Generator-MDPT (Application Component)](#document-generator-mdpt-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

### MyInsight (toekomstig) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[MyInsight (toekomstig) (Application Component)](#myinsight-(toekomstig)-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||
|[MyInsight (toekomstig) (Application Component)](#myinsight-(toekomstig)-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand BW (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[J&V (Application Interface)](#j&v-(application-interface))|||
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[Rechtspraak (Application Interface)](#rechtspraak-(application-interface))|||
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[Openbaar Min. (Application Interface)](#openbaar-min.-(application-interface))|||
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[Justitie (Application Interface)](#justitie-(application-interface))|||
|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|Flow Relationship|[3F (Application Interface)](#3f-(application-interface))|||
|[BW (Application Component)](#bw-(application-component))|Flow Relationship|[Uitgaand BW (Junction)](#uitgaand-bw-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand SAP PY (PI) (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Collectieve afdrachten (Application Interface)](#collectieve-afdrachten-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afrekenresultaten (Application Interface)](#afrekenresultaten-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Jaaropgaven (Application Interface)](#jaaropgaven-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Loonstroken (Application Interface)](#loonstroken-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Verwerkings overzicht (Application Interface)](#verwerkings-overzicht-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Blokkade overzicht (Application Interface)](#blokkade-overzicht-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[PCP (alleen MinFin) (Application Interface)](#pcp-(alleen-minfin)-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afschrift 1e betaalmoment (Application Interface)](#afschrift-1e-betaalmoment-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afschrift 2e betaalmoment (Application Interface)](#afschrift-2e-betaalmoment-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Afschrift 3e betaalmoment (Application Interface)](#afschrift-3e-betaalmoment-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Jaarloon BZT (Application Interface)](#jaarloon-bzt-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Audit bestanden (Application Interface)](#audit-bestanden-(application-interface))|||
|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|Flow Relationship|[Werkkosten regeling (Application Interface)](#werkkosten-regeling-(application-interface))|||
|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|Flow Relationship|[Uitgaand SAP PY (PI) (Junction)](#uitgaand-sap-py-(pi)-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand SAP HR (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[Jaartotaalbestand ministeries (Application Interface)](#jaartotaalbestand-ministeries-(application-interface))|||
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[DUO (Application Interface)](#duo-(application-interface))|05||
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[Roosterdump EZ (Application Interface)](#roosterdump-ez-(application-interface))|22||
|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|Flow Relationship|[SZW legacy (Application Interface)](#szw-legacy-(application-interface))|24||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand SAP PY (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[RBS batch betaling (Application Interface)](#rbs-batch-betaling-(application-interface))|||
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[Raad van State (outbound) (Application Interface)](#raad-van-state-(outbound)-(application-interface))|||
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[RDW (Application Interface)](#rdw-(application-interface))|||
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[BZK SMTP (Application Interface)](#bzk-smtp-(application-interface))|||
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[Printstraat Belastingdienst (Application Interface)](#printstraat-belastingdienst-(application-interface))|||
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[Fiscus Loonaangifte (Application Interface)](#fiscus-loonaangifte-(application-interface))|||
|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|Flow Relationship|[APG pensioen (Application Interface)](#apg-pensioen-(application-interface))|||
|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|Flow Relationship|[Uitgaand SAP PY (Junction)](#uitgaand-sap-py-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Uitgaand SAP HR (PI) (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[RBO/RSO (Application Interface)](#rborso-(application-interface))|||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[Shuttel (Application Interface)](#shuttel-(application-interface))|21||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[3W (outbound) (Application Interface)](#3w-(outbound)-(application-interface))|27||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[LNV (outbound) (Application Interface)](#lnv-(outbound)-(application-interface))|19||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[IDM2 ministeries (outbound) (Application Interface)](#idm2-ministeries-(outbound)-(application-interface))|14||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[IDM1 ministeries (outbound) (Application Interface)](#idm1-ministeries-(outbound)-(application-interface))|15||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[UWV (outbound) (Application Interface)](#uwv-(outbound)-(application-interface))|||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[ARBO (Application Interface)](#arbo-(application-interface))|04||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[SPX (outbound) (Application Interface)](#spx-(outbound)-(application-interface))|23||
|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|Flow Relationship|[Gegevensintegratie ministeries (outbound) (Application Interface)](#gegevensintegratie-ministeries-(outbound)-(application-interface))|06, 07, 08, 09||
|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|Flow Relationship|[Uitgaand SAP HR (PI) (Junction)](#uitgaand-sap-hr-(pi)-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Inkomend Jopi (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|Flow Relationship|[Jopi (Application Component)](#jopi-(application-component))|||
|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||
|[1e/2e kamer personeelsbestand (Application Interface)](#1e2e-kamer-personeelsbestand-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||
|[Ministerie van BZK (Enquetes) (Application Interface)](#ministerie-van-bzk-(enquetes)-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||
|[Mobiliteitsbank (BOSS, Tangram, Vacatures) (Application Interface)](#mobiliteitsbank-(boss,-tangram,-vacatures)-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||
|[ABP (Etniciteit) (Application Interface)](#abp-(etniciteit)-(application-interface))|Flow Relationship|[Inkomend Jopi (Junction)](#inkomend-jopi-(junction))|||

[Up](#applicaties-en-informatiestromen)

## PI (inbound) (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[PI (inbound) (Application Component)](#pi-(inbound)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|Flow Relationship|[PI (inbound) (Application Component)](#pi-(inbound)-(application-component))|||

[Up](#applicaties-en-informatiestromen)

## Inbound SAP HR (PI) (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|Flow Relationship|[PI (inbound) (Application Component)](#pi-(inbound)-(application-component))|||
|[LNV (inbound) (Application Interface)](#lnv-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|20||
|[SPX (inbound) (Application Interface)](#spx-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|||
|[Gegevensintegratie ministeries (inbound) (Application Interface)](#gegevensintegratie-ministeries-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|10, 11, 12, 13||
|[IDM2 ministeries (inbound) (Application Interface)](#idm2-ministeries-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|16||
|[IDM1 ministeries (inbound) (Application Interface)](#idm1-ministeries-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|17||
|[3W (inbound) (Application Interface)](#3w-(inbound)-(application-interface))|Flow Relationship|[Inbound SAP HR (PI) (Junction)](#inbound-sap-hr-(pi)-(junction))|26||

[Up](#applicaties-en-informatiestromen)

## Junction (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Junction (Junction)](#junction-(junction))|Flow Relationship|[InBeeld (Application Component)](#inbeeld-(application-component))|||
|[Document Generator-MDPT (Application Component)](#document-generator-mdpt-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||
|[MyInsight (toekomstig) (Application Component)](#myinsight-(toekomstig)-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Junction (Junction) 2

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Junction (Junction)](#junction-(junction))|Flow Relationship|[REO (Application Component)](#reo-(application-component))|||
|[MyInsight (toekomstig) (Application Component)](#myinsight-(toekomstig)-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||
|[Document Generator-MDPT (Application Component)](#document-generator-mdpt-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

## Junction (Junction) 3

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Junction (Junction)](#junction-(junction))|Flow Relationship|[Documentum (Application Component)](#documentum-(application-component))|||
|[PivotalTracker (Application Component)](#pivotaltracker-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||
|[Reveille, monitoring (Application Component)](#reveille,-monitoring-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||
|[Migration Center (Application Component)](#migration-center-(application-component))|Flow Relationship|[Junction (Junction)](#junction-(junction))|||

[Up](#applicaties-en-informatiestromen)

## BW (inbound) (Junction)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|Flow Relationship|[BW (Application Component)](#bw-(application-component))|||
|[CRM (Application Component)](#crm-(application-component))|Flow Relationship|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|||
|[Genesys (Application Component)](#genesys-(application-component))|Flow Relationship|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|||

[Up](#applicaties-en-informatiestromen)

## SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[Documentum (Application Component)](#documentum-(application-component))|18||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[CRM (Application Component)](#crm-(application-component))|03||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[BW (inbound) (Junction)](#bw-(inbound)-(junction))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[PI (outbound) (Application Component)](#pi-(outbound)-(application-component))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[3W (outbound) (Application Interface)](#3w-(outbound)-(application-interface))|25||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[Uitgaand SAP HR (Junction)](#uitgaand-sap-hr-(junction))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Flow Relationship|[SBI (GIS) (inbound) (Application Component)](#sbi-(gis)-(inbound)-(application-component))|01||
|[PI (inbound) (Application Component)](#pi-(inbound)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Solution Manager (Application Component)](#solution-manager-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HR transactiekanalen (Junction)](#sap-hr-transactiekanalen-(junction))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SBI (GIS) (outbound) (Application Component)](#sbi-(gis)-(outbound)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|02||
|[AND (Application Component)](#and-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Data Sync Manager (clone&test) (Application Component)](#data-sync-manager-(clone&test)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Kennis-Direkt Tool CC (handmatig) (Application Component)](#kennis-direkt-tool-cc-(handmatig)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Jira (handmatig) (Application Component)](#jira-(handmatig)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Trello (handmatig) (Application Component)](#trello-(handmatig)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Pardon (Application Component)](#pardon-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[REO-tool (oud) (Application Component)](#reo-tool-(oud)-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Query Manager (Application Component)](#query-manager-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[ACL (Application Component)](#acl-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Pandora (Application Component)](#pandora-(application-component))|Flow Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#applicaties-en-informatiestromen)

[embedView]: img-Applicaties-en-informatiestromen.png
Generated: Fri Jan 31 2020 10:28:50 GMT+0100 (CET)
