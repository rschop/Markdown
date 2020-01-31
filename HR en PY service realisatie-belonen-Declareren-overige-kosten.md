# (belonen) Declareren overige kosten

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [HRO (Business Role)](#hro-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))
  * [?? Commissie-, advies- of zittingsgelden (Business Process)](#??-commissie-,-advies--of-zittingsgelden-(business-process))
  * [Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))
  * [Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))
  * [?? Toelage bezwarende omstandigheden (Business Process)](#??-toelage-bezwarende-omstandigheden-(business-process))
  * [Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))
  * [Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))
  * [Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))
  * [Medewerker (Business Role)](#medewerker-(business-role))
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
  * [Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))
  * [Declareren overige kosten (Application Service)](#declareren-overige-kosten-(application-service))
  * [Mobile Platform (Application Component)](#mobile-platform-(application-component))
  * [Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))
  * [Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))
  * [Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))
  * [Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))
  * [Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))
  * [Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))
  * [Registreren werktijden (Application Service)](#registreren-werktijden-(application-service))
  * [Declareren werktijdverschuiving (Application Service)](#declareren-werktijdverschuiving-(application-service))

## Introduction

![(belonen) Declareren overige kosten][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-declareren-overige-kosten)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[?? Commissie-, advies- of zittingsgelden (Business Process)](#??-commissie-,-advies--of-zittingsgelden-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[?? Commissie-, advies- of zittingsgelden (Business Process)](#??-commissie-,-advies--of-zittingsgelden-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren overige kosten (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[Declareren overige kosten (Application Service)](#declareren-overige-kosten-(application-service))|Serving Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### ?? Commissie-, advies- of zittingsgelden (Business Process)

Van Kennis-Direct tool:

Dit is een overzicht van alle declaraties/aanvragen

Medewerker: P-Direktportaal &gt; Home &gt; Reizen &gt; Concept/ingediende reisaanvragen en declaraties

Uitbetaling Vz. referendumcommissie

Deze commissie is in 2015 ingesteld. De vergoeding die de leden krijgen, wordt sinds de start onder vacatiegelden uitbetaald. Dat is intern bij BZK goed afgestemd en juist bevonden.

De bedoeling is dat betrokkene als declarant wordt ingevoerd Medewerkergroep 52 is dat en dus geen ambtelijk personeel (NAPM)
Vervolgens kunnen de declaraties dan ingediend worden onder Looncomponent 0431 en dat is vacatiegeld.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[?? Commissie-, advies- of zittingsgelden (Business Process)](#??-commissie-,-advies--of-zittingsgelden-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[?? Commissie-, advies- of zittingsgelden (Business Process)](#??-commissie-,-advies--of-zittingsgelden-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|||
|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))|Serving Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Registreren overwerk (Business Process)

Aanvragen/intrekken/wijzigen. CC vat alles onder de noemer overwerk

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||
|[Registreren werktijden (Application Service)](#registreren-werktijden-(application-service))|Serving Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### ?? Toelage bezwarende omstandigheden (Business Process)

### Declareren onregelmatige dienst (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|||
|[Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))|Serving Relationship|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Beoordelen declaratie in behandeling (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))|Serving Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren werktijdverschuiving (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|Triggering Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|||
|[Declareren werktijdverschuiving (Application Service)](#declareren-werktijdverschuiving-(application-service))|Serving Relationship|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|||

[Up](#(belonen)-declareren-overige-kosten)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-declareren-overige-kosten)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-declareren-overige-kosten)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-declareren-overige-kosten)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-declareren-overige-kosten)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Registratie overige kosten (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|Realization Relationship|[Declareren overige kosten (Application Service)](#declareren-overige-kosten-(application-service))|||
|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|Realization Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))|||
|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|Realization Relationship|[Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren overige kosten (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren overige kosten (Application Service)](#declareren-overige-kosten-(application-service))|Serving Relationship|[Declareren overige kosten (Business Process)](#declareren-overige-kosten-(business-process))|||
|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|Realization Relationship|[Declareren overige kosten (Application Service)](#declareren-overige-kosten-(application-service))|||

[Up](#(belonen)-declareren-overige-kosten)

### Mobile Platform (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Autoriseren mutaties App (generiek) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|Realization Relationship|[Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))|||
|[Mobile Platform (Application Component)](#mobile-platform-(application-component))|Assignment Relationship|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Autoriseren mutaties Portaal (generiek) (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|Realization Relationship|[Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Beoordelen declaratie (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))|Serving Relationship|[Beoordelen declaratie in behandeling (Business Process)](#beoordelen-declaratie-in-behandeling-(business-process))|||
|[Autoriseren mutaties App (generiek) (Application Function)](#autoriseren-mutaties-app-(generiek)-(application-function))|Realization Relationship|[Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))|||
|[Autoriseren mutaties Portaal (generiek) (Application Function)](#autoriseren-mutaties-portaal-(generiek)-(application-function))|Realization Relationship|[Beoordelen declaratie (Application Service)](#beoordelen-declaratie-(application-service))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))|Serving Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Business Process)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(business-process))|||
|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|Realization Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren onregelmatige dienst (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))|Serving Relationship|[Declareren onregelmatige dienst (Business Process)](#declareren-onregelmatige-dienst-(business-process))|||
|[Registratie overige kosten (Application Function)](#registratie-overige-kosten-(application-function))|Realization Relationship|[Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))|||

[Up](#(belonen)-declareren-overige-kosten)

### Registratie werktijden (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Declareren bereikbaarheids- en beschikbaarheidsdienst (Application Service)](#declareren-bereikbaarheids--en-beschikbaarheidsdienst-(application-service))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Declareren onregelmatige dienst (Application Service)](#declareren-onregelmatige-dienst-(application-service))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Registreren werktijden (Application Service)](#registreren-werktijden-(application-service))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Declareren werktijdverschuiving (Application Service)](#declareren-werktijdverschuiving-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|||

[Up](#(belonen)-declareren-overige-kosten)

### Registreren werktijden (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren werktijden (Application Service)](#registreren-werktijden-(application-service))|Serving Relationship|[Registreren overwerk (Business Process)](#registreren-overwerk-(business-process))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Registreren werktijden (Application Service)](#registreren-werktijden-(application-service))|||

[Up](#(belonen)-declareren-overige-kosten)

### Declareren werktijdverschuiving (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren werktijdverschuiving (Application Service)](#declareren-werktijdverschuiving-(application-service))|Serving Relationship|[Declareren werktijdverschuiving (Business Process)](#declareren-werktijdverschuiving-(business-process))|||
|[Registratie werktijden (Application Function)](#registratie-werktijden-(application-function))|Realization Relationship|[Declareren werktijdverschuiving (Application Service)](#declareren-werktijdverschuiving-(application-service))|||

[Up](#(belonen)-declareren-overige-kosten)

[embedView]: img-HR en PY service realisatie-belonen-Declareren-overige-kosten.png
Generated: Fri Jan 31 2020 10:28:38 GMT+0100 (CET)
