> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Alle talen](../README.md)

# Gebruik een taalmodel voor de taak, niet als geheugen

![Tools, getrainde bestanden en bronverzamelingen houden afzonderlijke gegevens bij over hun oorsprong en voorwaarden.](../../illustrations/tool-model-source-index.png)

Robot Brain is geen taalmodel met extra geheugen. Het is de software voor het bijhouden, analyseren, samenstellen en controleren van gegevens die beslist wanneer een taalmodel zou kunnen helpen en welke beperkte taak het kan vervullen.

Het krachtigste beschikbare model is niet altijd de beste keuze voor die klus.

Een betaald taalmodel kan geschikt zijn voor moeilijk onderzoek of schrijven. Een klein lokaal model kan voldoende zijn voor achtergrondverklaring. Zoeken kan voldoende zijn om een ​​doorgang te vinden. Een vast proces kan veiliger zijn als het antwoord een exacte regel moet volgen. Soms is het beste antwoord een antwoord dat al is gecontroleerd en opgeslagen.

De request builder maakt die keuze vanuit de behoefte van de functie. Het kan een model gebruiken, verschillende beperkte methoden combineren, gecontroleerd werk hergebruiken of helemaal geen modelaanroep doen. Daarom is dit geen proxy die aanvragen zomaar doorstuurt naar een andere dienst.

## Betaalde online modellen

Commerciële taalmodeldiensten hielpen bij de opbouw van dit project. Ze ondersteunden onderzoek, coderen, schrijven en beoordelen.

Ze raakten ook eerdere instructies kwijt, verkortten gesprekken, gokten op oorzaken, begroeven korte antwoorden in invulmateriaal en rapporteerden het werk als voltooid voordat ze het controleerden. Voor het corrigeren van deze fouten was meer betaalde toelage en meer menselijke tijd nodig.

Hun diepere grens is geen slechte aanwijzing. Een getraind model kan niet de volledige geschiedenis van het menselijke werk dat het model heeft geleerd, opnieuw opbouwen. Het houdt patronen vast en verliest betrouwbare links naar elke auteur, doel, publiek, dispuut, correctie en ontbrekend gezichtspunt.

Die brede kennis komt nog steeds van pas. Het mag simpelweg niet de enige plek worden waar iemands geschiedenis bestaat.

Voor een online aanvraag,Robot Brain registreert welk model is gebruikt, wat het heeft ontvangen, wat het heeft geretourneerd, wat de servicekosten zijn geweest, welke controles zijn uitgevoerd en of het resultaat is behouden. Niet-ondersteunde achtergrond blijft eerder een suggestie van het model dan een feitelijk feit.

## Het lokale model is niet op de persoon getraind

De huidige installatie draait kleinQwentaalmodel doorvLLMop lokale hardware.Qwenis één vervangbare bijdrager, niet het project zelf.

Het leert niet door te trainen in de gesprekken, het werk of het leven van de persoon. Training zou die geschiedenis in een model verwerken en de weg terug naar de oorspronkelijke woorden en gebeurtenissen verzwakken.

In plaats van,Qwenontvangt geselecteerd materiaal voor één klus nadat een gesprek is beëindigd. Andere lokale methoden hebben de taal, uitspraken, relaties, redenering, tijd, menselijke ervaring en waarden in de uitwisseling al onderzocht.Qwenvoegt de brede achtergrond toe die deze methoden niet delen. Dit maakt het gemakkelijker om uit te leggen wat er is gebeurd en waarom.

Qwenonthult niet de verborgen gedachten, training of privéredenen van de online assistent. De nuttige bijdrage van de online assistent is al aanwezig in het opgeslagen gesprek. Algemene achtergrondkennis is niet uniek voor die assistent, dus een ander geschikt model kan helpen de opgenomen stukken met elkaar te verbinden.

DeQwenDe meting wordt opgeslagen met de modelnaam en datum. Het blijft gescheiden van het gesprek en kan later gecorrigeerd of vervangen worden. Het verzoek hoeft de lokale hardware nooit te verlaten.

## Zoeken is geen verklaring

Zoeken kan passages vinden met verwante woorden of onderwerpen. Het kan niet beslissen waarom een ​​gebeurtenis ertoe doet, of de ene actie de andere veroorzaakte, of wat iemand bedoelde.

Deze conclusies hebben bewijsmateriaal, geschiedenis en ruimte voor correctie nodig.

## De kosten omvatten de tijd van de persoon

Prijs en snelheid zijn niet de enige kosten. Een goedkoop antwoord wordt duur als iemand uren besteedt aan het opsporen van de fout, het opnieuw uitleggen van de geschiedenis en het herstellen van het resultaat.

De verzoekbouwer houdt daarom rekening met servicekosten, wachten, nieuwe pogingen, energieverbruik en menselijke controle. Een kleiner model, een vaste lokale methode of een opgeslagen resultaat kunnen meer waarde creëren als het werk ervan gemakkelijker te inspecteren is.

## Bronnen blijven identificeerbaar

Originele documenten, gekopieerde tekst, modelreacties, openbaar onderzoek, citaten en latere recensies blijven verschillende dingen.

Wanneer bekend en toegestaan, worden in het document de maker, het doel, het publiek, de datum, de taal, het bewijsmateriaal, het meningsverschil, de rechten en latere correcties bewaard. Publieke beschikbaarheid en kredietwaardigheid geven op zichzelf geen toestemming om beschermd materiaal te herverdelen.

Deze repository bevat openbare documentatie en door projecten gemaakte illustraties. Het laat privégegevens, wachtwoorden, toegangsgegevens, providergeheimen en extern materiaal dat niet is vrijgegeven voor vrijgave achterwege.
