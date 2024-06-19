> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Fresk.digital
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
### Het idee
![mockup-01](https://github.com/SamaraFellaDina/proof-of-concept/assets/144009778/67360457-eceb-4371-bd2d-14f78ec6e0f8)
### De uitwerking
![mockup-02](https://github.com/SamaraFellaDina/proof-of-concept/assets/144009778/47ed6401-0d8e-4d1c-a7c1-384f41ca87be)

Bij deze opdracht voor Fresk.digital, maak ik statistieken die van hun API's komen. Zodat zij een overzicht krijgen van hun voortgang. 

## Gebruik
<!-- Bij Gebruik staat de user story, hoe het werkt en wat je er mee kan. -->
* Initial setup - choose correct tech, setup repo, setup server/hosting etc [#25](https://github.com/SamaraFellaDina/proof-of-concept/issues/25)
* Show some data from the Google Analytics API [#26](https://github.com/SamaraFellaDina/proof-of-concept/issues/26)
* Apply the fresk branding [#27](https://github.com/SamaraFellaDina/proof-of-concept/issues/27)
* Add login/authentication [#28](https://github.com/SamaraFellaDina/proof-of-concept/issues/28)
* Show some data from the LinkedIn Analytics API [#29](https://github.com/SamaraFellaDina/proof-of-concept/issues/29)
* Show some data from the Hotjar API [#30](https://github.com/SamaraFellaDina/proof-of-concept/issues/30)
* Show some data from all three platforms of the same user (show that we can combine data) [#31](https://github.com/SamaraFellaDina/proof-of-concept/issues/31)

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? Misschien heb je iets met NodeJS gedaan, of heb je een framwork of library gebruikt? -->
Welke kenmerken heb ik gebruikt bij het maken van dit project?
* sever-side rendering
* `EJS`
* `Node`
* `Express`
* `ChartJS`
* Google Analytics API
* `.env`
* credentials Json
  
## Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->
* clone deze repo naar je eigen Git desktop
* Open de terminal
* voer de volgende commands uit:
  * `npm install`
    * (Ik heb zelf ook `nodemon` gebruikt)
  * `npm install @google-analytics/data`
  * `npm install dotenv --save`
* Hiermee heb je de volgende packages geinstalleerd:
  * `Google analytics data`
  * `node`
  * `dotenv`
 * Tot slot wil je de API ophalen. Volg deze [guide](https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries) Volg de stappen vanaf stap 3

***Hou er rekening mee dat je bij het maken van dit project een bemachtiging moet hebben op de `credentials.json` van Fresk.digital*** 

## Bronnen
* [Fresk.digital](https://fresk.digital/en)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [Google Analytics Quickstart](https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries)
* [Chartjs](https://www.chartjs.org/docs/latest/)
### Handige bronnen binnen dit project
* [Project board](https://github.com/users/SamaraFellaDina/projects/11)
* [wiki](https://github.com/SamaraFellaDina/proof-of-concept/wiki)
* [Iteraties](https://github.com/users/SamaraFellaDina/projects/11/views/2)
* [Issues](https://github.com/SamaraFellaDina/proof-of-concept/issues)
* [Sprint review](https://github.com/SamaraFellaDina/proof-of-concept/wiki/4.-Testen%F0%9F%A7%AA#sprint-review)
* [commits](https://github.com/fdnd-task/proof-of-concept/compare/main...SamaraFellaDina:proof-of-concept:main)
* [pull-requests](https://github.com/fdnd-task/proof-of-concept/pulls)

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

