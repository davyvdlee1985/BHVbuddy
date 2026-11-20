# BHV Buddy — MVP-plan Brand & Ontruiming

## Productdoel

BHV Buddy ondersteunt echte cursisten met een Nederlandstalige, interactieve digitale cursus **Brand & Ontruiming** van ongeveer twee uur. Na afronding volgt een afzonderlijke praktische les waarin cursisten onder begeleiding van een bevoegde instructeur de praktische handelingen daadwerkelijk uitvoeren.

De digitale cursus is voorbereiding en leerondersteuning. De app verklaart een cursist niet zelfstandig praktisch bekwaam en verleent geen certificaat of bevoegdheid. Praktische beoordeling en eventuele certificering vallen buiten de AI-beoordeling en worden door de verantwoordelijke opleider/instructeur uitgevoerd.

## Doelgroep en rollen

- **Cursist:** volgt de digitale les, oefent scenario’s en maakt de kennistoets.
- **Instructeur:** beheert de lesgroep, bekijkt voortgang en bespreekt resultaten; beoordeelt de praktische les zelf.
- **Beheerder/contentbeheerder:** beheert cursusversies, bronnen, vertalingen en goedkeuringsstatus.

## Leerervaring

De cursus bestaat uit interactieve uitleg, korte kennischecks, situaties om over na te denken en een afsluitende kennistoets. De AI-instructeur gebruikt alleen door de inhoudsverantwoordelijke goedgekeurde cursusinformatie. Antwoorden buiten de goedgekeurde inhoud worden als zodanig gemarkeerd en niet ingevuld op basis van giswerk.

### Voorlopige opbouw van de digitale les (120 minuten)

| Onderdeel | Richttijd |
| --- | ---: |
| Introductie, leerdoelen en afspraken | 5 min |
| Brandveiligheid, brandrisico’s en preventie | 15 min |
| Brand herkennen, alarm slaan en melden | 15 min |
| Eigen veiligheid en eerste besluitvorming | 15 min |
| Blusmiddelen: keuze, toepassingsgrenzen en theorie | 20 min |
| Ontruimingsplan, routes, taken en communicatie | 20 min |
| Scenario-oefeningen en klassikale/AI-nabespreking | 20 min |
| Kennistoets en persoonlijke terugkoppeling | 10 min |
| **Totaal** | **120 min** |

Dit is een eerste planningsverdeling. De inhoud, volgorde en tijdsduur worden afgestemd op de toepasselijke opleidingsdoelen en goedgekeurd door de inhoudsdeskundige. De cursus kan pauzemomenten bevatten; de gerapporteerde leertijd moet daarom van verstreken tijd te onderscheiden zijn.

## Aparte praktische les

Na de digitale cursus wordt een praktische les gepland. Daarin voert iedere cursist de praktische handelingen zelf uit onder toezicht van een instructeur, met passende oefenmiddelen en volgens de lokale procedures en veiligheidsafspraken.

De app kan de praktische les ondersteunen met:

- een instructeurschecklist die door de opleider wordt opgesteld en goedgekeurd;
- registratie dat de praktijkles gepland of bijgewoond is;
- registratie van de beoordeling door de instructeur, met beoordelaar en datum;
- terugkoppeling naar relevante digitale lesonderdelen.

De app laat de AI geen praktische handeling op afstand aftekenen en leidt deelname aan de digitale cursus niet automatisch af als bewijs van praktische bekwaamheid.

## Eerste MVP-functionaliteit

1. Nederlandstalige cursusweergave en toegankelijk lesoverzicht.
2. Lesblokken met tekst, afbeeldingen/video-verwijzingen, bronnen en kennischecks.
3. AI-instructeur met context uit uitsluitend goedgekeurde cursusinhoud.
4. Scenario-oefeningen met vooraf vastgestelde beoordelingscriteria en feedback.
5. Kennistoets met score, uitleg en verwijzing naar relevante lesstof.
6. Opslaan van cursusversie, voortgang en toetsresultaat.
7. Instructeursweergave voor cursisten, voortgang en resultaten.
8. Status van de afzonderlijke praktische les, met beoordeling die door een instructeur wordt ingevoerd.
9. Beheer van goedkeuringsstatus en versies van lesinhoud.

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
- Houd rekening met verschillen tussen organisaties: instructies en verzamelplaatsen mogen niet als universeel worden aangenomen.
- Bij vragen buiten de lesinhoud verzint de AI geen procedure, maar verwijst naar de instructeur, het lokale bedrijfsnoodplan of de aangewezen noodprocedure.
- Houd voortgangs- en AI-gegevens beperkt tot wat nodig is, met passende toegangsrechten en bewaartermijnen.

## Acceptatiecriteria voor de eerste pilot

- Een cursist kan de volledige Nederlandse digitale cursus volgen en tussentijds voortgang hervatten.
- De geplande lesonderdelen tellen samen op tot circa 120 minuten leertijd.
- De AI geeft antwoorden op basis van goedgekeurde inhoud en maakt onzekerheid of ontbrekende informatie duidelijk.
- De scenario’s en kennistoets zijn door een inhoudsdeskundige beoordeeld.
- Een instructeur kan voortgang en toetsresultaten zien.
- De praktische les is afzonderlijk zichtbaar en kan uitsluitend door een instructeur worden geregistreerd/beoordeeld.
- Cursusresultaten vermelden de gevolgde inhoudsversie en taal.
- Er zijn geen claims dat de digitale cursus op zichzelf een praktijktoets of certificering vervangt.

## Voorgestelde bouwvolgorde

1. Inhoudsmodel, Nederlandse taalinstelling en cursusstructuur.
2. Cursistweergave, voortgang en eerste lesblokken.
3. Scenario’s en kennistoets.
4. AI-instructeur op basis van goedgekeurde cursusinhoud.
5. Instructeursomgeving en registratie van de afzonderlijke praktijkles.
6. Pilot, inhoudelijke review, privacy- en beveiligingscontrole.
7. Pas daarna vertaalworkflow en aanvullende talen.

## Open inhoudelijke input

Voor de cursusproductie zijn nog nodig: de gewenste eindtermen/opleidingsstandaard, jouw lesmateriaal en voorbeelden van jouw lesstijl, eventuele bestaande lokale procedures, en de instructeurschecklist voor de praktische les. Gebruik geen organisatiegebonden noodinstructies als algemene standaard zonder ze als lokaal configureerbare inhoud te behandelen.
