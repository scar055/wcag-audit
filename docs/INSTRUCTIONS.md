# WCAG Audit

Doe een WCAG audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

## Context

Deze deeltaak hoort bij Sprint 3 **All Human**. Dit is een deeltaak die je individueel uitvoert.

In de workshop S03W1-02-WCAG-audit wordt behandeld hoe je een WCAG audit kan uitvoeren.


## Doel van deze opdracht

Je leert hoe je een toegankelijkheidstest kan uitvoeren en je presenteert je bevindingen.


## Werkwijze

Fork deze deeltaak, zet je Wiki aan bij Repository Settings en documenteer je test in de Wiki.

Het is de verantwoordelijkheid van een frontender dat een website voor verschillende mensen, met verschillende apparaten, in verschillende situaties, _Toegankelijk_ is. Met goede code en een goed design kun je ervoor zorgen dat mensen met een (tijdelijke) beperking een website ook op een prettige manier kunnen bedienen.

Stel je voor dat de gebruiker van jouw website niet kan zien, of kleurenblind is, of een website bedient met alleen het toetsenbord, of spastisch is, of een arm in het gips heeft. Of ...

Een goede toegankelijke website voldoet aan de _[Web Content Accessibility Guidelines](https://www.w3.org/TR/WCAG22/)_ van het W3C. [The A11Y Project](https://www.a11yproject.com) is een goede plek om te lezen over toegankelijkheid, daar staat ook een [checklist](https://www.a11yproject.com/checklist/) waar een website aan moet voldoen, en waarmee je je eigen site kunt controleren. 

Voor het testen van toegankelijkheid kun je een website automatisch testen in de browser met bijvoorbeeld de tool _Lighthouse_ van Google. Voor deze opdracht ga je zo'n test uitvoeren en documenteer je wat je hebt getest in de Wiki van deze deeltaak.

1. Eerst ga je een [Lighthouse test](#1-lighthouse-test) doen van een bestaande website en documenteer je de belangrijkste bevindingen uit de test in je Wiki
2. Daarna ga je [met de hand](#2-handmatige-tests) dezelfde website verder testen en documenteer je de bevindingen van de tests.

### 1. Lighthouse test

Lighthouse is een geautomatiseerde test die je in een Chrome (of op Chromium gebaseerde) browser kan uitvoeren. In de Devtools kun je Lighthouse gebruiken. Je begint de toegankelijkheidstest met een Lighthouse test.

#### Aanpak

- Ga naar een website uit je eigen omgeving, bijvoorbeeld die van je eigen voetbalvereniging, yogaclub, muziekschool, bijbaantje, fitnessschool of het werk van je ouders.
- Open de Devtools en klik naar Lighthouse.
- Selecteer alleen _Accessibility_ en zorg dat _Clear storage_ aan staat en _Throttling_ op _default_. 
<img width="500" alt="image" src="https://user-images.githubusercontent.com/1391509/195625978-c079cbb8-35d0-4bf3-a381-7a74aa24ebb3.png">

- Run de test, maak een screenshot van de score en zet deze in de Wiki.
- Bekijk het Lighthouse rapport en documenteer de problemen en de goede uitkomsten van de test in de Wiki. 
- Schrijf bij elk onderdeel in je eigen woorden wat het betekent. Vraag om hulp als je niet begrijpt wat de verschillende problemen betekenen.
- Schrijf bij de problemen hoe je dit in code zou kunnen oplossen. Vraag om hulp als je het niet weet.

#### Bronnen Lighthouse test

 - [Test accessibility with Chrome DevTools @ YouTube](https://www.youtube.com/watch?v=b0Q5Zp_yKaU)
 - [Lighthouse documentation](https://developer.chrome.com/docs/lighthouse/accessibility/)

### 2. Handmatige tests

Lighthouse is een geautomatiserde test, die veel voorkomende toegankelijkheidsproblemen kan testen. Echter, een geautomatiseerde test is _nooit_ voldoende om een website goed op toegankelijkheid te testen. Hiervoor moet je nog een aantal handmatige tests uitvoeren en beoordelen. In het Lighthouse rapport staan een aantal handmatige checks genoemd, maar ook op de website van The A11Y Project staat een checklist. Deze gaan we gebruiken om de bestaande website mee te testen.

#### Aanpak

- Lees de handmatige checks die in het Lighthouse rapport worden aanbevolen.
- Vergelijk de lijst met de checklist van de A11Y Project checklist. Je zult dan zien dat hier (ongeveer) dezelfde checks staan, maar dan anders georganiseerd.
- Begin met het testen van de website met je _keyboard_, zoals beschreven in het artikel, “How To Do an Accessibility Review”.
- Test de website met een _screen reader_, zoals beschreven in het artikel, “How To Do an Accessibility Review”.
- Test de _interactive elements_ en _headings and landmarks_ van de website, zoals beschreven in het artikel “How To Do an Accessibility Review”.
- Documenteer je bevindingen stap voor stap in de Wiki.

#### Bronnen handmatige tests

- [How To Do an Accessibility Review](https://web.dev/how-to-review/)
- [The A11Y Project Checklist](https://www.a11yproject.com/checklist/)
- [Building the most inaccessible site possible with a perfect Lighthouse score](https://www.matuzo.at/blog/building-the-most-inaccessible-site-possible-with-a-perfect-lighthouse-score/)

#### Bronnen screen reader software
 
 - [VoiceOver voor macOS (en iOS)](https://webaim.org/articles/voiceover/)
 - [JAWS voor Windows](https://support.freedomscientific.com/Downloads/JAWS)
 - [NVDA voor Windows](https://www.nvaccess.org/download/)
 - [Screen Reader Keyboard Shortcuts and Gestures](https://dequeuniversity.com/screenreaders/)

## Definition of done

Deze opdracht is done als:

- [ ] Je hebt een Lighthouse test gedaan op een bestaande website en de test is gedocumenteerd in de Wiki van deze deeltaak
- [ ] Je hebt een _keyboard navigatie_ test gedaan op een bestaande website en gedocumenteerd in de wiki
- [ ] Je hebt een _screen reader_ test gedaan op een bestaande website en gedocumenteerd in de wiki
- [ ] Je hebt een _interactive elements_ test gedaan op een bestaande website en gedocumenteerd in de wiki
- [ ] Je hebt een _headings and landmarks_ test gedaan op een bestaande website en gedocumenteerd in de wiki
