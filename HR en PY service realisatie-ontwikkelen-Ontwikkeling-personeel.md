# (ontwikkelen) Ontwikkeling personeel

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))
  * [Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))
  * [HRO (Business Role)](#hro-(business-role))
  * [Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))
  * [Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))
  * [Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))
  * [Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))
  * [Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))
  * [Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))
  * [Registreren P-Schouw (Business Process)](#registreren-p-schouw-(business-process))
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
  * [Registratie personeelsgesprekken (Application Function)](#registratie-personeelsgesprekken-(application-function))
  * [Verslaglegging personeelsgesprek (Application Service)](#verslaglegging-personeelsgesprek-(application-service))
  * [Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))
  * [Rapportage HRO personeelsgesprekken (Application Service)](#rapportage-hro-personeelsgesprekken-(application-service))
  * [Rapportage manager personeelsgesprekken (Application Service)](#rapportage-manager-personeelsgesprekken-(application-service))
  * [Registreren beoordelingsdatum (Application Service)](#registreren-beoordelingsdatum-(application-service))
  * [Registratie beoordelingsdatum (Application Function)](#registratie-beoordelingsdatum-(application-function))
  * [Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))
  * [Wijziging studiefaciliteit (Application Service)](#wijziging-studiefaciliteit-(application-service))
  * [Afrekenen studiefaciliteit (Application Service)](#afrekenen-studiefaciliteit-(application-service))
  * [Registratie opleidingen (Application Function)](#registratie-opleidingen-(application-function))
  * [Registreren afgeronde opleiding (Application Service)](#registreren-afgeronde-opleiding-(application-service))

## Introduction

![(ontwikkelen) Ontwikkeling personeel][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registreren personeelsgesprek (Business Process)

Zowel manager als medewerker moeten akkoord geven op functioneringsgesprek.
Geldt niet voor beoordelingsgesprek

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[Verslaglegging personeelsgesprek (Application Service)](#verslaglegging-personeelsgesprek-(application-service))|Serving Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Ontwikkelen personeel (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Registreren P-Schouw (Business Process)](#registreren-p-schouw-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Aanvragen rapportage HRO personeelsgesprekken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|||
|[Rapportage HRO personeelsgesprekken (Application Service)](#rapportage-hro-personeelsgesprekken-(application-service))|Serving Relationship|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Aanvragen rapportage manager personeelsgesprekken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|||
|[Rapportage manager personeelsgesprekken (Application Service)](#rapportage-manager-personeelsgesprekken-(application-service))|Serving Relationship|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registreren beoordelingsdatum (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|||
|[Registreren beoordelingsdatum (Application Service)](#registreren-beoordelingsdatum-(application-service))|Serving Relationship|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Aanvragen/wijzigen studiefaciliteit (Business Process)

Kan ook voorschot krijgen

Kan hier ook meteen opleiding registreren

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Triggering Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||
|[Wijziging studiefaciliteit (Application Service)](#wijziging-studiefaciliteit-(application-service))|Serving Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Afrekenen studiefaciliteit (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||
|[Afrekenen studiefaciliteit (Application Service)](#afrekenen-studiefaciliteit-(application-service))|Serving Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Triggering Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registreren afgeronde opleiding (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Registreren afgeronde opleiding (Application Service)](#registreren-afgeronde-opleiding-(application-service))|Serving Relationship|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registreren P-Schouw (Business Process)

Managerstool -&gt; input voor p-gesprekken. Puur registratie, geen koppeling.
Huidige oplossing maatwerk

Komt niet in P-dossier

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren P-Schouw (Business Process)](#registreren-p-schouw-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgesprekken (Application Function)](#registratie-personeelsgesprekken-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie beoordelingsdatum (Application Function)](#registratie-beoordelingsdatum-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie opleidingen (Application Function)](#registratie-opleidingen-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registratie personeelsgesprekken (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie personeelsgesprekken (Application Function)](#registratie-personeelsgesprekken-(application-function))|Realization Relationship|[Verslaglegging personeelsgesprek (Application Service)](#verslaglegging-personeelsgesprek-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie personeelsgesprekken (Application Function)](#registratie-personeelsgesprekken-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Verslaglegging personeelsgesprek (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verslaglegging personeelsgesprek (Application Service)](#verslaglegging-personeelsgesprek-(application-service))|Serving Relationship|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|||
|[Registratie personeelsgesprekken (Application Function)](#registratie-personeelsgesprekken-(application-function))|Realization Relationship|[Verslaglegging personeelsgesprek (Application Service)](#verslaglegging-personeelsgesprek-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Genereren rapportage personeelsgesprekken (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))|Realization Relationship|[Rapportage HRO personeelsgesprekken (Application Service)](#rapportage-hro-personeelsgesprekken-(application-service))|||
|[Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))|Realization Relationship|[Rapportage manager personeelsgesprekken (Application Service)](#rapportage-manager-personeelsgesprekken-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Rapportage HRO personeelsgesprekken (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Rapportage HRO personeelsgesprekken (Application Service)](#rapportage-hro-personeelsgesprekken-(application-service))|Serving Relationship|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|||
|[Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))|Realization Relationship|[Rapportage HRO personeelsgesprekken (Application Service)](#rapportage-hro-personeelsgesprekken-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Rapportage manager personeelsgesprekken (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Rapportage manager personeelsgesprekken (Application Service)](#rapportage-manager-personeelsgesprekken-(application-service))|Serving Relationship|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|||
|[Genereren rapportage personeelsgesprekken (Application Function)](#genereren-rapportage-personeelsgesprekken-(application-function))|Realization Relationship|[Rapportage manager personeelsgesprekken (Application Service)](#rapportage-manager-personeelsgesprekken-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registreren beoordelingsdatum (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren beoordelingsdatum (Application Service)](#registreren-beoordelingsdatum-(application-service))|Serving Relationship|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|||
|[Registratie beoordelingsdatum (Application Function)](#registratie-beoordelingsdatum-(application-function))|Realization Relationship|[Registreren beoordelingsdatum (Application Service)](#registreren-beoordelingsdatum-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registratie beoordelingsdatum (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie beoordelingsdatum (Application Function)](#registratie-beoordelingsdatum-(application-function))|Realization Relationship|[Registreren beoordelingsdatum (Application Service)](#registreren-beoordelingsdatum-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie beoordelingsdatum (Application Function)](#registratie-beoordelingsdatum-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registratie studiefaciliteiten (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))|Realization Relationship|[Wijziging studiefaciliteit (Application Service)](#wijziging-studiefaciliteit-(application-service))|||
|[Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))|Realization Relationship|[Afrekenen studiefaciliteit (Application Service)](#afrekenen-studiefaciliteit-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Wijziging studiefaciliteit (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijziging studiefaciliteit (Application Service)](#wijziging-studiefaciliteit-(application-service))|Serving Relationship|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|||
|[Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))|Realization Relationship|[Wijziging studiefaciliteit (Application Service)](#wijziging-studiefaciliteit-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Afrekenen studiefaciliteit (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen studiefaciliteit (Application Service)](#afrekenen-studiefaciliteit-(application-service))|Serving Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||
|[Registratie studiefaciliteiten (Application Function)](#registratie-studiefaciliteiten-(application-function))|Realization Relationship|[Afrekenen studiefaciliteit (Application Service)](#afrekenen-studiefaciliteit-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registratie opleidingen (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie opleidingen (Application Function)](#registratie-opleidingen-(application-function))|Realization Relationship|[Registreren afgeronde opleiding (Application Service)](#registreren-afgeronde-opleiding-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie opleidingen (Application Function)](#registratie-opleidingen-(application-function))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

### Registreren afgeronde opleiding (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren afgeronde opleiding (Application Service)](#registreren-afgeronde-opleiding-(application-service))|Serving Relationship|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|||
|[Registratie opleidingen (Application Function)](#registratie-opleidingen-(application-function))|Realization Relationship|[Registreren afgeronde opleiding (Application Service)](#registreren-afgeronde-opleiding-(application-service))|||

[Up](#(ontwikkelen)-ontwikkeling-personeel)

[embedView]: img-HR en PY service realisatie-ontwikkelen-Ontwikkeling-personeel.png
Generated: Fri Jan 31 2020 10:28:42 GMT+0100 (CET)
