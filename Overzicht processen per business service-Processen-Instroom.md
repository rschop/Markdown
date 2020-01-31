# Processen Instroom

* [Introduction](#introduction)
* [Instroom (Business Service)](#instroom-(business-service))
* [Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))
* [Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))
* [Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))
* [Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))
* [Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))
* [HR en PY (Business Service)](#hr-en-py-(business-service))
* [Warm welkom (Product)](#warm-welkom-(product))
* [Afkortingen app (Product)](#afkortingen-app-(product))

## Introduction

![Processen Instroom][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Instroom (Business Service)

WNRA gaat hier wijzigingen in aanbrengen

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Warm welkom (Product)](#warm-welkom-(product))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Afkortingen app (Product)](#afkortingen-app-(product))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

## Registreren nieuwe medewerker (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Triggering Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#processen-instroom)

## Aanstellen nieuwe medewerker (Business Process)

Gaan meldingen naar UWV

VOG, WID-scan

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||
|[Registreren nieuwe medewerker (Business Process)](#registreren-nieuwe-medewerker-(business-process))|Triggering Relationship|[Aanstellen nieuwe medewerker (Business Process)](#aanstellen-nieuwe-medewerker-(business-process))|||

[Up](#processen-instroom)

## Registreren Arbeidsverleden (Business Process)

Wordt meegenomen in bepalen ambtsjubileum

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Registreren Arbeidsverleden (Business Process)](#registreren-arbeidsverleden-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

## Corrigeren aanstellingsgegevens (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Corrigeren aanstellingsgegevens (Business Process)](#corrigeren-aanstellingsgegevens-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

## Aanstelling verwijderen (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Aanstelling verwijderen (Business Process)](#aanstelling-verwijderen-(business-process))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

## Warm welkom (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Warm welkom (Product)](#warm-welkom-(product))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

## Afkortingen app (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afkortingen app (Product)](#afkortingen-app-(product))|Realization Relationship|[Instroom (Business Service)](#instroom-(business-service))|||

[Up](#processen-instroom)

[embedView]: img-Overzicht processen per business service-Processen-Instroom.png
Generated: Fri Jan 31 2020 10:28:48 GMT+0100 (CET)
