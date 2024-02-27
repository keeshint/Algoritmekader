---
title: Non-discriminatie
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
 
De [ISO standaard 22989]() schrijft het volgende over **bias** en **fairness**:

In AI, the term bias refers to the idea that different cases call for different treatment. In this sense, bias is that which allows machine learning systems to judge that one situation is different from another and to behave differently accordingly. 
As such, bias is fundamental to the machine learning process and to adapting behaviour to the particular situation at hand.
In social context, however, the term bias often refers to the notion that certain differences in treatment are unfair. To avoid confusion, in the context of AI, instead of bias, the term unfairness is used to refer to unjustified differential treatment that preferentially benefits certain groups more than others. Unfair AI system behaviour can lead to disrespect of established facts, beliefs and norms, leading to favouritism or discrimination.
While certain bias is essential for proper AI system operation, unwanted bias can be introduced into an AI system unintentionally and can lead to unfair system results. Sources of unwanted bias in AI systems are interrelated and include human cognitive bias, data bias and bias introduced by engineering decisions. Bias in training data is major source of bias in AI systems. Human cognitive biases can affect decisions about data collection and processing, system design, model training and other development decisions.

> Hoe vertalen we bias? Willen we dit vertalen? Vooringenomenheid, vertekening? 

Vervolgens specificeren we verschillende vormen van bias:

