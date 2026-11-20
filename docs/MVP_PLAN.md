# BHV Buddy — MVP-plan Brand & Ontruiming

## Productdoel

BHV Buddy ondersteunt echte cursisten met een Nederlandstalige, interactieve **basiscursus BHV Brand & Ontruiming** van ongeveer twee uur. De digitale cursus leert de algemene basisprincipes van brandveiligheid, eerste reactie bij brand en ontruiming.

De cursus is zelfstandig opgezet en hoeft niet aan te sluiten op een specifieke praktische les, opdrachtenreeks of lokaal cursusprogramma. Een organisatie kan haar eigen praktische training daarnaast aanbieden, maar die is geen onderdeel van dit MVP en wordt niet inhoudelijk aan de digitale cursus gekoppeld.

De app maakt geen aanspraak op het vervangen van vereiste praktijktraining, praktijkbeoordeling of een erkende certificering. De precieze positie van de cursus als opleiding of aanvulling moet vóór inzet met de opleider en relevante opleidingsstandaard worden vastgesteld.

## Doelgroep en rollen

- **Cursist:** volgt de digitale les, oefent scenario’s en maakt de kennistoets.
- **Instructeur:** bekijkt de voortgang en resultaten van cursisten.
- **Beheerder/contentbeheerder:** beheert lesinhoud, bronnen, vertalingen en goedkeuringsstatus.

## Leerervaring

De cursus bestaat uit interactieve uitleg, korte kennischecks, algemene situaties om over na te denken en een afsluitende kennistoets. De AI-instructeur gebruikt alleen door de inhoudsverantwoordelijke goedgekeurde cursusinformatie. Antwoorden buiten de goedgekeurde inhoud worden als zodanig gemarkeerd en niet ingevuld op basis van giswerk.

### Voorlopige opbouw van de digitale basiscursus (120 minuten)

| Onderdeel | Richttijd |
| --- | ---: |
| Introductie, leerdoelen en afspraken | 5 min |
| Brandveiligheid, brandrisico’s en preventie | 15 min |
| Brand herkennen, alarm slaan en melden | 15 min |
| Eigen veiligheid en eerste besluitvorming | 15 min |
| Blusmiddelen: algemene keuze, toepassingsgrenzen en theorie | 20 min |
| Ontruiming: algemene principes, vluchtroutes, rollen en communicatie | 20 min |
| Algemene scenario-oefeningen en nabespreking | 20 min |
| Kennistoets en persoonlijke terugkoppeling | 10 min |
| **Totaal** | **120 min** |

Dit is een eerste planningsverdeling. De inhoud, volgorde en tijdsduur worden afgestemd op de toepasselijke opleidingsdoelen en goedgekeurd door een inhoudsdeskundige. De cursus kan pauzemomenten bevatten; de gerapporteerde leertijd moet daarom van verstreken tijd te onderscheiden zijn.

De cursus behandelt algemene uitgangspunten. Locatiegebonden zaken, zoals interne alarmnummers, specifieke vluchtroutes, taken en verzamelplaatsen, moeten door organisaties apart worden vastgesteld en mogen niet als universele instructies worden gepresenteerd.

## Afbakening praktische training

Praktische lessen en opdrachten vallen buiten het MVP. De digitale cursus hoeft niet de volgorde, opdrachten of beoordelingscriteria van een specifieke praktijkles te volgen. Er is in deze MVP geen registratie, checklist of AI-beoordeling voor praktische handelingen.

De cursus maakt wel duidelijk dat digitale kennisopbouw op zichzelf geen bewijs is dat iemand praktische handelingen heeft uitgevoerd of praktisch bekwaam is. Organisaties en opleiders bepalen zelf welke praktische training of beoordeling aanvullend nodig is.

## Eerste MVP-functionaliteit

