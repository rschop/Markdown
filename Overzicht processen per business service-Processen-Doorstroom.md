# Processen Doorstroom

* [Introduction](#introduction)
* [Doorstroom (Business Service)](#doorstroom-(business-service))
* [Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))
* [Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))
* [Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))
* [Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))
* [HR en PY (Business Service)](#hr-en-py-(business-service))

## Introduction

![Processen Doorstroom][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Doorstroom (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#processen-doorstroom)

## Beëindigen dienstverband (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Triggering Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#processen-doorstroom)

## Nabewerkingsprocessen portaal met financiële impact (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Triggering Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||

[Up](#processen-doorstroom)

## Wijzigen/intrekken beëindigen dienstverband (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#processen-doorstroom)

## Wijzigen aanstellingsgegevens (Business Process)

Op moment dat bijv. tijdelijk contract afloopt moet de aanstelling gewijzigd worden.

Wordt automatisch ontslag gegenereerd wanneer geen actie wordt ondernomen.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|Realization Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#processen-doorstroom)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Doorstroom (Business Service)](#doorstroom-(business-service))|||

[Up](#processen-doorstroom)

[embedView]: img-Overzicht processen per business service-Processen-Doorstroom.png
Generated: Fri Jan 31 2020 10:28:48 GMT+0100 (CET)
