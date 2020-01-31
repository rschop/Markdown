# Processen Verlof en verzuim

* [Introduction](#introduction)
* [Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))
* [Registreren verlof (Business Process)](#registreren-verlof-(business-process))
* [Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))
* [Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))
* [Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))
* [Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))
* [Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))
* [Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))
* [Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))
* [Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))
* [Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))
* [Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))
* [Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))
* [Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))
* [Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))
* [HR en PY (Business Service)](#hr-en-py-(business-service))
* [Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))
* [Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))
* [Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))

## Introduction

![Processen Verlof en verzuim][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Verlof en verzuim (Business Service)

Betreft alles rondom tijdsadministratie.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Registreren verlof (Business Process)

Bevat meerdere typen verlof, al dan niet op basis van contigent

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verlof (Business Process)](#registreren-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Aanvragen Zwangerschapsverlof (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Triggering Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Registreren Bevallingsdatum (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||
|[Aanvragen Zwangerschapsverlof (Business Process)](#aanvragen-zwangerschapsverlof-(business-process))|Triggering Relationship|[Registreren Bevallingsdatum (Business Process)](#registreren-bevallingsdatum-(business-process))|||

[Up](#processen-verlof-en-verzuim)

## Aanvragen Adoptie-/pleegzorgverlof (Business Process)

Heeft 'Registreren kindgegevens' ingebouwd

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen Adoptie-/pleegzorgverlof (Business Process)](#aanvragen-adoptie-pleegzorgverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Aanvragen Ouderschapsverlof (Business Process)

Verschillende regelingen
- Gebaseerd op CAO of organisatie
- Afhankelijk van tijd geboorte (2015, 2017, etc)
- Heeft gevolgen voor salaris

Heeft 'Registreren kindgegevens' ingebouwd


**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen Ouderschapsverlof (Business Process)](#aanvragen-ouderschapsverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Aanvragen langdurig buitengewoon verlof (Business Process)

Regelingen afhankelijk van organisatie
Gevolg voor salaris & aanwezigheid

Niet zelf registreren

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen langdurig buitengewoon verlof (Business Process)](#aanvragen-langdurig-buitengewoon-verlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Verminderen verlofrecht (Business Process)

Trigger vanuit andere processen (zoals disciplinaire staf)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Verminderen verlofrecht (Business Process)](#verminderen-verlofrecht-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Raadplegen verzuim (Business Process)

Als los proces opgenomen omdat sommige mutaties in de SAP-backend worden gedaan. Er wordt hier actief verwezen naar het inzien van de huidige stand van zaken via het portaal.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Raadplegen verzuim (Business Process)](#raadplegen-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Registreren verzuim (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren verzuim (Business Process)](#registreren-verzuim-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Corrigeren verzuimgegevens (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren verzuimgegevens (Business Process)](#corrigeren-verzuimgegevens-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Corrigeren casemanager (Business Process)

Manager is de standaard casemanager, dit proces voor afwijkingen

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren casemanager (Business Process)](#corrigeren-casemanager-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Poortwachter beheren (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Poortwachter beheren (Business Process)](#poortwachter-beheren-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Aanvragen WIA uitkering (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanvragen WIA uitkering (Business Process)](#aanvragen-wia-uitkering-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Corrigeren compensatieverlof (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren compensatieverlof (Business Process)](#corrigeren-compensatieverlof-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Registreren arbeidsduur, werktijd en rooster (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren arbeidsduur, werktijd en rooster (Business Process)](#registreren-arbeidsduur,-werktijd-en-rooster-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Registreren PAS-regeling (Business Process)

Partiële Arbeidsparticipatie Senioren

Uitzonderingen PAS (documentatie CC):
- Rechterlijke macht/Rechtspraak: 2 PAS-regelingen. Voor 57+ (kleine PAS) en 61+ (grote PAS).
- 1e & 2e kamer: Personenchauffeurs ontvangen een periodieke toelage
- MinDef: voor hen geld burgerlijk ambtenarenreglement Defensie met soortgelijke regeling. Medewerkers die met Rijksvastgoed naar BZK zijn gegaan vallen nu onder ARAR
- I&M: PAS-formulier gaat eerst langs roosterbeheerder

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren PAS-regeling (Business Process)](#registreren-pas-regeling-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

## Corrigeren arbeidsduur/werktijd/PAS (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren arbeidsduur/werktijd/PAS (Business Process)](#corrigeren-arbeidsduurwerktijdpas-(business-process))|Realization Relationship|[Verlof en verzuim (Business Service)](#verlof-en-verzuim-(business-service))|||

[Up](#processen-verlof-en-verzuim)

[embedView]: img-Overzicht processen per business service-Processen-Verlof-en-verzuim.png
Generated: Fri Jan 31 2020 10:28:49 GMT+0100 (CET)
