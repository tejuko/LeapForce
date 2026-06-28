# CMS-velden voor CTA-sectie

## Sectie

### Eyebrow label
- Verplicht: Nee
- Default waarde: "Label"
- Tooltip: Korte tekst boven de titel, bijvoorbeeld een categorie of introductie.
- Beperkingen: Maximaal 30 tekens.

### Hoofdtitel
- Verplicht: Ja
- Default waarde: "Mandatory title about the call-to-action here"
- Tooltip: De hoofdtekst van de sectie.
- Beperkingen: Maximaal 80 tekens.

### Cursief/GT Alpina gedeelte van de titel
- Verplicht: Nee
- Default waarde: "call-to-action"
- Tooltip: Woord of woorden die in een afwijkend lettertype worden weergegeven.
- Beperkingen: Maximaal 30 tekens.

### Introductietekst
- Verplicht: Nee
- Default waarde: "Optional body copy goes here."
- Tooltip: Korte ondersteunende tekst onder de titel.
- Beperkingen: Maximaal 150 tekens.

### Button tekst
- Verplicht: Nee
- Default waarde: "Optional button"
- Tooltip: Tekst van de knop onder de introductie.
- Beperkingen: Maximaal 30 tekens.

### Button link
- Verplicht: Nee
- Default waarde: "#"
- Tooltip: Selecteer de pagina waar de knop naartoe moet linken.
- Beperkingen: Alleen interne of externe URL's.


## CTA-kaarten (repeater field)

De marketeer kan meerdere kaarten toevoegen, verwijderen of herschikken.

### Afbeelding
- Verplicht: Ja
- Default waarde: Standaard placeholder-afbeelding
- Tooltip: Upload een afbeelding voor de kaart.
- Beperkingen: Aanbevolen verhouding 335:252.

### Titel
- Verplicht: Ja
- Default waarde: "Title"
- Tooltip: Titel die op de afbeelding wordt weergegeven.
- Beperkingen: Maximaal 40 tekens.

### Beschrijving
- Verplicht: Nee
- Default waarde: "Supporting text about the call-to-action goes here."
- Tooltip: Korte ondersteunende tekst onder de titel.
- Beperkingen: Maximaal 100 tekens.

### Link
- Verplicht: Ja
- Default waarde: "#"
- Tooltip: Selecteer de pagina waar deze kaart naartoe moet linken.
- Beperkingen: Alleen interne of externe URL's.

### Alt-tekst afbeelding
- Verplicht: Ja
- Default waarde: ""
- Tooltip: Beschrijf de afbeelding voor toegankelijkheid en SEO.
- Beperkingen: Maximaal 125 tekens.

# Onderbouwing keuzes CMS-velden

Bij het bepalen van de CMS-velden heb ik gekeken naar welke onderdelen een marketeer waarschijnlijk regelmatig wil aanpassen zonder tussenkomst van een developer.

## Repeater voor de CTA-kaarten
Ik heb gekozen voor een repeater field voor de kaarten, zodat marketeers eenvoudig kaarten kunnen toevoegen, verwijderen en de volgorde kunnen aanpassen. Hierdoor is de sectie flexibel en hoeft de code niet aangepast te worden wanneer het aantal kaarten verandert.

## Verplichte en optionele velden
Essentiële content, zoals de hoofdtitel van de sectie, de afbeelding van een kaart en de link van een kaart, zijn verplicht gemaakt. Hierdoor wordt voorkomen dat er onvolledige of niet-werkende content op de website verschijnt.

Ondersteunende teksten, zoals de introductietekst en beschrijvingen bij kaarten, zijn optioneel. De sectie blijft daardoor bruikbaar wanneer een marketeer minder tekst wil tonen.

## Default waardes
Ik heb default waardes toegevoegd zodat de sectie direct zichtbaar en bruikbaar is wanneer deze aan een pagina wordt toegevoegd. Dit helpt marketeers om sneller content te plaatsen en maakt duidelijk welk type content in elk veld verwacht wordt.

## Tooltips en helpteksten
Bij ieder veld is een korte uitleg toegevoegd. Dit vermindert de kans op fouten en maakt de module gebruiksvriendelijk voor mensen zonder technische kennis.

## Inputbeperkingen
Ik heb maximale aantallen tekens voorgesteld voor titels en beschrijvingen. Hierdoor blijft de layout intact op verschillende schermgroottes en wordt voorkomen dat teksten buiten de beschikbare ruimte vallen.

Voor afbeeldingen is een aanbevolen beeldverhouding van 335:252 opgenomen, zodat de kaarten consistent blijven met het ontwerp uit Figma.

## Toegankelijkheid
Voor afbeeldingen heb ik een verplicht alt-tekstveld toegevoegd. Dit verbetert de toegankelijkheid voor schermlezers en draagt bij aan SEO.