# (P&O) Personeelskaart en p-dossier

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))
  * [Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))
  * [Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))
  * [Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))
  * [Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))
  * [Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))
  * [Manager (Business Role)](#manager-(business-role))
  * [Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))
  * [HRO (Business Role)](#hro-(business-role))
  * [Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))
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
  * [Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))
  * [Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))
  * [Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))
  * [Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))
  * [Registratie nevenwerkzaamheden (Application Function)](#registratie-nevenwerkzaamheden-(application-function))
  * [Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))
  * [Registratie kindgegevens (Application Function)](#registratie-kindgegevens-(application-function))
  * [Registreren kind (Application Service)](#registreren-kind-(application-service))
  * [Registratie ambtsjubileum (Application Function)](#registratie-ambtsjubileum-(application-function))
  * [Registreren ambtsjubileum (Application Service)](#registreren-ambtsjubileum-(application-service))

## Introduction

![(P&O) Personeelskaart en p-dossier][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Wijzigen basis personeelsgegevens (Business Process)

Omvat:
- Aanschrijfnaam wijzigen
- Adres- en telefoongegevens
- Noodcontact
- Zakelijke contactgegevens
- Wijzigen betaalgegevens

Moet ook buitenlands (post)adres ondersteunen (is nu handmatig ivm routeplanner)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|||
|[Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))|Serving Relationship|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registreren kindgegevens (Business Process)

Verplicht voor BuZa voor alle medewerkers

Binnen proces aanvragen ouderschapsverlof ingebouwd.
Verplicht voor overige medewerkers ten behoeve van ouderschapsverlof, adoptieverlof en pleegverlof.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|||
|[Registreren kind (Application Service)](#registreren-kind-(application-service))|Serving Relationship|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Raadplegen personeelskaart(en) (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|||
|[Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))|Serving Relationship|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Raadplegen personeelsdossier(s) (Business Process)

Zit in documentum

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|Serving Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Beheersing personeel en organisatie (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registreren nevenwerkzaamheden (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))|Serving Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)

(maatwerk + maatwerk infotype)


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))|Serving Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Toevoegen item personeelsdossier (Business Process)

Komt uit verschillende bronnen/processen
Documenten van besluiten in portaal worden automatisch gegenereerd.
Documentum

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|||
|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|Serving Relationship|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Wijzigen berekeningsdatum ambtsjubileum (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|Realization Relationship|[Beheersing personeel en organisatie (Business Service)](#beheersing-personeel-en-organisatie-(business-service))|||
|[Registreren ambtsjubileum (Application Service)](#registreren-ambtsjubileum-(application-service))|Serving Relationship|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie nevenwerkzaamheden (Application Function)](#registratie-nevenwerkzaamheden-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie kindgegevens (Application Function)](#registratie-kindgegevens-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie ambtsjubileum (Application Function)](#registratie-ambtsjubileum-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registratie personeelsgegevens (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|Realization Relationship|[Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registratie personeelsdossier (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|Realization Relationship|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Bewerken personeelsdossier (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|Serving Relationship|[Raadplegen personeelsdossier(s) (Business Process)](#raadplegen-personeelsdossier(s)-(business-process))|||
|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|Serving Relationship|[Toevoegen item personeelsdossier (Business Process)](#toevoegen-item-personeelsdossier-(business-process))|||
|[Registratie personeelsdossier (Application Function)](#registratie-personeelsdossier-(application-function))|Realization Relationship|[Bewerken personeelsdossier (Application Service)](#bewerken-personeelsdossier-(application-service))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Bewerken personeelsgegevens (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))|Serving Relationship|[Wijzigen basis personeelsgegevens (Business Process)](#wijzigen-basis-personeelsgegevens-(business-process))|||
|[Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))|Serving Relationship|[Raadplegen personeelskaart(en) (Business Process)](#raadplegen-personeelskaart(en)-(business-process))|||
|[Registratie personeelsgegevens (Application Function)](#registratie-personeelsgegevens-(application-function))|Realization Relationship|[Bewerken personeelsgegevens (Application Service)](#bewerken-personeelsgegevens-(application-service))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registratie nevenwerkzaamheden (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie nevenwerkzaamheden (Application Function)](#registratie-nevenwerkzaamheden-(application-function))|Realization Relationship|[Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie nevenwerkzaamheden (Application Function)](#registratie-nevenwerkzaamheden-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Bewerken nevenwerkzaamheden (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))|Serving Relationship|[Registreren nevenwerkzaamheden (Business Process)](#registreren-nevenwerkzaamheden-(business-process))|||
|[Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))|Serving Relationship|[Registreren nevenwerkzaamheden rechterlijke ambtenaar (Business Process)](#registreren-nevenwerkzaamheden-rechterlijke-ambtenaar-(business-process))|||
|[Registratie nevenwerkzaamheden (Application Function)](#registratie-nevenwerkzaamheden-(application-function))|Realization Relationship|[Bewerken nevenwerkzaamheden (Application Service)](#bewerken-nevenwerkzaamheden-(application-service))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registratie kindgegevens (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie kindgegevens (Application Function)](#registratie-kindgegevens-(application-function))|Realization Relationship|[Registreren kind (Application Service)](#registreren-kind-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie kindgegevens (Application Function)](#registratie-kindgegevens-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registreren kind (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren kind (Application Service)](#registreren-kind-(application-service))|Serving Relationship|[Registreren kindgegevens (Business Process)](#registreren-kindgegevens-(business-process))|||
|[Registratie kindgegevens (Application Function)](#registratie-kindgegevens-(application-function))|Realization Relationship|[Registreren kind (Application Service)](#registreren-kind-(application-service))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registratie ambtsjubileum (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie ambtsjubileum (Application Function)](#registratie-ambtsjubileum-(application-function))|Realization Relationship|[Registreren ambtsjubileum (Application Service)](#registreren-ambtsjubileum-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie ambtsjubileum (Application Function)](#registratie-ambtsjubileum-(application-function))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

### Registreren ambtsjubileum (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren ambtsjubileum (Application Service)](#registreren-ambtsjubileum-(application-service))|Serving Relationship|[Wijzigen berekeningsdatum ambtsjubileum (Business Process)](#wijzigen-berekeningsdatum-ambtsjubileum-(business-process))|||
|[Registratie ambtsjubileum (Application Function)](#registratie-ambtsjubileum-(application-function))|Realization Relationship|[Registreren ambtsjubileum (Application Service)](#registreren-ambtsjubileum-(application-service))|||

[Up](#(p&o)-personeelskaart-en-p-dossier)

[embedView]: img-HR en PY service realisatie-P&O-Personeelskaart-en-p-dossier.png
Generated: Fri Jan 31 2020 10:28:41 GMT+0100 (CET)
