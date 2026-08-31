> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../08-What-Works-Today.md) | [Alle talen](../README.md)

# Wat de huidige implementatie doet

![Ideeën, tests, mislukkingen en bewezen capaciteiten blijven duidelijk gescheiden.](../../illustrations/evidence-implementation-gates.png)

Robot Brain draait software voor het behouden en opnieuw opbouwen van de betekenis rond opgenomen werk. Het is geen voorstel voor een chatbot, en de huidige implementatie ervan is geen taalmodel.

## Mogelijkheden in de huidige implementatie

Uit geregistreerde runs blijkt dat de software:

- een voltooid gesprek bewaren zonder het te vervangen door een samenvatting
- houd de woorden van de persoon gescheiden van modelantwoorden en latere interpretaties
- creëer gedetailleerde bevindingen over taal, betekenis, redenering, tijd, menselijke ervaring en waarden
- Verbind elke bewaarde bevinding met het deel van het gesprek erachter
- bewaar correcties, meningsverschillen, mislukt werk en onbeantwoorde vragen
- voeg een gedateerd lokaal algemeen kennisoverzicht toe zonder het originele online model aan te roepen
- de ingehouden bijdragen verzamelen voor een aangevraagde reconstructie
- registreer wat er is gecontroleerd, afgewezen, gecorrigeerd en geaccepteerd
- een scherm of deelnemend taalmodel vervangen zonder de opgeslagen geschiedenis te vervangen

Dit zijn functies van de software rondom de modellen. Het zijn geen vaardigheden waarvoor wordt geclaimdQwen,LibreChat, of een online assistent.

## Wat er is gebeurd in de mijlpaal van het voltooide gesprek

Het geteste gesprek is opgeslagen met de berichten van de persoon en de antwoorden van het online model op volgorde.

Gerichte lokale methoden produceerden vervolgens afzonderlijke records over de uitwisseling. Hun werk omvatte taal en betekenis, redeneren, psychologische observaties, filosofische observaties, relaties en veranderingen in de loop van de tijd. Elke behouden bijdrage bleef gebonden aan het bronmateriaal en de methode waarmee het geproduceerd werd.

Deze gedetailleerde methoden bevatten opzettelijk niet de brede achtergrondkennis van een model voor algemene doeleinden. Een kleine lokaleQwenmodel, gediend doorvLLM, geselecteerd materiaal gelezen en een gedateerd overzicht toegevoegd. Het was zijn taak om gewone achtergrondinformatie te verschaffen die de afzonderlijke bevindingen met elkaar verbond en de uitwisseling als geheel begrijpelijk maakte.

Qwenheeft de verborgen gedachten, de trainingsgeschiedenis of de persoonlijke interne toestand van het oorspronkelijke model niet hersteld. De nuttige bijdrage van het oorspronkelijke model was al aanwezig in de opgeslagen berichten. Brede achtergrondkennis werd geleverd door een vervangbaar lokaal model, omdat die kennis niet uniek was voor de oorspronkelijke aanbieder.

## Wat ‘voltooid’ betekent voor deze mijlpaal

Het woord verwijst naar de bijgehouden lijst met bijdragen voor deze run. Elke bronboodschap en elke bijdrage die het proces voor de reconstructie heeft behouden, kan worden gevonden en opnieuw verzameld.

Het betekent niet dat één model een volledige interpretatie gaf. De prestatie is dat de geaccepteerde stukken bewaard blijven, gescheiden door bron en methode, en beschikbaar zijn voor reconstructie zonder de oorspronkelijke online uitwisseling opnieuw uit te voeren.

## Hoe de claim wordt ondersteund

De run registreert welke onderdelen zijn uitgevoerd, wat ze hebben ontvangen, wat ze hebben geretourneerd, welke bijdragen zijn afgewezen en welke controles zijn geslaagd. De reconstructie wordt gemeten aan de hand van de eigen opgeslagen lijst met verwachte records.

Een componententest wordt omschreven als een componententest. Een verbonden run wordt beschreven als een verbonden run. Geplande werkzaamheden blijven gescheiden van de huidige uitvoering.

Het volgende werk omvat bredere onafhankelijke tests, ondersteuning voor meer soorten documenten, meer talen en culturen, duidelijkere beoordelingsschermen en een betere meting van de tijd die mensen besteden aan het lezen en corrigeren van resultaten.
