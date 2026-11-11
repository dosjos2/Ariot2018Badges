# ARIoT 2018 Badges

En C#-løsning for innsamling og administrasjon av badges fra ARIoT 2018. En scraper leser badges fra arrangementets nettside, mens en ASP.NET MVC-applikasjon viser og administrerer dem.

## Innhold

- `BadgeCollector/`: webapplikasjon med visning og administrasjon av badges, bedømming og status.
- `BadgeScraper/`: konsollprogram som periodisk henter badges fra nettsiden.
- `Models/`: felles modeller og Entity Framework-datakontekst.
- `Paho.MqttDotnet-master/`: medfølgende MQTT-bibliotek; scraperen har også kommenterte integrasjonsforsøk.
- `BadgeCollector.sln`: Visual Studio-løsningen.

## Åpne prosjektet

Åpne `BadgeCollector.sln` i Visual Studio med støtte for klassisk ASP.NET og .NET Framework, og gjenopprett NuGet-pakkene. Kontroller databaseoppsett og eksterne adresser før kjøring. Scraperen er avhengig av HTML-strukturen på den opprinnelige nettsiden.

## Opphav og historikk

- Opprinnelig repo: [dosjos/Ariot2018Badges](https://github.com/dosjos/Ariot2018Badges).
- Opprinnelig opprettet på GitHub: **2018-03-14 14:02:04 UTC** (GitHubs metadata for kilderepoet).
- Denne kopien: [dosjos2/Ariot2018Badges](https://github.com/dosjos2/Ariot2018Badges).

Flyttet fra `dosjos` til `dosjos2` fordi eieren mistet tilgangen til den opprinnelige kontoen. Eksisterende Git-historikk, forfattere, grener og tags er bevart; README-oppdateringen er en ny commit. GitHub-opprettelsesdatoen for denne kopien er datoen for flyttingen, og erstatter ikke datoen ovenfor.

Beskrivelsen er basert på kildekoden og prosjektfilene. Bygg og kjøring av de historiske prosjektene er ikke verifisert ved flyttingen. Eksisterende lisensfiler og krediteringer gjelder fortsatt.
