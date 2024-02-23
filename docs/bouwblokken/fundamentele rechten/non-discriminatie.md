---
title: Non-discriminatie
summary: hier staat een korte samenvatting over dit onderwerp
---
!!! info "Disclaimer"

    Het Algoritmekader is nog volop in ontwikkeling. Op deze plek willen we vooral aan de slag gaan op een open en transparante wijze. Het is dus niet definitief. Dat betekent dat er dingen opstaan die niet af zijn en soms zelfs fout. Mocht er iets niet kloppen, laat het ons weten via [GitHub](https://github.com/MinBZK/Algoritmekader).

## Waarom?
Hier is plek voor een algemene beschrijving van dit bouwblok. Neem hier in ieder geval op:

- waar gaat dit bouwblok over
- zijn er eventueel deelonderwerpen die behoren tot dit bouwblok? Zo ja welke? En verwijzen indien dit een aparte pagina betreft.
- waarom is dit bouwblok belangrijk?
- eventueel definities of toelichting van bepaalde begrippen die relevant zijn voor dit bouwblok

## Definities
In deze sectie werken we relevante definities uit die horen bij het bouwblok bias en non-discriminatie. Dat betekent dat we eerst een overzicht maken van bestaande definities, waarna we per begrip een besluit nemen welke defintie we zullen gebruiken in het algoritmekader. 

### Bias 

De term **bias** wordt in veel verschillende contexten en disciplines gebruikt en kan daardoor ook verschillende betekenissen hebben. Als eerste zoeken we naar een definitie van bias zoals die in algoritmische context bedoeld en gebruikt wordt. 

| Definitie                                                                                                                                                                                                                       | Bron                                                                                                                                                                         | Opmerking                                                                                                                                                                                                                                                                    |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| systematic difference in treatment of certain objects, people, or groups in comparison to others. *Note 1 to entry: Treatment is any kind of action, including perception, observation, representation, prediction or decision* | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en)                                                                                        | NL vertaling door DeepL: "systematisch verschil in behandeling van bepaalde objecten, mensen of groepen in vergelijking met andere. Noot 1 bij aantekening: Behandeling is elke vorm van actie, inclusief waarneming, observatie, representatie, voorspelling of beslissing" |
| Differential treatment based on protected characteristics, such as discrimination and bias-motivated crimes                                                                                                                     | [European Union Agency for Fundamental Rights - bias in algorithms](http://fra.europa.eu/sites/default/files/fra_uploads/fra-2022-bias-in-algorithms_en.pdf)                 | NL vertaling door DeepL: "Gedifferentieerde behandeling op basis van beschermde kenmerken, zoals discriminatie en misdrijven op basis van vooroordelen"                                                                                                                      |
| onwenselijke systematische afwijking                                                                                                                                                                                            | [Toetsingskader Algemene Rekenkamer](https://www.rekenkamer.nl/onderwerpen/algoritmes-digitaal-toetsingskader/documenten/publicaties/2021/01/28/download-het-toetsingskader) | Is bias altijd onwenselijk?                                                                                                                                                                                                                                                  |
| systematische afwijking voor specifieke personen, groepen of andere eenheden                                                                                                                                                    | [Onderzoekskader Algoritmes Auditdienst Rijk](https://www.rijksoverheid.nl/documenten/rapporten/2023/07/11/onderzoekskader-algoritmes-adr-2023)                              |                                                                                                                                                                                                                                                                              |
 
> Hoe vertalen we bias? Willen we dit vertalen? Vooringenomenheid, vertekening? 

Vervolgens specificeren we verschillende vormen van bias:

| Definitie                                                                                                                                                                                      | Bron                                                                                  | Opmerking                                                                                                                                                                                                                                                                    |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **automation bias:** propensity for humans to favour suggestions from automated decision-making systems and to ignore contradictory information made without automation, even if it is correct | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en) | NL vertaling door DeepL: "automatiseringsvooringenomenheid: de neiging van mensen om de voorkeur te geven aan suggesties van geautomatiseerde besluitvormingssystemen en om tegenstrijdige informatie te negeren die zonder automatisering is verkregen, zelfs als deze correct is" |
| **human cognitive bias:** bias that occurs when humans are processing and interpreting information. *Note 1 to entry: human cognitive bias influences judgement and decision-making.*          | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en) | NL vertaling door DeepL: "menselijke cognitieve vooringenomenheid: vooringenomenheid die optreedt wanneer mensen informatie verwerken en interpreteren. *Noot 1 bij item: menselijke cognitieve vooringenomenheid beïnvloedt oordeelsvorming en besluitvorming.*" |
| **confirmation bias:** type of human cognitive bias that favours predictions of AI systems that confirm pre-existing beliefs or hypotheses                                                     | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en) | NL vertaling door DeepL: "confirmation bias: soort menselijke cognitieve bias die de voorkeur geeft aan voorspellingen van AI-systemen die reeds bestaande overtuigingen of hypotheses bevestigen" |
| **data bias:** data properties that if unaddressed lead to AI systems that perform better or worse for different groups                                                                        | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en) | NL vertaling door DeepL: "gegevensvooringenomenheid: gegevenseigenschappen die, als ze niet worden aangepakt, leiden tot AI-systemen die beter of slechter presteren voor verschillende groepen" |
| **statistical bias:** type of consistent numerical offset in an estimate relative to the true underlying value, inherent to most estimates                                                     | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en) | NL vertaling door DeepL: "statistische vertekening: soort consistente numerieke afwijking in een schatting ten opzichte van de werkelijke onderliggende waarde, inherent aan de meeste schattingen" |