1. Nederlandstalige cursusweergave en toegankelijk lesoverzicht.
2. Lesblokken met tekst, afbeeldingen/video-verwijzingen, bronnen en kennischecks.
3. AI-instructeur met context uit uitsluitend goedgekeurde cursusinhoud.
4. Algemene scenario-oefeningen met vooraf vastgestelde beoordelingscriteria en feedback.
5. Kennistoets met score, uitleg en verwijzing naar relevante lesstof.
6. Opslaan van cursusversie, voortgang en toetsresultaat.
7. Instructeursweergave voor cursisten, voortgang en resultaten.
8. Beheer van goedkeuringsstatus en versies van lesinhoud.

## Taaluitbreiding

- MVP-taal: Nederlands (`nl-NL`).
- Interface-teksten worden gescheiden van lesinhoud en in vertaalbestanden opgeslagen.
- Lesinhoud krijgt een stabiele inhouds-ID, taalcode, versienummer en goedkeuringsstatus.
- Een vertaalde versie wordt pas beschikbaar na inhoudelijke controle en goedkeuring; een letterlijke vertaling geldt niet automatisch als gevalideerde cursus.
- Cursusvoortgang en resultaten verwijzen naar de gevolgde taal- en inhoudsversie.
- AI-antwoorden blijven in de geselecteerde taal en gebruiken de goedgekeurde inhoud van die taal; als die ontbreekt, wordt dat duidelijk gemeld.

## Inhoudelijke veiligheid en kwaliteitscontrole

- Laat leerdoelen, lesmateriaal, scenario’s en toetsvragen vóór gebruik goedkeuren door de inhoudsverantwoordelijke/BHV-deskundige.
- Leg per inhoudsversie bronnen, eigenaar, beoordelaar en datum van laatste controle vast.
- Houd rekening met verschillen tussen organisaties: interne instructies, alarmprocedures, routes en verzamelplaatsen zijn lokaal configureerbaar en worden niet als universeel aangenomen.
- Bij vragen buiten de lesinhoud verzint de AI geen procedure, maar verwijst naar de instructeur, het lokale bedrijfsnoodplan of de aangewezen noodprocedure.
- Houd voortgangs- en AI-gegevens beperkt tot wat nodig is, met passende toegangsrechten en bewaartermijnen.
- Maak duidelijk onderscheid tussen digitale kenniscontrole en praktische uitvoering/beoordeling.

## Acceptatiecriteria voor de eerste pilot

- Een cursist kan de volledige Nederlandse digitale basiscursus volgen en tussentijds voortgang hervatten.
- De geplande lesonderdelen tellen samen op tot circa 120 minuten leertijd.
- De cursus behandelt de algemene basisprincipes van BHV Brand & Ontruiming en is niet afhankelijk van een specifieke praktische les.
- De AI geeft antwoorden op basis van goedgekeurde inhoud en maakt onzekerheid of ontbrekende informatie duidelijk.
- De scenario’s en kennistoets zijn door een inhoudsdeskundige beoordeeld.
- Een instructeur kan voortgang en toetsresultaten zien.
- Cursusresultaten vermelden de gevolgde inhoudsversie en taal.
- De app presenteert voltooiing van de digitale cursus niet als bewijs van praktische uitvoering, praktische bekwaamheid of certificering.

## Voorgestelde bouwvolgorde

1. Inhoudsmodel, Nederlandse taalinstelling en cursusstructuur.
2. Cursistweergave, voortgang en eerste lesblokken.
3. Algemene scenario’s en kennistoets.
4. AI-instructeur op basis van goedgekeurde cursusinhoud.
5. Instructeursomgeving voor voortgang en resultaten.
6. Pilot, inhoudelijke review, privacy- en beveiligingscontrole.
7. Pas daarna vertaalworkflow en aanvullende talen.

## Open inhoudelijke input

Voor de cursusproductie zijn nog nodig: de gewenste eindtermen/opleidingsstandaard, jouw lesmateriaal en voorbeelden van jouw lesstijl, en de inhoudelijke bronnen die gebruikt mogen worden. Organisatiegebonden noodinstructies worden alleen toegevoegd als optionele, lokaal beheerde inhoud.
