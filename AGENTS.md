# Website-instructies

Deze instructies zijn de standaard werkwijze voor **iedere wijziging** aan deze
GitHub Pages-website. De gebruiker hoeft ze niet per opdracht te herhalen.

- Lees en volg dit bestand vóór je aan een wijziging begint.
- Onderzoek eerst de bestaande structuur, inhoud en huisstijl.
- Maak alleen de kleinste wijziging die nodig is voor de opdracht.
- De productiebranch is main.
- Wijzig main nooit rechtstreeks.
- Werk uitsluitend in een aparte branch of worktree en gebruik voor branches
  het prefix `codex/`.
- Push, merge en publiceer uitsluitend na mijn expliciete toestemming.
- Bewaar nooit wachtwoorden, tokens of API-sleutels in de repository.
- Dit is een statische GitHub Pages-site zonder Node-project of buildstap. Voeg geen
  `package.json`, framework of buildtool toe tenzij de opdracht dat vereist.
- Start de website vóór oplevering via een lokale HTTP-server; open HTML-bestanden
  niet alleen rechtstreeks vanaf de schijf.
- Controleer de website visueel in desktop- en mobiel formaat.
- Controleer gewijzigde pagina's, navigatie, interne en externe links, afbeeldingen,
  horizontale overflow en fouten of waarschuwingen in de browserconsole.
- Controleer redirects vanaf hun oorspronkelijke URL en voorkom een terug-knoplus.
- Voer `git diff --check` uit vóór commit of oplevering.
- Geef na iedere wijziging het resultaat, een overzicht van gewijzigde bestanden,
  de uitgevoerde controles en testresultaten, en eventuele resterende risico's.
- Controleer na een toegestane publicatie de GitHub Pages-deployment en herhaal de
  relevante controles op de live website.

## Controlecommando's

- Installeren: niet van toepassing.
- Lokale website (Windows): `py -m http.server 4173 --bind 127.0.0.1`
- Alternatief: `python -m http.server 4173 --bind 127.0.0.1`
- Open lokaal: `http://127.0.0.1:4173/`
- Productiebuild: niet van toepassing; GitHub Pages publiceert de statische bestanden
  rechtstreeks vanaf de productiebranch.
- Technische controle: `git diff --check`
- Tests: voer de hierboven beschreven browsercontroles handmatig of geautomatiseerd uit.
