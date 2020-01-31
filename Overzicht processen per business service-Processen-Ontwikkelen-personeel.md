# Processen Ontwikkelen personeel

* [Introduction](#introduction)
* [Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))
* [Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))
* [Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))
* [Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))
* [Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))
* [Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))
* [Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))
* [Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))
* [HR en PY (Business Service)](#hr-en-py-(business-service))
* [Registreren P-Schouw (Business Process)](#registreren-p-schouw-(business-process))
* [Functieruil (Product)](#functieruil-(product))

## Introduction

![Processen Ontwikkelen personeel][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Ontwikkelen personeel (Business Service)

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
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Registreren P-Schouw (Business Process)](#registreren-p-schouw-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Functieruil (Product)](#functieruil-(product))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Registreren personeelsgesprek (Business Process)

Zowel manager als medewerker moeten akkoord geven op functioneringsgesprek.
Geldt niet voor beoordelingsgesprek

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren personeelsgesprek (Business Process)](#registreren-personeelsgesprek-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Aanvragen rapportage HRO personeelsgesprekken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen rapportage HRO personeelsgesprekken (Business Process)](#aanvragen-rapportage-hro-personeelsgesprekken-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Aanvragen rapportage manager personeelsgesprekken (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen rapportage manager personeelsgesprekken (Business Process)](#aanvragen-rapportage-manager-personeelsgesprekken-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Registreren beoordelingsdatum (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren beoordelingsdatum (Business Process)](#registreren-beoordelingsdatum-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Aanvragen/wijzigen studiefaciliteit (Business Process)

Kan ook voorschot krijgen

Kan hier ook meteen opleiding registreren

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Triggering Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||

[Up](#processen-ontwikkelen-personeel)

## Afrekenen studiefaciliteit (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||
|[Aanvragen/wijzigen studiefaciliteit (Business Process)](#aanvragenwijzigen-studiefaciliteit-(business-process))|Triggering Relationship|[Afrekenen studiefaciliteit (Business Process)](#afrekenen-studiefaciliteit-(business-process))|||

[Up](#processen-ontwikkelen-personeel)

## Registreren afgeronde opleiding (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren afgeronde opleiding (Business Process)](#registreren-afgeronde-opleiding-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Registreren P-Schouw (Business Process)

Managerstool -&gt; input voor p-gesprekken. Puur registratie, geen koppeling.
Huidige oplossing maatwerk

Komt niet in P-dossier

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren P-Schouw (Business Process)](#registreren-p-schouw-(business-process))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

## Functieruil (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Functieruil (Product)](#functieruil-(product))|Realization Relationship|[Ontwikkelen personeel (Business Service)](#ontwikkelen-personeel-(business-service))|||

[Up](#processen-ontwikkelen-personeel)

[embedView]: img-Overzicht processen per business service-Processen-Ontwikkelen-personeel.png
Generated: Fri Jan 31 2020 10:28:49 GMT+0100 (CET)