| Definitie                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Bron                                                                                                                                                                                              | Opmerking                                                                                                                                                                                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **automation bias:** propensity for humans to favour suggestions from automated decision-making systems and to ignore contradictory information made without automation, even if it is correct                                                                                                                                                                                                                                                                                                                                                                                                                        | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en)                                                                                                             | NL vertaling door DeepL: "automatiseringsvooringenomenheid: de neiging van mensen om de voorkeur te geven aan suggesties van geautomatiseerde besluitvormingssystemen en om tegenstrijdige informatie te negeren die zonder automatisering is verkregen, zelfs als deze correct is"           |
| **human cognitive bias:** bias that occurs when humans are processing and interpreting information. *Note 1 to entry: human cognitive bias influences judgement and decision-making.*                                                                                                                                                                                                                                                                                                                                                                                                                                 | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en)                                                                                                             | NL vertaling door DeepL: "menselijke cognitieve vooringenomenheid: vooringenomenheid die optreedt wanneer mensen informatie verwerken en interpreteren. *Noot 1 bij item: menselijke cognitieve vooringenomenheid beïnvloedt oordeelsvorming en besluitvorming.*"                             |
| **confirmation bias:** type of human cognitive bias that favours predictions of AI systems that confirm pre-existing beliefs or hypotheses                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en)                                                                                                             | NL vertaling door DeepL: "confirmation bias: soort menselijke cognitieve bias die de voorkeur geeft aan voorspellingen van AI-systemen die reeds bestaande overtuigingen of hypotheses bevestigen"                                                                                            |
| **conformation bias:** also called confirmatory bias, a cognitive bias where people tend to prefer information that aligns with, or confirms, their existing beliefs. People can exhibit confirmation bias in the search for, interpretation of, and recall of information. In the famous Wason selection task experiments, participants repeatedly showed a preference for confirmation over falsification. They were tasked with identifying an underlying rule that applied to number triples they were shown, and they overwhelmingly tested triples that confirmed rather than falsified their hypothesized rule | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "historische vertekening: Dit type vertekening wordt veroorzaakt door gegevens die de menselijke vooroordelen, vooroordelen en andere effecten van maatschappelijke of historische ongelijkheden weerspiegelen, wat leidt tot nadelige representatie en toewijzing." |
| **data bias:** data properties that if unaddressed lead to AI systems that perform better or worse for different groups                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en)                                                                                                             | NL vertaling door DeepL: "gegevensvooringenomenheid: gegevenseigenschappen die, als ze niet worden aangepakt, leiden tot AI-systemen die beter of slechter presteren voor verschillende groepen"                                                                                              |
| **statistical bias:** type of consistent numerical offset in an estimate relative to the true underlying value, inherent to most estimates                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [ISO standaard 24027](https://www.iso.org/obp/ui#iso:std:iso-iec:tr:24027:ed-1:v1:en)                                                                                                             | NL vertaling door DeepL: "statistische vertekening: soort consistente numerieke afwijking in een schatting ten opzichte van de werkelijke onderliggende waarde, inherent aan de meeste schattingen"                                                                                           |
| **historical bias:** This type of bias is caused by data that reflects the human biases, prejudices and other effects of societal or historical inequities, leading to representation and allocation harm                                                                                                                                                                                                                                                                                                                                                                                                             | [The fairness handbook](https://openresearch.amsterdam/en/media/inline/2022/7/14/fairness_handbook.pdf)                                                                                           | NL vertaling door DeepL: "historische vertekening: Dit type vertekening wordt veroorzaakt door gegevens die de menselijke vooroordelen, vooroordelen en andere effecten van maatschappelijke of historische ongelijkheden weerspiegelen, wat leidt tot nadelige representatie en toewijzing." |
| **historical bias:** referring to the long-standing biases encoded in society over time. Related to, but distinct from, biases in historical description, or the interpretation, analysis, and explanation of history. A common example of historical bias is the tendency to view the larger world from a Western or European view.                                                                                                                                                                                                                                                                                  | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "historische vertekening: Verwijzend naar de langdurige vooroordelen die in de loop der tijd in de samenleving zijn gecodeerd. Verwant aan, maar verschillend van, vooroordelen in historische beschrijving, of de interpretatie, analyse en verklaring van de geschiedenis. Een veel voorkomend voorbeeld van historische vooringenomenheid is de neiging om de wereld te bekijken vanuit een Westers of Europees perspectief." |
| **activity bias:** A type of selection bias that occurs when systems/platforms get their training data from their most active users, rather than those less active (or inactive)                                                                                                                                                                                                                                                                                                                                                                                                                                      | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "activiteitsvertekening: Een soort selectievooroordeel dat optreedt wanneer systemen/platforms hun trainingsgegevens krijgen van de meest actieve gebruikers, in plaats van minder actieve (of inactieve) gebruikers.." |
| **amplification bias:** Arises when the distribution over prediction outputs is skewed in comparison to the prior distribution of the prediction target                                                                                                                                                                                                                                                                                                                                                                                                                                                               | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "amplificatiebias: Ontstaat wanneer de verdeling over voorspellingsoutputs scheef is in vergelijking met de prior-verdeling van het voorspellingsdoel." |
| **anchoring bias:** A cognitive bias, the influence of a particular reference point or anchor on people’s decisions. Often more fully referred to as anchoring-and-adjustment, or anchoring-and-adjusting: after an anchor is set, people adjust insufficiently from that anchor point to arrive at a final answer. Decision makers are biased towards an initially presented value                                                                                                                                                                                                                                   | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "anchoring bias: Een cognitieve bias, de invloed van een bepaald referentiepunt of anker op de beslissingen van mensen. Vaak vollediger aangeduid als anchoring-and-adjustment, of anchoring-and-adjusting: nadat een anker is vastgesteld, passen mensen zich onvoldoende aan vanuit dat ankerpunt om tot een definitief antwoord te komen. Beslissers zijn bevooroordeeld ten opzichte van een aanvankelijk gepresenteerde waarde" |
| **cognitive bias:** A broad term referring generally to a systematic pattern of deviation from rational judgement and decision-making. A large variety of cognitive biases have been identified over many decades of research in judgement and decision-making, some of which are adaptive mental shortcuts known as heuristics.                                                                                                                                                                                                                                                                                      | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "cognitieve vooringenomenheid: Een brede term die in het algemeen verwijst naar een systematisch patroon van afwijking van rationele oordeels- en besluitvorming. In vele decennia van onderzoek naar oordeelsvorming en besluitvorming is een grote verscheidenheid aan cognitieve vertekeningen geïdentificeerd, waarvan sommige adaptieve mentale snelkoppelingen zijn die bekend staan als heuristieken." |
| **behavioral bias:** Systematic distortions in user behavior across platforms or contexts, or across users represented in different datasets                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "gedragsvooringenomenheid: systematische verstoringen in gebruikersgedrag tussen platforms of contexten, of tussen gebruikers die zijn vertegenwoordigd in verschillende datasets" |
| **deployment bias:** Arises when systems are used as decision aids for humans, since the human intermediary may act on predictions in ways that are typically not modeled in the system [90]. However, it is still individuals using the deployed system.                                                                                                                                                                                                                                                                                                                                                             | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "inzetbias: Ontstaat wanneer systemen worden gebruikt als beslissingshulp voor mensen, omdat de menselijke tussenpersoon kan handelen op voorspellingen op manieren die meestal niet zijn gemodelleerd in het systeem [90]. Het zijn echter nog steeds individuen die het gebruikte systeem gebruiken." |
| **evaluation bias:** Arises when the testing or external benchmark populations do not equally represent the various parts of the user population or from the use of performance metrics that are not appropriate for the way in which the model will be used                                                                                                                                                                                                                                                                                                                                                          | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "evaluatievooringenomenheid: Ontstaat wanneer de test- of externe benchmarkpopulaties niet in gelijke mate de verschillende delen van de gebruikerspopulatie vertegenwoordigen of door het gebruik van prestatiemaatstaven die niet geschikt zijn voor de manier waarop het model zal worden gebruikt." |
| **measurement bias:** Arises when features and labels are proxies for desired quantities, potentially leaving out important factors or introducing group or input-dependent noise that leads to differential performance                                                                                                                                                                                                                                                                                                                                                                                              | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "meetvertekening: Ontstaat wanneer kenmerken en labels benaderingen zijn voor gewenste grootheden, waarbij mogelijk belangrijke factoren worden weggelaten of groeps- of ingangsafhankelijke ruis wordt geïntroduceerd die leidt tot differentiële prestaties." |
| **representation bias:** Arises due to non-random sampling of subgroups, causing trends estimated for one population to not be generalizable to data collected from a new population                                                                                                                                                                                                                                                                                                                                                                                                                                  | [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence) | NL vertaling door DeepL: "vertekening door representatie: Ontstaat doordat subgroepen niet willekeurig worden bemonsterd, waardoor trends die voor één populatie worden geschat, niet generaliseerbaar zijn naar gegevens van een nieuwe populatie." |

>  Kunnen we dit koppelen aan de levenscyclus? 

> [NIST, Towards a Standard for identifying and managing bias in artificial intelligence](https://www.nist.gov/publications/towards-standard-identifying-and-managing-bias-artificial-intelligence)  en andere bronnen definieren nog meer vormen van bias. Ik heb een snelle selectie gemaakt van de vormen die mij het meest belangrijk leken. Dit kunnen we nog aanvullen. 

#### Vooringenomenheid

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

### Fairness

| Definitie                                                                                                                                                                                                                                                                                      | Bron                                                                                                                                                                                    | Opmerking |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| **unfairness**: unjustified differential treatment that preferentially benefits certain groups more than others | [ISO standaard 22989](https://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_IEC_22989_2022_ed.1_id.74296_Publication_PDF_(en).zip)                                                   | NL vertaling door deepL: "ongerechtvaardigde differentiële behandeling die bepaalde groepen meer bevoordeelt dan andere"           |
| **algorithmic fairness**:  the field which studies how algorithmic systems should behave to treat people fairly, that is, without discrimination on the grounds of protected sensitive characteristics such as age, gender, disability, ethnic or racial origin, religion or belief, or sexual orientation  | [The fairness handbook](https://openresearch.amsterdam/en/media/inline/2022/7/14/fairness_handbook.pdf)                               | NL vertaling door deepL: "het gebied dat bestudeert hoe algoritmische systemen zich moeten gedragen om mensen eerlijk te behandelen, dat wil zeggen zonder discriminatie op grond van beschermde gevoelige kenmerken zoals leeftijd, geslacht, handicap, etnische of raciale afkomst, religie of geloofsovertuiging, of seksuele geaardheid"           |

> Nederlandse vertaling?

> Wat is het verschil met eerlijkheid, rechtvaardigheid, justice?

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

### Gouden standaard / ground truth

| Definitie                                                                                                                                                                                                                                 | Bron                                                                                                                                       | Opmerking                                                                                                                                                                                                                                                                  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| value of the target variable for a particular item of labelled input data. *Note 1 to entry: The term ground truth does not imply that the labelled input data consistently corresponds to the real-world value of the target variables.* | [ISO standaard 22989](https://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_IEC_22989_2022_ed.1_id.74296_Publication_PDF_(en).zip) | NL vertaling door DeepL: "waarde van de doelvariabele voor een bepaald item van gelabelde invoergegevens. Noot 1 bij invoer: De term ground truth impliceert niet dat de gelabelde invoergegevens consistent overeenkomen met de werkelijke waarde van de doelvariabelen." |
|                                                                                                                                                                                                                                           |                                                                                                                                            |                                                                                                                                                                                                                                                                            |

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

| **Fase levenscyclus**                                                                                 | **Relevant ja/nee** | **Toelichting**                                                                                                                                                                                                                                          |
|-------------------------------------------------------------------------------------------------------|:-------------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Probleemanalyse](../../levenscyclus/probleemanalyse.md)                                              |                     |                                                                                                                                                                                                                                                          |
| [Ontwerp](../../levenscyclus/ontwerp.md)                                                              |                     |                                                                                                                                                                                                                                                          |
| [Data verkennen en data preparatie](../../levenscyclus/data%20verkenning%20en%20data%20preparatie.md) |                     | De vraag is of dit voldoende plek is voor een toelichting. Hoe veel tekst willen we hier precies kwijt? Je kan hier best een tijdje doortypen, maar deze vorm van weergeven is misschien niet heel geschikt als je hier heel veel meer tekst kwijt wilt. |
| [Ontwikkelen](../../levenscyclus/ontwikkelen.md)                                                      |                     |                                                                                                                                                                                                                                                          |
| [Validatie](../../levenscyclus/validatie.md)                                                          |                     |                                                                                                                                                                                                                                                          |
| [Implementatie](../../levenscyclus/implementatie.md)                                                  |                     |                                                                                                                                                                                                                                                          |
| [Monitoren](../../levenscyclus/monitoren.md)                                                          |                     |                                                                                                                                                                                                                                                          |
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
