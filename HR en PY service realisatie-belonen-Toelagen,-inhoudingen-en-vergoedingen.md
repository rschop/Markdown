# (belonen) Toelagen, inhoudingen en vergoedingen

* [Introduction](#introduction)
* [Business (Diagram Model Group)](#business-(diagram-model-group))
  * [Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))
  * [Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))
  * [Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))
  * [Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))
  * [Dienstwoningen (Business Process)](#dienstwoningen-(business-process))
  * [Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))
  * [Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))
  * [Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))
  * [?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))
  * [BHV toelage (Business Process)](#bhv-toelage-(business-process))
  * [?? Auto van de zaak ministers/staatssecretatissen (Business Process)](#??-auto-van-de-zaak-ministersstaatssecretatissen-(business-process))
  * [Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))
  * [Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))
  * [Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))
  * [Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))
  * [Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))
  * [HRS (Business Role)](#hrs-(business-role))
  * [Medewerker (Business Role)](#medewerker-(business-role))
  * [Manager (Business Role)](#manager-(business-role))
  * [HRO (Business Role)](#hro-(business-role))
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
  * [Registreren dienstauto (Application Service)](#registreren-dienstauto-(application-service))
  * [Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))
  * [Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))
  * [Beëindigen dienstauto (Application Service)](#beëindigen-dienstauto-(application-service))
  * [Registratie BHV (Application Function)](#registratie-bhv-(application-function))
  * [Registreren BHV (Application Service)](#registreren-bhv-(application-service))
  * [Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))
  * [Aanvragen verhuiskostenvergoeding (Application Service)](#aanvragen-verhuiskostenvergoeding-(application-service))
  * [Declareren verhuiskosten (Application Service)](#declareren-verhuiskosten-(application-service))
  * [Registratie dienstwoningen (Application Function)](#registratie-dienstwoningen-(application-function))
  * [Bewerken dienstwoning (Application Service)](#bewerken-dienstwoning-(application-service))
  * [Registratie schadevergoeding (Application Function)](#registratie-schadevergoeding-(application-function))
  * [Registreren schadevergoeding (Application Service)](#registreren-schadevergoeding-(application-service))
  * [Registratie telewerken (Application Function)](#registratie-telewerken-(application-function))
  * [Toekennen/beëindigen telewerken (Application Service)](#toekennenbeëindigen-telewerken-(application-service))
  * [Verhalen schade op medewerker (Application Service)](#verhalen-schade-op-medewerker-(application-service))
  * [Registratie schade (Application Function)](#registratie-schade-(application-function))
  * [Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))
  * [Registratie toe(s)lagen (Application Function)](#registratie-toe(s)lagen-(application-function))

## Introduction

![(belonen) Toelagen, inhoudingen en vergoedingen][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Business (Diagram Model Group)

### Belonen en vergoeden (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Dienstwoningen (Business Process)](#dienstwoningen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Toe(s)lagen eenmalig (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|||
|[Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))|Serving Relationship|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Verhalen kosten en schade op medewerker (Business Process)

Ook voor inhouden verkeersboetes

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[Verhalen schade op medewerker (Application Service)](#verhalen-schade-op-medewerker-(application-service))|Serving Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Aanvragen schadevergoeding (Business Process)

Aanvragen, corrigeren, intrekken en beëindigen schadevergoeding

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||
|[Registreren schadevergoeding (Application Service)](#registreren-schadevergoeding-(application-service))|Serving Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Dienstwoningen (Business Process)

Nieuwe dienstwoningen zullen niet meer worden aangemeld. Voor wijzigen van de emolumenten en huurwaardes wordt een circulaire uitgebracht. De wijzigingen van de circulaire worden aan team IC doorgegeven. Team IC geeft het vervolgens door aan team Taakaccenten.

Voor het beëindigen van de dienstwoning. Het opvoeren komt niet meer voor. Wijzigingen worden door R&O via team IC doorgegeven naar aanleiding van de circulaire.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Dienstwoningen (Business Process)](#dienstwoningen-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Bewerken dienstwoning (Application Service)](#bewerken-dienstwoning-(application-service))|Serving Relationship|[Dienstwoningen (Business Process)](#dienstwoningen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Dienstwoningen (Business Process)](#dienstwoningen-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Afrekenen verhuiskostenvergoeding (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|||
|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|Triggering Relationship|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|||
|[Declareren verhuiskosten (Application Service)](#declareren-verhuiskosten-(application-service))|Serving Relationship|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Aanvragen verhuiskostenvergoeding (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|Triggering Relationship|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|||
|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[Aanvragen verhuiskostenvergoeding (Application Service)](#aanvragen-verhuiskostenvergoeding-(application-service))|Serving Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Vergoeding telewerken (Business Process)

Valt onder IKB
Kan niet aangevraagd worden voor vrijwillig telewerken voor startdatum na 1-9-2018

Aangepaste procedures/richtlijnen voor NVWA en RWS

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|||
|[Toekennen/beëindigen telewerken (Application Service)](#toekennenbeëindigen-telewerken-(application-service))|Serving Relationship|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### ?? SBF verlof en uitkering / FLO (Business Process)

Substantieel Verzwarende Functie

Uit kennistool:
Sinds 1 oktober 2014 is de nieuwe SBF-regeling ingegaan. Hierdoor worden de nieuwe SBF-aanvragen door Loylais uitgevoerd en niet meer door P-Direkt. Toch blijft dit proces nog bestaan voor de mensen die onder de oude SBF-regeling vallen.

Wanneer een opdracht binnenkomt met het onderwerp 'loopbaanpremie SBF arrangement A tot en met C', dan kan de activiteit worden doorgezet naar Team Taakaccenten. 
De categorisering in CRM is 'Opdracht &gt; HRS &gt; VWNW'. 
Team Taakaccenten maakt het portaalformulier aan. Hiervoor dient het formulier 'Corr. Overige mutaties HRO' (optie Salaris) worden gebruikt. Dit formulier wordt na acoordering van de manager door Team Taakaccenten verwerkt onder LC0123.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### BHV toelage (Business Process)

Betreft aanvragen (HRO BHV), corrigeren (HRO BHV) en intrekken (HRO BHV & HRS)


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|||
|[Registreren BHV (Application Service)](#registreren-bhv-(application-service))|Serving Relationship|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### ?? Auto van de zaak ministers/staatssecretatissen (Business Process)

### Afrekenen gebruik dienstauto (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|Serving Relationship|[Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registreren nieuwe dienstauto (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Registreren dienstauto (Application Service)](#registreren-dienstauto-(application-service))|Serving Relationship|[Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Toe(s)lagen vast (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|||
|[Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))|Serving Relationship|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Afrekenen en beëindigen gebruik dienstauto (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Beëindigen dienstauto (Application Service)](#beëindigen-dienstauto-(application-service))|Serving Relationship|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|||
|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|Serving Relationship|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Correcties gegevens afgerekende dienstauto (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))|Realization Relationship|[Belonen en vergoeden (Business Service)](#belonen-en-vergoeden-(business-service))|||
|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|Serving Relationship|[Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### HRS (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Dienstwoningen (Business Process)](#dienstwoningen-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))|||
|[HRS (Business Role)](#hrs-(business-role))|Assignment Relationship|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Medewerker (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|||
|[Medewerker (Business Role)](#medewerker-(business-role))|Assignment Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Manager (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[?? SBF verlof en uitkering / FLO (Business Process)](#??-sbf-verlof-en-uitkering--flo-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|||
|[Manager (Business Role)](#manager-(business-role))|Assignment Relationship|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### HRO (Business Role)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|||
|[HRO (Business Role)](#hro-(business-role))|Assignment Relationship|[Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

## Applicatie (Diagram Model Group)

### ESS/MSS Portaal (P-Direkt Portaal) (Application Component)

Employee Self-Service
Manager Self-Service

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie BHV (Application Function)](#registratie-bhv-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie dienstwoningen (Application Function)](#registratie-dienstwoningen-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie schadevergoeding (Application Function)](#registratie-schadevergoeding-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie telewerken (Application Function)](#registratie-telewerken-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie schade (Application Function)](#registratie-schade-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie toe(s)lagen (Application Function)](#registratie-toe(s)lagen-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Tijdevaluatie (Application Function)

Automatische berekening contigenten en looncomponenten

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Personeels administratie op Infotypen (Application Function)

Personeelsadministratie op basis van infotypen. Elke IT is een Object met onderliggende entiteiten.Bijv. IT2001, afwezigheden, IT2006 Afwezigheidssaldo's


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|Triggering Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### SAP HCM Suite (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

#### SAP Personeels Administratie (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|Assignment Relationship|[Personeels administratie op Infotypen (Application Function)](#personeels-administratie-op-infotypen-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

#### SAP Time Management (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|Assignment Relationship|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Time Management (Application Component)](#sap-time-management-(application-component))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

#### SAP Payroll (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Tijdevaluatie (Application Function)](#tijdevaluatie-(application-function))|Serving Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||
|[SAP HCM Suite (Application Component)](#sap-hcm-suite-(application-component))|Aggregation Relationship|[SAP Payroll (Application Component)](#sap-payroll-(application-component))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### SAP GUI (Application Component)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren BHV (Application Service)](#registreren-bhv-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Gebruikersinterface voor AC02 (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|Serving Relationship|[SAP Personeels Administratie (Application Component)](#sap-personeels-administratie-(application-component))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Assignment Relationship|[Gebruikersinterface voor AC02 (Application Function)](#gebruikersinterface-voor-ac02-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registreren dienstauto (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren dienstauto (Application Service)](#registreren-dienstauto-(application-service))|Serving Relationship|[Registreren nieuwe dienstauto (Business Process)](#registreren-nieuwe-dienstauto-(business-process))|||
|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|Realization Relationship|[Registreren dienstauto (Application Service)](#registreren-dienstauto-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie dienstautos (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|Realization Relationship|[Registreren dienstauto (Application Service)](#registreren-dienstauto-(application-service))|||
|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|Realization Relationship|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|||
|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|Realization Relationship|[Beëindigen dienstauto (Application Service)](#beëindigen-dienstauto-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Afrekenen dienstautos (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|Serving Relationship|[Afrekenen gebruik dienstauto (Business Process)](#afrekenen-gebruik-dienstauto-(business-process))|||
|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|Serving Relationship|[Correcties gegevens afgerekende dienstauto (Business Process)](#correcties-gegevens-afgerekende-dienstauto-(business-process))|||
|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|Serving Relationship|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|||
|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|Realization Relationship|[Afrekenen dienstautos (Application Service)](#afrekenen-dienstautos-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Beëindigen dienstauto (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstauto (Application Service)](#beëindigen-dienstauto-(application-service))|Serving Relationship|[Afrekenen en beëindigen gebruik dienstauto (Business Process)](#afrekenen-en-beëindigen-gebruik-dienstauto-(business-process))|||
|[Registratie dienstautos (Application Function)](#registratie-dienstautos-(application-function))|Realization Relationship|[Beëindigen dienstauto (Application Service)](#beëindigen-dienstauto-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie BHV (Application Function)

Intrekken vergt handmatige verwerking door HRS

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie BHV (Application Function)](#registratie-bhv-(application-function))|Realization Relationship|[Registreren BHV (Application Service)](#registreren-bhv-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie BHV (Application Function)](#registratie-bhv-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registreren BHV (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren BHV (Application Service)](#registreren-bhv-(application-service))|Serving Relationship|[BHV toelage (Business Process)](#bhv-toelage-(business-process))|||
|[Registratie BHV (Application Function)](#registratie-bhv-(application-function))|Realization Relationship|[Registreren BHV (Application Service)](#registreren-bhv-(application-service))|||
|[SAP GUI (Application Component)](#sap-gui-(application-component))|Realization Relationship|[Registreren BHV (Application Service)](#registreren-bhv-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie verhuiskostenvergoeding (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))|Realization Relationship|[Aanvragen verhuiskostenvergoeding (Application Service)](#aanvragen-verhuiskostenvergoeding-(application-service))|||
|[Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))|Realization Relationship|[Declareren verhuiskosten (Application Service)](#declareren-verhuiskosten-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Aanvragen verhuiskostenvergoeding (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen verhuiskostenvergoeding (Application Service)](#aanvragen-verhuiskostenvergoeding-(application-service))|Serving Relationship|[Aanvragen verhuiskostenvergoeding (Business Process)](#aanvragen-verhuiskostenvergoeding-(business-process))|||
|[Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))|Realization Relationship|[Aanvragen verhuiskostenvergoeding (Application Service)](#aanvragen-verhuiskostenvergoeding-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Declareren verhuiskosten (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Declareren verhuiskosten (Application Service)](#declareren-verhuiskosten-(application-service))|Serving Relationship|[Afrekenen verhuiskostenvergoeding (Business Process)](#afrekenen-verhuiskostenvergoeding-(business-process))|||
|[Registratie verhuiskostenvergoeding (Application Function)](#registratie-verhuiskostenvergoeding-(application-function))|Realization Relationship|[Declareren verhuiskosten (Application Service)](#declareren-verhuiskosten-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie dienstwoningen (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie dienstwoningen (Application Function)](#registratie-dienstwoningen-(application-function))|Realization Relationship|[Bewerken dienstwoning (Application Service)](#bewerken-dienstwoning-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie dienstwoningen (Application Function)](#registratie-dienstwoningen-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Bewerken dienstwoning (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bewerken dienstwoning (Application Service)](#bewerken-dienstwoning-(application-service))|Serving Relationship|[Dienstwoningen (Business Process)](#dienstwoningen-(business-process))|||
|[Registratie dienstwoningen (Application Function)](#registratie-dienstwoningen-(application-function))|Realization Relationship|[Bewerken dienstwoning (Application Service)](#bewerken-dienstwoning-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie schadevergoeding (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie schadevergoeding (Application Function)](#registratie-schadevergoeding-(application-function))|Realization Relationship|[Registreren schadevergoeding (Application Service)](#registreren-schadevergoeding-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie schadevergoeding (Application Function)](#registratie-schadevergoeding-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registreren schadevergoeding (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren schadevergoeding (Application Service)](#registreren-schadevergoeding-(application-service))|Serving Relationship|[Aanvragen schadevergoeding (Business Process)](#aanvragen-schadevergoeding-(business-process))|||
|[Registratie schadevergoeding (Application Function)](#registratie-schadevergoeding-(application-function))|Realization Relationship|[Registreren schadevergoeding (Application Service)](#registreren-schadevergoeding-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie telewerken (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie telewerken (Application Function)](#registratie-telewerken-(application-function))|Realization Relationship|[Toekennen/beëindigen telewerken (Application Service)](#toekennenbeëindigen-telewerken-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie telewerken (Application Function)](#registratie-telewerken-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Toekennen/beëindigen telewerken (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Toekennen/beëindigen telewerken (Application Service)](#toekennenbeëindigen-telewerken-(application-service))|Serving Relationship|[Vergoeding telewerken (Business Process)](#vergoeding-telewerken-(business-process))|||
|[Registratie telewerken (Application Function)](#registratie-telewerken-(application-function))|Realization Relationship|[Toekennen/beëindigen telewerken (Application Service)](#toekennenbeëindigen-telewerken-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Verhalen schade op medewerker (Application Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verhalen schade op medewerker (Application Service)](#verhalen-schade-op-medewerker-(application-service))|Serving Relationship|[Verhalen kosten en schade op medewerker (Business Process)](#verhalen-kosten-en-schade-op-medewerker-(business-process))|||
|[Registratie schade (Application Function)](#registratie-schade-(application-function))|Realization Relationship|[Verhalen schade op medewerker (Application Service)](#verhalen-schade-op-medewerker-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie schade (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie schade (Application Function)](#registratie-schade-(application-function))|Realization Relationship|[Verhalen schade op medewerker (Application Service)](#verhalen-schade-op-medewerker-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie schade (Application Function)](#registratie-schade-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registreren toe(s)lagen (Application Service)

Proces voor beide bestaat uit manager of HRS die aanvraag doet en autom. goedkeuring. Bij intrekking of beëindiging goedkeuring door HRS.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))|Serving Relationship|[Toe(s)lagen eenmalig (Business Process)](#toe(s)lagen-eenmalig-(business-process))|||
|[Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))|Serving Relationship|[Toe(s)lagen vast (Business Process)](#toe(s)lagen-vast-(business-process))|||
|[Registratie toe(s)lagen (Application Function)](#registratie-toe(s)lagen-(application-function))|Realization Relationship|[Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

### Registratie toe(s)lagen (Application Function)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registratie toe(s)lagen (Application Function)](#registratie-toe(s)lagen-(application-function))|Realization Relationship|[Registreren toe(s)lagen (Application Service)](#registreren-toe(s)lagen-(application-service))|||
|[ESS/MSS Portaal (P-Direkt Portaal) (Application Component)](#essmss-portaal-(p-direkt-portaal)-(application-component))|Assignment Relationship|[Registratie toe(s)lagen (Application Function)](#registratie-toe(s)lagen-(application-function))|||

[Up](#(belonen)-toelagen,-inhoudingen-en-vergoedingen)

[embedView]: img-HR en PY service realisatie-belonen-Toelagen,-inhoudingen-en-vergoedingen.png
Generated: Fri Jan 31 2020 10:28:37 GMT+0100 (CET)