### Vooringenomenheid

| Definitie                                                                                         | Bron                                                                                                                                                                                              | Opmerking |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| met een vooroordeel, partijdig | [Van Dale](https://www.vandale.nl/gratis-woordenboek/nederlands/betekenis/vooringenomen) |           |
|  

### Discriminatie

#### Directe discriminatie
| Definitie                                                                                                                                                                                  | Bron                                                                                                                                                                                    | Opmerking |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| De ongelijke behandeling van een persoon of groep personen ten opzichte van andere personen in een vergelijkbare situatie, op grond van een beschermd persoonskenmerk (discriminatiegrond) | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |           |
| takes place when a person receives less favourable treatment than another in a comparable situation, based on a protected ground                                                           | [European Union Agency for Fundamental Rights - bias in algorithms](http://fra.europa.eu/sites/default/files/fra_uploads/fra-2022-bias-in-algorithms_en.pdf)                            | NL vertaling door DeepL: "vindt plaats wanneer een persoon een minder gunstige behandeling krijgt dan een ander in een vergelijkbare situatie, op basis van een beschermde grond"          |

#### Indirecte discriminatie
| Definitie                                                                                                                                                                                                                                                             | Bron                                                                                                                                                                                    | Opmerking |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| Wanneer een ogenschijnlijk neutrale bepaling, maatstaf of handelwijze personen met een bepaald beschermd persoonskenmerk (discriminatiegrond) in vergelijking met andere personen in het bijzonder benadeelt, tenzij hiervoor een objectieve rechtvaardiging bestaat. | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |
| takes place when an apparently neutral provision, criterion or practice puts people with a particular protected characteristic at a disadvantage compared with others;                                                                                                | [European Union Agency for Fundamental Rights - bias in algorithms](http://fra.europa.eu/sites/default/files/fra_uploads/fra-2022-bias-in-algorithms_en.pdf)                            | NL vertaling door DeepL: "vindt plaats wanneer een ogenschijnlijk neutrale bepaling, criterium of praktijk mensen met een bepaald beschermd kenmerk benadeelt ten opzichte van anderen"           |


### Onderscheid
| Definitie                                                                                                                                                                                                                                                                                      | Bron                                                                                                                                                                                    | Opmerking |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| Om te bepalen of een risicoprofiel **onderscheid** maakt op grond van ras of nationaliteit moet worden bekeken of er sprake is van 1. een ongelijke behandeling van een persoon of groep personen; 2. in verhouding tot anderen in een vergelijkbare situatie; 3. op basis van nationaliteit of ras | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce)                                                                                                   |           |


#### Direct onderscheid
| Definitie                                                                                                                                                                                                                                                                                      | Bron                                                                                                                                                                                    | Opmerking |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| Indien een persoon op een andere wijze wordt behandeld dan een ander in een vergelijkbare situatie wordt, is of zou worden behandeld, op grond van godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht, nationaliteit, hetero- of homoseksuele gerichtheid of burgerlijke staat | [Algemene wet gelijke behandeling](https://wetten.overheid.nl/BWBR0006502/2020-01-01)                                                                                                   |           |

#### Indirect onderscheid
| Definitie                                                                                                                                                                                                                                                                                       | Bron                                                                                                                                                                                    | Opmerking |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| indien een ogenschijnlijk neutrale bepaling, maatstaf of handelwijze personen met een bepaalde godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht, nationaliteit, hetero- of homoseksuele gerichtheid of burgerlijke staat in vergelijking met andere personen bijzonder treft. | [Algemene wet gelijke behandeling](https://wetten.overheid.nl/BWBR0006502/2020-01-01)                                                                                                   |           |

### Fairness (nederlandse term?), eerlijkheid, rechtvaardigheid, justice
### Beschermde persoonskenmerken en bijzondere kenmerken (omstreden variabelen)
### Gouden standaard / ground truth
### Gerechtvaardigd belang
### (Etnisch) profileren
### Proxy

| Definitie                                                                                         | Bron                                                                                                                                                                                              | Opmerking |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| a variable that can stand in for another, usually nor directly observable or measurable, variable | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |           |
|                                                                                                   |                                                                                                                                                                                                   |           |

### Groep
| Definitie                                                                                         | Bron                                                                                                                                                                                              | Opmerking |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| subset of objects in a domain that are linked because they have shared characteristics | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en) |           |
| 

--- 

## Bias en non-discriminatie ten opzichte van de levenscyclus

| **Fase levenscyclus**                                                                            |               **Relevant ja/nee**               | **Toelichting**                                                                                                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------|:-----------------------------------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Probleemanalyse](../../levenscyclus/probleemanalyse.md)                                         |                                                 |                                                                                                                                                                                                                                                          |
| [Ontwerp](../../levenscyclus/ontwerp.md)                                                         | :material-check-bold:{ style="color: #4DB6AC" } |                                                                                                                                                                                                                                                          |
| [Data verkennen en data preparatie](../../levenscyclus/data%20verkenning%20en%20data%20preparatie.md) | :material-check-bold:{ style="color: #4DB6AC" } | De vraag is of dit voldoende plek is voor een toelichting. Hoe veel tekst willen we hier precies kwijt? Je kan hier best een tijdje doortypen, maar deze vorm van weergeven is misschien niet heel geschikt als je hier heel veel meer tekst kwijt wilt. |
| [Ontwikkelen](../../levenscyclus/ontwikkelen.md)                                                 |                                                 |                                                                                                                                                                                                                                                          |
| [Validatie](../../levenscyclus/validatie.md)                                                     |                                                 |                                                                                                                                                                                                                                                          |
| [Implementatie](../../levenscyclus/implementatie.md)                                             | :material-check-bold:{ style="color: #4DB6AC" } |                                                                                                                                                                                                                                                          |
| [Monitoren](../../levenscyclus/monitoren.md)                                                     | :material-check-bold:{ style="color: #4DB6AC" } |                                                                                                                                                                                                                                                          |
| [Archiveren](../../levenscyclus/archiveren.md)                                                   | :material-check-bold:{ style="color: #4DB6AC" } |

Per fase van de levenscyclus lichten we toe welke vormen van bias kunnen onstaan.

### Probleemanalyse
### Ontwerp
### Data verkennen en data preparatie
### Ontwikkelen
### Validatie
### Implementatie
### Monitoren
### Archiveren

## Normen

Onderstaand een overzicht van de minimale vereisten die volgen uit geldende wet- en regelgeving, toetingskaders en andere bronnen

=== "Laag risico" 

    | **Norm**                          | **Uitleg**                               | **Bron** |
    |-----------------------------------|------------------------------------------|----------|
    | Norm 2                             | Korte uitleg over norm 2                |          |
    
=== "Hoog risico"

    | **Norm**                          | **Uitleg**                               | **Bron** |
    |-----------------------------------|------------------------------------------|----------|
    | Verbod op ongelijke behandeling in gelijke omstandigheden. Discriminatie wegens godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht of op welke grond dan ook, is niet toegestaan    | Korte uitleg over norm 1                |          | IKA1.0
    | Norm 2                             | Korte uitleg over norm 2                |          |
    | Norm 3                             | Korte uitleg over norm 3                |          |
    | Norm 4                             | Korte uitleg over norm 4                |          |


## Rollen
Overzicht van welke rollen belangrijk zijn te betrekken bij dit bouwblok. 

<div class="grid cards" markdown>

- __technische expert__ bron: handreiking non-discriminatie by design
- __projectleider__ bron: handreiking non-discriminatie by design
- __jurist__ bron: handreiking non-discriminatie by design
- __functionaris gegevensbescherming__ bron: handreiking non-discriminatie by design
- __relevante stakeholders__ bron: handreiking non-discriminatie by design
- __domein expert__ bron: handreiking non-discriminatie by design
- __data steward__ bron: handreiking non-discriminatie by design
- __data analist__ bron: handreiking non-discriminatie by design
- __beleid__ bron: evaluatie handreiking non-discriminatie by design door ADR

</div>

## Aanbevelingen
[Rathenau](https://www.rathenau.nl/nl/digitalisering/algoritmes-afwegen)

* Geef als uitvoeringsorganisatie meer inzicht in hoe biastoetsing plaatsvindt 
* Zet een nationaal kennisplatform voor biastoetsing op waar expertise kan worden ontwikkeld en gedeeld. Bepaal welke mate van standaardisatie gewenst is en of wettelijke eisen nodig zijn.

[ADR](https://open.overheid.nl/documenten/7052294a-e70a-4084-88da-d09ae5f202cb/file)

* Plaats de handreiking in een kader in relatie tot andere instrumenten 
* Overweeg een risicogerichte benadering voor de toepassing van de handreiking 
* Werk aan het vergroten van bewustzijn voor algoritmen en (data-)ethiek in de organisatie 
* Zorg voor duidelijkheid in taken en verantwoordelijkheden van verschillende betrokkenen 
* Beleg verantwoordelijkheid voor de handreiking en borg de (blijvende) aandacht ervoor 
* Verplichte toepassing van de handreiking kan bestaande initiatieven tenietdoen 

[Toetsingskader ADR](https://open.overheid.nl/documenten/61b54381-d331-40ed-8fce-b2883b195f25/file)

* De definitie van de verschillende groepen en de gewenste prestatie van het model voor deze groepen zijn opgenomen in de functionele eisen.
* De mate van geaccepteerde bias in de uitkomst is opgenomen in de functionele eisen en uitgewerkt in meetbare prestatiecriteria.
* De methoden om bias te voorkomen, detecteren en corrigeren zijn vastgelegd.
* De mate van bias in de data, dataverzameling en het model zijn in kaart gebracht.
* Tijdens de ontwikkeling van het model is beoordeeld of er een verschil bestaat tussen de prestatie van het model tussen verschillende subgroepen. De prestatiemetrieken afleidbaar uit de confusionmatrix zijn vergeleken voor deze subgroepen.
* De uitkomstbias van productiedata is beoordeeld voor de verschillende subgroepen en voldoet aan de prestatiecriteria.
* Bij de geconstateerde bias is beoordeeld of deze op discriminatie duidt.

[College voor de Rechten van de Mens](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) (Richtlijnen)

* Overheidsinstanties mogen bij opsporings- en handhavingsbevoegdheden, met het oog op effectiviteit, efficiëntie en kostenbesparing, gebruik maken van risicoprofielen. Binnen deze risicoprofielen mogen ervaringsgegevens die tot een bepaalde vooronderstelling leiden een rol spelen, tenzij dit leidt tot discriminatie op grond van ras of nationaliteit
* Risicoprofielen die uitsluitend of in doorslaggevende mate gebaseerd zijn op ras (waaronder etniciteit en afkomst) zijn in strijd met het discriminatieverbod;
* Risicoprofielen die zich richten op één bepaalde afkomst of nationaliteit hebben een stigmatiserend effect en zijn daarom strijdig met het discriminatieverbod;
* Risicoprofielen die uitsluitend gebaseerd zijn op nationaliteit zijn zeer moeilijk te rechtvaardigen;
* Risicoprofielen waarin ras of nationaliteit mede een rol speelt, kunnen slechts gerechtvaardigd worden door zeer zwaarwegende redenen;
* Het gebruik van ras of nationaliteit als selectiecriterium binnen een risicoprofiel is nooit toegestaan als er geen objectieve relatie kan worden aangetoond tussen dit selectiecriterium en het legitieme doel van het profiel;
* In alle gevallen moeten de selectiecriteria  binnen een risicoprofiel samen voldoende relevant en objectief (geschikt) zijn om op een effectieve wijze bij te dragen aan de verwezenlijking van het nagestreefde legitieme doel;
* Het gebruik van ras of nationaliteit als selectiecriterium binnen een risicoprofiel moet daarnaast noodzakelijk zijn om het gewenste doel tebereiken.
* Selectiebeslissingen moeten te allen tijde uitlegbaar zijn.
  
## Mogelijke hulpmiddelen en methoden
* [Fairness Handbook](https://amsterdamintelligence.com/resources/the-fairness-handbook)
