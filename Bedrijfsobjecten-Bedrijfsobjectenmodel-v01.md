# Bedrijfsobjectenmodel v01

* [Introduction](#introduction)
* [Medewerker (Business Object)](#medewerker-(business-object))
* [Organisatie (Business Object)](#organisatie-(business-object))
* [Formatieplaats (Business Object)](#formatieplaats-(business-object))
* [Functie (Business Object)](#functie-(business-object))
* [Kostenplaats (Business Object)](#kostenplaats-(business-object))
* [Sollicitant (Business Object)](#sollicitant-(business-object))
* [Belangstellende (Business Object)](#belangstellende-(business-object))
* [Evenement (Business Object)](#evenement-(business-object))
* [Vacature (Business Object)](#vacature-(business-object))
* [Afspraak (Business Object)](#afspraak-(business-object))
* [Externe medewerker (Business Object)](#externe-medewerker-(business-object))
* [Contract (Business Object)](#contract-(business-object))
* [Gebeurtenis (Business Object)](#gebeurtenis-(business-object))
* [Rooster (Business Object)](#rooster-(business-object))
* [Verlof/verzuim (Business Object)](#verlofverzuim-(business-object))
* [Kandidaat (Business Object)](#kandidaat-(business-object))
* [Casus (Business Object)](#casus-(business-object))
* [Trajectbegeleider (Business Object)](#trajectbegeleider-(business-object))
* [Participant (Business Object)](#participant-(business-object))
* [Module (Business Object)](#module-(business-object))
* [Instrument (Business Object)](#instrument-(business-object))
* [Personeelsgesprek (Business Object)](#personeelsgesprek-(business-object))
* [Opleiding (Business Object)](#opleiding-(business-object))
* [Kwalificatie (Business Object)](#kwalificatie-(business-object))
* [Bezoldiging (Business Object)](#bezoldiging-(business-object))
* [Interne medewerker (Business Object)](#interne-medewerker-(business-object))
* [Uurtarief (Business Object)](#uurtarief-(business-object))
* [Leverancier (Business Object)](#leverancier-(business-object))
* [Recruiter (Business Object)](#recruiter-(business-object))

## Introduction

![Bedrijfsobjectenmodel v01][embedView]

Meer input nodig, staat niet in de kennistool en zijn geen standaardprocessen.
> Nakisa, maar ook Reotool moeten hiervoor in kaart worden gebracht.

TODO Applicatielaag

## Medewerker (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Object)](#medewerker-(business-object))|Association Relationship|[Rooster (Business Object)](#rooster-(business-object))|||
|[Medewerker (Business Object)](#medewerker-(business-object))|Association Relationship|[Verlof/verzuim (Business Object)](#verlofverzuim-(business-object))|||
|[Medewerker (Business Object)](#medewerker-(business-object))|Association Relationship|[Kandidaat (Business Object)](#kandidaat-(business-object))|||
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Sollicitant (Business Object)](#sollicitant-(business-object))|Association Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Gebeurtenis (Business Object)](#gebeurtenis-(business-object))|Association Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Externe medewerker (Business Object)](#externe-medewerker-(business-object))|Specialization Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|Specialization Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Organisatie (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie (Business Object)](#organisatie-(business-object))|Association Relationship|[Kostenplaats (Business Object)](#kostenplaats-(business-object))|||
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Organisatie (Business Object)](#organisatie-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Formatieplaats (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Organisatie (Business Object)](#organisatie-(business-object))|||
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Functie (Business Object)](#functie-(business-object))|||
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Vacature (Business Object)](#vacature-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Functie (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Functie (Business Object)](#functie-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Kostenplaats (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Organisatie (Business Object)](#organisatie-(business-object))|Association Relationship|[Kostenplaats (Business Object)](#kostenplaats-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Sollicitant (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Sollicitant (Business Object)](#sollicitant-(business-object))|Association Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Sollicitant (Business Object)](#sollicitant-(business-object))|Association Relationship|[Vacature (Business Object)](#vacature-(business-object))|||
|[Belangstellende (Business Object)](#belangstellende-(business-object))|Association Relationship|[Sollicitant (Business Object)](#sollicitant-(business-object))|||
|[Afspraak (Business Object)](#afspraak-(business-object))|Association Relationship|[Sollicitant (Business Object)](#sollicitant-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Belangstellende (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Belangstellende (Business Object)](#belangstellende-(business-object))|Association Relationship|[Sollicitant (Business Object)](#sollicitant-(business-object))|||
|[Evenement (Business Object)](#evenement-(business-object))|Association Relationship|[Belangstellende (Business Object)](#belangstellende-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Evenement (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Evenement (Business Object)](#evenement-(business-object))|Association Relationship|[Belangstellende (Business Object)](#belangstellende-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Vacature (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Formatieplaats (Business Object)](#formatieplaats-(business-object))|Association Relationship|[Vacature (Business Object)](#vacature-(business-object))|||
|[Sollicitant (Business Object)](#sollicitant-(business-object))|Association Relationship|[Vacature (Business Object)](#vacature-(business-object))|||
|[Recruiter (Business Object)](#recruiter-(business-object))|Association Relationship|[Vacature (Business Object)](#vacature-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Afspraak (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Afspraak (Business Object)](#afspraak-(business-object))|Association Relationship|[Sollicitant (Business Object)](#sollicitant-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Externe medewerker (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Externe medewerker (Business Object)](#externe-medewerker-(business-object))|Specialization Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Uurtarief (Business Object)](#uurtarief-(business-object))|Association Relationship|[Externe medewerker (Business Object)](#externe-medewerker-(business-object))|||
|[Leverancier (Business Object)](#leverancier-(business-object))|Association Relationship|[Externe medewerker (Business Object)](#externe-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Contract (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Contract (Business Object)](#contract-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Gebeurtenis (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Gebeurtenis (Business Object)](#gebeurtenis-(business-object))|Association Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Rooster (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Object)](#medewerker-(business-object))|Association Relationship|[Rooster (Business Object)](#rooster-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Verlof/verzuim (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Medewerker (Business Object)](#medewerker-(business-object))|Association Relationship|[Verlof/verzuim (Business Object)](#verlofverzuim-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Kandidaat (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Kandidaat (Business Object)](#kandidaat-(business-object))|Association Relationship|[Casus (Business Object)](#casus-(business-object))|||
|[Medewerker (Business Object)](#medewerker-(business-object))|Association Relationship|[Kandidaat (Business Object)](#kandidaat-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Casus (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Casus (Business Object)](#casus-(business-object))|Association Relationship|[Participant (Business Object)](#participant-(business-object))|||
|[Casus (Business Object)](#casus-(business-object))|Association Relationship|[Module (Business Object)](#module-(business-object))|||
|[Kandidaat (Business Object)](#kandidaat-(business-object))|Association Relationship|[Casus (Business Object)](#casus-(business-object))|||
|[Trajectbegeleider (Business Object)](#trajectbegeleider-(business-object))|Association Relationship|[Casus (Business Object)](#casus-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Trajectbegeleider (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Trajectbegeleider (Business Object)](#trajectbegeleider-(business-object))|Association Relationship|[Casus (Business Object)](#casus-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Participant (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Casus (Business Object)](#casus-(business-object))|Association Relationship|[Participant (Business Object)](#participant-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Module (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Module (Business Object)](#module-(business-object))|Association Relationship|[Instrument (Business Object)](#instrument-(business-object))|||
|[Casus (Business Object)](#casus-(business-object))|Association Relationship|[Module (Business Object)](#module-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Instrument (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Module (Business Object)](#module-(business-object))|Association Relationship|[Instrument (Business Object)](#instrument-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Personeelsgesprek (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Personeelsgesprek (Business Object)](#personeelsgesprek-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Opleiding (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Opleiding (Business Object)](#opleiding-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Kwalificatie (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Kwalificatie (Business Object)](#kwalificatie-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Bezoldiging (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Bezoldiging (Business Object)](#bezoldiging-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Interne medewerker (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|Specialization Relationship|[Medewerker (Business Object)](#medewerker-(business-object))|||
|[Kwalificatie (Business Object)](#kwalificatie-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||
|[Opleiding (Business Object)](#opleiding-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||
|[Personeelsgesprek (Business Object)](#personeelsgesprek-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||
|[Bezoldiging (Business Object)](#bezoldiging-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||
|[Contract (Business Object)](#contract-(business-object))|Association Relationship|[Interne medewerker (Business Object)](#interne-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Uurtarief (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Uurtarief (Business Object)](#uurtarief-(business-object))|Association Relationship|[Externe medewerker (Business Object)](#externe-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Leverancier (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Leverancier (Business Object)](#leverancier-(business-object))|Association Relationship|[Externe medewerker (Business Object)](#externe-medewerker-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

## Recruiter (Business Object)

**Relationships**
|From|Relationship|To|Name|Description|
|---|---|---|---|---|
|[Recruiter (Business Object)](#recruiter-(business-object))|Association Relationship|[Vacature (Business Object)](#vacature-(business-object))|||

[Up](#bedrijfsobjectenmodel-v01)

[embedView]: img-Bedrijfsobjecten-Bedrijfsobjectenmodel-v01.png
Generated: Fri Jan 31 2020 10:28:45 GMT+0100 (CET)
