---
title: Non-discriminatie
---

!!! info "Disclaimer"

    Het Algoritmekader is nog volop in ontwikkeling. Op deze plek willen we vooral aan de slag gaan op een open en transparante wijze. Het is dus niet definitief. Dat betekent dat er dingen opstaan die niet af zijn en soms zelfs fout. Mocht er iets niet kloppen, laat het ons weten via [GitHub](https://github.com/MinBZK/Algoritmekader).

## Wat en waarom?
Wanneer algoritmes ingezet worden om publieke taken uit te voeren, moeten we rekening houden met bias en eventuele discriminerende effecten daarvan. 
In dit bouwblok van het algoritmekader werken we uit wat bias is, hoe bias kan ontstaan, hoe we dit kunnen signaleren en welke maatregelen er genomen kunnen worden om dit te voorkomen.

*Bias* is een Engelse term die in het Nederlands wordt vertaald als vooringenomenheid, vooroordeel of neiging. 
Omdat niet één van die termen helemaal de lading van het begrip *bias* dekt, maken we in het Algoritmekader wel gebruik van de term *bias*. 
De term *bias* heeft verschillende betekenissen afhankelijk van de context waarin het gebruikt wordt en de disciplines die daarbij betrokken zijn. 
Vaak wordt er naar bias gekeken als een technisch concept, maar het omvat daarnaast ook menselijke en systemische aspecten. 
Om beter de verschillende betekennissen van het begrip *bias* te begrijpen, maken we onderscheid in drie verschillende aspecten van bias, zoals die door [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) zijn gedefinieerd: systemische bias, statistische bias en menselijke bias.

### systemische bias
Deze vorm van bias is een gevolg van bepaalde processen of systemen die gebruikt worden op zo'n wijze dat bepaalde groepen bevoordeeld worden en andere groepen benadeeld worden. 
Dit is vaak geen bewuste vorm van vooringenomenheid, maar ontstaat doordat de meerderheid bestaande regels of normen volgt. 
Systemische bias kan ook institutionele of historische worden genoemd. 

### statistische bias
Statistische bias wordt gedefinieerd als een consistente numerieke afwijking van een schatting ten opzichte van de werkelijke onderliggende waarde. 


### menselijke bias 



### Gebruikte definities
| Term of begrip          | Definitie                                                                                                                                                                                                                                                                                                            | Bron                                                                                                                                                                                      |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| (algoritmische) bias    | systematisch verschil in behandeling van bepaalde objecten, mensen of groepen in vergelijking met andere.                                                                                                                                                                                                            | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                       |
| directe discriminatie   | de ongelijke behandeling van een persoon of groep personen ten opzichte van andere personen in een vergelijkbare situatie, op grond van een beschermd persoonskenmerk (discriminatiegrond).                                                                                                                          | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |
| indirecte discriminatie | wanneer een ogenschijnlijk neutrale bepaling, maatstaf of handelwijze personen met een bepaald beschermd persoonskenmerk (discriminatiegrond) in vergelijking met andere personen in het bijzonder benadeelt, tenzij hiervoor een objectieve rechtvaardiging bestaat.                                                | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |
| direct onderscheid      | indien een persoon op een andere wijze wordt behandeld dan een ander in een vergelijkbare situatie wordt, is of zou worden behandeld, op grond van godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht, nationaliteit, hetero- of homoseksuele gerichtheid of burgerlijke staat                       | [Algemene wet gelijke behandeling](https://wetten.overheid.nl/BWBR0006502/2020-01-01)                                                                                                     |
| indirect onderscheid    | indien een ogenschijnlijk neutrale bepaling, maatstaf of handelwijze personen met een bepaalde godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht, nationaliteit, hetero- of homoseksuele gerichtheid of burgerlijke staat in vergelijking met andere personen bijzonder treft.                      | [Algemene wet gelijke behandeling](https://wetten.overheid.nl/BWBR0006502/2020-01-01)                                                                                                     |
| algoritmische fairness  | het vakgebied dat bestudeert hoe algoritmische systemen zich moeten gedragen om mensen eerlijk te behandelen, dat wil zeggen zonder discriminatie op grond van beschermde gevoelige kenmerken zoals leeftijd, geslacht, handicap, etnische of raciale afkomst, religie of geloofsovertuiging, of seksuele geaardheid | [The fairness handbook](https://openresearch.amsterdam/en/media/inline/2022/7/14/fairness_handbook.pdf)                                                                                   |
| ground truth            | waarde van de doelvariabele voor een bepaald item van gelabelde invoergegevens. [^2]                                                                                                                                                                                                                                 | [NEN-EN-ISO/IEC 22989:2023 en](https://www.nen.nl/nen-en-iso-iec-22989-2023-en-312642) [^1]                                                                                               |
| etnisch profileren      | Het gebruik door overheidsinstanties van selectiecriteria als ras, huidskleur, taal, religie, nationaliteit of nationale of etnische afkomst bij de uitoefening van toezichts-, handhavings- en opsporingsbevoegdheden, zonder dat daarvoor een objectieve en redelijke rechtvaardiging bestaat.                     | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |
| discriminatiegrond      | Beschermde persoonskenmerken op basis waarvan het maken van onderscheid tussen personen verboden is. Bijvoorbeeld: ras, nationaliteit, religie, geslacht, seksuele gerichtheid, handicap of chronische ziekte                                                                                                        | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |
| risicoprofiel           | Een verzameling van één of meer selectiecriteria op basis waarvan een bepaald risico op normovertreding wordt ingeschat en een selectiebeslissing wordt gemaakt.                                                                                                                                                     | [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce) |
| groep                   | deelverzameling van objecten in een domein die zijn gekoppeld omdat ze gemeenschappelijke kenmerken hebben.                                                                                                                                                                                                          | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                       |

[^1]: Hoewel het gebruik van de NEN-ISO-normen in het Algoritmekader auteursrechtelijk is beschermd, heeft het Nederlands Normalisatie Instituut (NEN) voor het gebruik in het Algoritmekader toestemming verleend. Zie [nen.nl](https://www.nen.nl/) voor meer informatie over NEN en het gebruik van hun producten.
[^2]: De term ground truth impliceert niet dat de gelabelde invoergegevens consistent overeenkomen met de werkelijke waarde van de doelvariabelen.

Omdat bias op verschillende manieren kan ontstaan, zijn er allerlei verschillende vormen van bias, die hieronder gedefinieerd worden. 

| Begrip                     | Definitie                                                                                                                                                                                                                                                                                                                                                                                                          | Bron                                                                                                                                                                                              |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| automatiseringsbias        | de neiging van mensen om de voorkeur te geven aan suggesties van geautomatiseerde besluitvormingssystemen en om tegenstrijdige informatie te negeren die zonder automatisering is verkregen, zelfs als deze correct is                                                                                                                                                                                             | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                               |
| menselijke cognitieve bias | bias die optreedt wanneer mensen informatie verwerken en interpreteren.                                                                                                                                                                                                                                                                                                                                            | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                               |
| bevestigingsbias           | soort menselijke cognitieve bias die de voorkeur geeft aan voorspellingen van AI-systemen die reeds bestaande overtuigingen of hypotheses bevestigen                                                                                                                                                                                                                                                               | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                               |
| data bias                  | dataeigenschappen die, als ze niet worden aangepakt, leiden tot AI-systemen die beter of slechter presteren voor verschillende groepen                                                                                                                                                                                                                                                                             | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                               |
| statistische bias          | soort consistente numerieke afwijking in een schatting ten opzichte van de werkelijke onderliggende waarde, inherent aan de meeste schattingen                                                                                                                                                                                                                                                                     | [ISO/IEC TR 24027:2021 en](https://www.nen.nl/iso-iec-tr-24027-2021-en-289193) [^1]                                                                                                               |
| historische bias           | Verwijzend naar de langdurige vooroordelen die in de loop der tijd in de samenleving zijn gecodeerd. Verwant aan, maar verschillend van, vooroordelen in historische beschrijving, of de interpretatie, analyse en verklaring van de geschiedenis. Een veel voorkomend voorbeeld van historische vooringenomenheid is de neiging om de wereld te bekijken vanuit een Westers of Europees perspectief               | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| activiteitenbias           | Een soort selectievooroordeel dat optreedt wanneer systemen/platforms hun trainingsgegevens krijgen van de meest actieve gebruikers, in plaats van minder actieve (of inactieve) gebruikers.                                                                                                                                                                                                                       | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| versterkingsbias           | Ontstaat wanneer de verdeling over voorspellingsoutputs scheef is in vergelijking met de prior-verdeling van het voorspellingsdoel.                                                                                                                                                                                                                                                                                | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| verankeringsbias           | Een cognitieve bias, de invloed van een bepaald referentiepunt of anker op de beslissingen van mensen. Vaak vollediger aangeduid als anchoring-and-adjustment, of anchoring-and-adjusting: nadat een anker is vastgesteld, passen mensen zich onvoldoende aan vanuit dat ankerpunt om tot een definitief antwoord te komen. Beslissers zijn bevooroordeeld ten opzichte van een aanvankelijk gepresenteerde waarde | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| cognitieve bias            | Een brede term die in het algemeen verwijst naar een systematisch patroon van afwijking van rationele oordeels- en besluitvorming. In vele decennia van onderzoek naar oordeelsvorming en besluitvorming is een grote verscheidenheid aan cognitieve vertekeningen geïdentificeerd, waarvan sommige adaptieve mentale snelkoppelingen zijn die bekend staan als heuristieken.                                      | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| gedragsbias                | systematische verstoringen in gebruikersgedrag tussen platforms of contexten, of tussen gebruikers die zijn vertegenwoordigd in verschillende datasets                                                                                                                                                                                                                                                             | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| implementatie bias         | Ontstaat wanneer systemen worden gebruikt als beslissingshulp voor mensen, omdat de menselijke tussenpersoon kan handelen op voorspellingen op manieren die meestal niet zijn gemodelleerd in het systeem. Het zijn echter nog steeds individuen die het gebruikte systeem gebruiken                                                                                                                          | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| evaluatie bias             | Ontstaat wanneer de test- of externe benchmarkpopulaties niet in gelijke mate de verschillende delen van de gebruikerspopulatie vertegenwoordigen of door het gebruik van prestatiemaatstaven die niet geschikt zijn voor de manier waarop het model zal worden gebruikt                                                                                                                                           | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| meetbias                   | Ontstaat wanneer kenmerken en labels benaderingen zijn voor gewenste grootheden, waarbij mogelijk belangrijke factoren worden weggelaten of groeps- of ingangsafhankelijke ruis wordt geïntroduceerd die leidt tot differentiële prestaties.                                                                                                                                                                       | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |
| representatie bias         | Ontstaat doordat subgroepen niet willekeurig worden bemonsterd, waardoor trends die voor één populatie worden geschat, niet generaliseerbaar zijn naar gegevens van een nieuwe populatie                                                                                                                                                                                                                           | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) |


### Omstreden variabelen

#### Bijzondere persoonsgegevens
De [AVG](https://www.autoriteitpersoonsgegevens.nl/themas/basis-avg/privacy-en-persoonsgegevens/wat-zijn-persoonsgegevens) ziet deze persoonsgegevens als bijzondere persoonsgegevens:

- persoonsgegevens waaruit iemands ras of etnische afkomst blijkt;
- persoonsgegevens waaruit iemands politieke opvattingen blijken;
- persoonsgegevens waaruit iemands religieuze of levensbeschouwelijke overtuigingen blijken;
- persoonsgegevens waaruit het lidmaatschap van een vakbond blijkt;
- gegevens over iemands gezondheid;
- gegevens over iemands seksueel gedrag of seksuele gerichtheid;
- genetische gegevens;
- biometrische gegevens (bedoeld voor de unieke identificatie van een persoon).

#### Gevoelige persoonsgegevens
De [AVG](https://www.autoriteitpersoonsgegevens.nl/themas/basis-avg/privacy-en-persoonsgegevens/wat-zijn-persoonsgegevens) beschouwt de volgende gegevens als privacygevoelig:

- gegevens over elektronische communicatie;
- locatiegegevens;
- financiële gegevens (zoals inkomen of koopgedrag);
- het burgerservicenummer (BSN).

#### Beschermde persoonsgegevens

[The fairness handbook](https://openresearch.amsterdam/en/media/inline/2022/7/14/fairness_handbook.pdf)  definieert de volgende lijst van beschermde persoonsgegevens (protected attributes):

- Migration Background
- Nationality
- Race
- Ethnicity
- Country of Birth
- Gender
- Sex
- Sexual Orientation
- Religion
- Age
- Pregnancy
- Civil Status
- Socioeconomic Class
- Income
- Skin Colour
- Language
- Political Views
- Health
- Disability status
- Biometrics

## Bias en non-discriminatie ten opzichte van de levenscyclus

| **Fase levenscyclus**                                                                                 | **Relevant ja/nee** | **Toelichting** |
|-------------------------------------------------------------------------------------------------------|:-------------------:|-----------------|
| [Probleemanalyse](../../levenscyclus/probleemanalyse.md)                                              |                     |                 |
| [Ontwerp](../../levenscyclus/ontwerp.md)                                                              |                     |                 |
| [Data verkennen en data preparatie](../../levenscyclus/data%20verkenning%20en%20data%20preparatie.md) |                     |                 |
| [Ontwikkelen](../../levenscyclus/ontwikkelen.md)                                                      |                     |                 |
| [Validatie](../../levenscyclus/validatie.md)                                                          |                     |                 |
| [Implementatie](../../levenscyclus/implementatie.md)                                                  |                     |                 |
| [Monitoren](../../levenscyclus/monitoren.md)                                                          |                     |                 |
| [Archiveren](../../levenscyclus/archiveren.md)                                                        |                     |

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
    | Verbod op ongelijke behandeling in gelijke omstandigheden. Discriminatie wegens godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht of op welke grond dan ook, is niet toegestaan    | Korte uitleg over norm 1                |          | IKA1.0
 
=== "Hoog risico"

    | **Norm**                          | **Uitleg**                               | **Bron** |
    |-----------------------------------|------------------------------------------|----------|
    | Verbod op ongelijke behandeling in gelijke omstandigheden. Discriminatie wegens godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht of op welke grond dan ook, is niet toegestaan    | Korte uitleg over norm 1                |          | IKA1.0



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
* [Handreiking non-discriminatie-by-design](https://www.rijksoverheid.nl/documenten/rapporten/2021/06/10/handreiking-non-discriminatie-by-design)
* [College voor de rechten van de mens, Discriminatie door risicoprofielen - een mensenrechtelijk toetsingskader](https://publicaties.mensenrechten.nl/publicatie/61a734e65d726f72c45f9dce)
