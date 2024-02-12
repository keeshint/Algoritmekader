---
title: Non discriminatie

---

!!! info "Disclaimer"

    Het Algoritmekader is nog volop in ontwikkeling. Op deze plek willen we vooral aan de slag gaan op een open en transparante wijze. Het is dus niet definitief. Dat betekent dat er dingen opstaan die niet af zijn en soms zelfs fout. Mocht er iets niet kloppen, laat het ons weten via [GitHub](https://github.com/MinBZK/Algoritmekader).


## Norm
**Verbod op ongelijke behandeling in gelijke omstandigheden. Discriminatie wegens godsdienst, levensovertuiging, politieke gezindheid, ras, geslacht of op welke grond dan ook, is niet toegestaan.**

## Risico
- Toepassing van het model leidt tot discriminatie op basis van beschermde persoonskenmerken. 

- Andere data dan beschermde persoonskenmerken leiden tot discriminatie in de uitkomsten. 

- Het gebruik van proxy variabelen leidt tot indirecte discriminatatie.

- Bias in het algoritme leidt tot discriminatie

## Bronnen

#### Wet- en regelgeving
- Grondwet Art. 1
- EVRM Art. 1 en 14, jo. 21 HvEU jo. 1 GW
- Algemene wet gelijke behandeling, Protocol 12 2.2, Artikel 1 lid 1 sub c 
- Aritkel 9 AVG

#### Toetsingskaders
EC/AI HLEG April 2019 - hoofdstuk II. 1.1, 1.5
Toetsingskader Algemene Rekenkamer
Toetsingskader Auditdienst Rijk
Toetsingskader College voor de Rechten van de Mens

## Toelichting
- Er is sprake van een objectieve rechtvaardiging als sprake is van een legitiem doel en het middel dat wordt gebruikt om het doel te bereiken is passend, noodzakelijk en evenredig. Om te bepalen of een algoritme verboden onderscheid maakt, moet worden bekeken of door het algoritme sprake is van een ongelijke behandeling van een persoon of groep personen in verhouding tot anderen in een vergelijkbare situatie.

Verdacht onderscheid op basis van onder andere:

- Burgerlijke staat
- Handicap/chronische ziekte
- Geslacht (incl. genderidentiteit)
- Godsdienst
- Leeftijd
- Levensovertuiging
- Nationaliteit
- Politieke gezindheid
- Ras/etniciteit
- Seksuele gerichtheid

- Onvoldoende representativiteit in de trainingsdata kan leiden tot ongelijke uitkomsten
Onvoldoende representativiteit in de trainingsdata kan leiden tot ongelijke uitkomsten. Kan bij voorspellende algoritmes ook leiden tot ongewenste feedbackloops. (Gebruik van data van bijvoorbeeld vroegere surveillances en criminaliteitscijfers in nieuwe algoritmes kan leiden tot link aan wijken, personen met een immigratieachtergrond. Indien het geval, is dit niet representatief en neutraal)

- Ogenschijnlijk neutrale data die op het eerste gezicht geen enkele link hebben met afkomst of nationaliteit kunnen leiden tot indirect onderscheid op grond van ras of nationaliteit. Voorbeelden zijn postcode, hoogte van inkomen, hoogte van inkomensafhankelijke toeslagen, kinderopvang door een gastouderbureau met een ‘homogeen’ klantenbestand, een familielid in het buitenland, kenteken en laaggeletterdheid.
(ook black box opties zoal bias mitigation met adversarial networks zijn mogelijk)

- Van belang bij de gemeten bias die duidt op discriminatie is het kijken vanuit wetgeving én wenselijkheid.
- Eerst moet duidelijk worden wat eerlijk is voor het proces. Dan kunnen fairness metrics worden opgesteld om eerlijkheid te meten
- Documentatie van de aanpak van bias bevordert de controleerbaarheid.
- De keuze voor een gewenste prestatie per groep is een ethische afweging. 
- Bias in de trainingsdata kan leiden tot bias in het model. Regels in het model kan leiden tot bias. De beslissing van de eindgebruiker kan leiden tot bias. Bias in de inputdata kan doorwerken tot bias in de uitkomst.
- Een model kan gemiddeld goed presteren, maar kan voor bepaalde subgroepen die minder in de testset aanwezig waren verkeerde uitkomsten geven. Een ongebalanceerde dataset kan ervoor zorgen dat het model minder goed presteert voor sommige subgroepen in de data.
-  Tijdens de ontwikkeling van het model kunnen methoden om bias te corrigeren helpen om uiteindelijk aan de prestatiecriteria te voldoen. Testresultaten op de uitkomtstbias tijdens het ontwikkelen zijn ook wenselijk. Merk op dat voor het meten van uitkomst bias alleen de inputdata en uitkomst van het model nodig is. Uitkomstbias kan zonder gelabelde dataset gemeten worden.


## Maatregelen
- Stel vast of bij het doel, design of de uitkomst van het algoritme sprake is van mogelijk verdacht (direct of indirect) onderscheid. Maak bij de uitkomst ook gebruik van controlevariabelen (bijvoorbeeld nationaliteit/ras). Stel vervolgens vast of dit leidt tot benadeling. Bepaal of er goede redenen zijn voor het maken van onderscheid zoals een wettelijke uitzondering of een objectieve rechtvaardiging. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Zorg voor gelijke mate van vertegenwoordiging relevante groepen. Selecteer een afgebakende toepassing om het systeem te testen; zorg dat deze afgebakende toepassing representatief is voor het gehele domein waarop het AI-systeem later wordt ingezet. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Documenteer de mate van afhankelijkheid van historische data. Weeg af of de geconstateerde afhankelijkheid wenselijk is en of deze op discriminatie duidt. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Identificeer bij een onrechtmatigheid in de uitkomst van het algoritme ogenschijnlijk neutrale data (proxies). Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Beoordeel of de geconstateerde bias wenselijk is en of deze op discriminatie duidt. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Documenteer in de funtionele eisen de definitie van acceptabele bias. In de documentatie waarin deze eisen tot meetbare prestatiecriteria zijn uitgewerkt is te vinden welke fairness metrics hierbij horen. Maak de consequenties expliciet.
- Documenteer in de functionele eisen de methoden van voorkomen, detecteren en corrigeren van bias. Maak de consequenties expliciet.
- Documenteer in de functionele eisen de doelstelling voor en definitie van de verschillende groepen en gewenste prestatie van het model voor deze groepen. Maak de consequenties expliciet en bespreek dit in het ethisch gesprek.
- Documenteer de mate van bias in de (trainings)data, dataverzameling en het model. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Beoordeel tijdens de ontwikkeling van het model of een verschil bestaat tussen prestatie van het model voor verschillende subgroepen. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- Beoordeel of de uitkomstbias van de productiedata voor de verschillende subgroepen voldoet aan de productiecriteria. Doe dit ook met een testset gedurende het ontwikkelproces. Maak de consequentie expliciet en leg deze op het juiste niveau vast.
- De ultieme maatregel kan zijn het (tijdelijk) stopzetten van het algoritme.

### Probleemanalyse
- Kleven er aan de opgestelde doelstelling en/of parameters op grond waarvan onderscheid wordt gemaakt discriminatie-aspecten?
- Is de target variabele een goede maatstaaf voor het concept dat wordt voorspeld of is er sprake van measurement bias? In veel gevallen is het concept moeilijk meetbaar en wordt gebruik gemaakt van een proxy. In plaats van criminaliteit meten we arrestaties en in plaats van kwaliteit van werknemers meten we de evaluatiescores van hun manager. Het verschil tussen de target en de proxy is een vorm van measurement bias. Wanneer de bias verschillend is voor subgroepen, kan dit leiden tot een discriminatoir model.
- Leg vast wanneer het proces zal worden stopgezet en wat de exitstrategie is.

### Ontwerp

### Data Verkenning en Preparatie
- Controleer je data op mogelijke bias ten opzichte van de beschermde gronden.
- Verdeling van de doelvariabele in verschillende groepen. Ongelijkheid in de samenleving is vaak ook terug te zien in op zich neutraal verzamelde data.
- Relaties tussen paren of een klein aantal attributen (features): leidt dit tot proxies?
- Verdeling van attributen en representatie van relevante subpopulaties. Representatie bias ontstaat wanneer delen van de inputruimte zijn onder- of overgerepresenteerd.
- De aannames achter de data: meten we wel wat we willen meten?
- Zorg dat data zo neutraal en objectief mogelijk worden verzameld en dat dit zo transparant en controleerbaar mogelijk geschiedt. De wijze waarop data worden verzameld, hoe, door wie, waar en met gebruikmaking van welke technieken kunnen bepalend zijn voor de neutraliteit en betrouwbaarheid van de verkregen data.
- Leg dit proces nauwgezet vast en bewaar te allen tijde gegevens over hoe de dataset tot stand is gekomen, om zo de processen controleerbaar en herhaalbaar te maken. Doe dat ook voor de data die via derden zijn verkregen.
- Controleer op ontbrekende waarden, nauwkeurigheid en representativiteit en of de verdeling voor verschillende groepen gelijk is. Leg verschillen uit en overweeg mitigerende maatregelen. Overweeg om nieuwe gegevens te verzamelen of om het doel van het project te herzien: ga dan terug naar fase 1 (probleemdefinitie).
- Faciliteer een gesprek over de controle op ontbrekende waarden, nauwkeurigheid en representativiteit tussen verschillende betrokkenen (bijv. data scientists, AI experts, product owner, project leider, bevoegd gezag).
- Controleer bij de inclusie en exclusie van data welke gevolgen de dataselectie heeft voor de representatie, met name van categorieën die direct of indirect verwijzen naar de beschermde gronden zoals burgerlijke staat, geslacht, godsdienst/levensovertuiging, hetero- of homoseksuele gerichtheid, nationaliteit, politieke gezindheid, ras/etniciteit.
- (Zie verder nog Datavoorbereiding)

### Ontwikkelen
- Controleer hoe het model presteert t.a.v. categorieën die direct of indirect verwijzen naar iemands geslacht, ras, kleur, taal, godsdienst, politieke of andere mening, nationale of maatschappelijke afkomst of het behoren tot een nationale minderheid
- Overweeg het gebruik van unfairness mitigation technieken om te optimaliseren voor een
fairness metric
- Overweeg de vooraf gedefinieerde fairness-maatstaven bij het selecteren van een model
- Overweeg het gebruik van bias mitigatietechnieken.
- Pas indien nodig nabewerkingsmethoden toe om bias te beperken na training van het classificatiemodel. White-box-methoden passen het model aan; black-box-methoden passen de voorspellingen aan.
- 
### Validatie
- Controleer hoe het model presteert t.a.v. categorieën die direct of indirect verwijzen de beschermde gronden zoals burgerlijke staat, geslacht, godsdienst/levensovertuiging, hetero- of homoseksuele gerichtheid, nationaliteit, politieke gezindheid, ras/etniciteit.
- Als het model significant onderscheid maakt, direct of indirect, op basis van een van deze groepen, is daar een rechtvaardiging voor en zo ja welke? Leg dit voor aan een jurist.
- Wanneer het model regelmatig wordt geüpdatet op basis van nieuwe data, zorg dat ook deze nieuwe modellen grondig worden geëvalueerd.
- Plan voor het monitoren van veranderingen in de datadistributie, zoals concept drift en eenverschuiving in de demografie van data subjecten.

### Implementatie
- Zorg dat er een exitstrategie is.

### Monitoren
- Controleer hoe het systeem presteert t.a.v. categorieën die direct of indirect verwijzen naar de beschermde gronden zoals burgerlijke staat, geslacht, godsdienst/levensovertuiging, hetero- of homoseksuele gerichtheid, nationaliteit, politieke gezindheid, ras/etniciteit.
- Als het model significant onderscheid maakt op basis van een van deze groepen, is daar een rechtvaardiging voor, en zo ja, welke? Ga na of het systeem al dan niet tijdelijk moet worden stopgezet of dat naar een van de vorige fasen in het proces moet worden teruggegaan om aanpassingen te doen.

## Rollen

- __technische expert__ bron: handreiking non-discriminatie by design
- __projectleider__ bron: handreiking non-discriminatie by design
- __jurist__ bron: handreiking non-discriminatie by design
- __functionaris gegevensbescherming__ bron: handreiking non-discriminatie by design
- __relevante stakeholders__ bron: handreiking non-discriminatie by design
- __domein expert__ bron: handreiking non-discriminatie by design
- __data steward__ bron: handreiking non-discriminatie by design
- __data analist__ bron: handreiking non-discriminatie by design
- __beleid__ bron: evaluatie handreiking non-discriminatie by design door ADR

## Best practices
Het is aan te bevelen om hiervoor de handreiking non-discriminatie by design te gebruiken.

https://open.overheid.nl/documenten/ronl-3f9fa69c-acf4-444d-96e1-5c48df00eb3c/pdf

Indien risicoprofielen worden ingezet en bestaat een risico op discriminatie, dan kan de Beslisboom van het College van de Rechten van de Mens worden gebruikt.
 
https://publicaties.mensenrechten.nl/file/2aecbba3-e0ab-015f-5e51-93293b16ecca.pdf
