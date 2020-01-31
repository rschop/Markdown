# Processen Uitstroom

* [Introduction](#introduction)
* [Uitstroom (Business Service)](#uitstroom-(business-service))
* [HR en PY (Business Service)](#hr-en-py-(business-service))
* [Exit enquetes (Product)](#exit-enquetes-(product))
* [Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))
* [Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))
* [Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))
* [Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))

## Introduction

![Processen Uitstroom][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Uitstroom (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||
|[Exit enquetes (Product)](#exit-enquetes-(product))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||
|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||
|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||
|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#processen-uitstroom)

## HR en PY (Business Service)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[HR en PY (Business Service)](#hr-en-py-(business-service))|Aggregation Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#processen-uitstroom)

## Exit enquetes (Product)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Exit enquetes (Product)](#exit-enquetes-(product))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#processen-uitstroom)

## Wijzigen aanstellingsgegevens (Business Process)

Op moment dat bijv. tijdelijk contract afloopt moet de aanstelling gewijzigd worden.

Wordt automatisch ontslag gegenereerd wanneer geen actie wordt ondernomen.

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen aanstellingsgegevens (Business Process)](#wijzigen-aanstellingsgegevens-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#processen-uitstroom)

## Wijzigen/intrekken beëindigen dienstverband (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Wijzigen/intrekken beëindigen dienstverband (Business Process)](#wijzigenintrekken-beëindigen-dienstverband-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#processen-uitstroom)

## Nabewerkingsprocessen portaal met financiële impact (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Triggering Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||

[Up](#processen-uitstroom)

## Beëindigen dienstverband (Business Process)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Triggering Relationship|[Nabewerkingsprocessen portaal met financiële impact (Business Process)](#nabewerkingsprocessen-portaal-met-financiële-impact-(business-process))|||
|[Beëindigen dienstverband (Business Process)](#beëindigen-dienstverband-(business-process))|Realization Relationship|[Uitstroom (Business Service)](#uitstroom-(business-service))|||

[Up](#processen-uitstroom)

[embedView]: img-Overzicht processen per business service-Processen-Uitstroom.png
Generated: Fri Jan 31 2020 10:28:48 GMT+0100 (CET)
