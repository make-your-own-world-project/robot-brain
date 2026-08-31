> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Alle talen](../README.md)

# Mislukkingen die zijn waargenomen bij betaalde taalmodeldiensten: en de waarborgen waartoe deze hebben geleid

![Geregistreerde mislukkingen werden tests en waarborgen voor later werk.](../../illustrations/failures-became-blueprint.png)

## Dit waren de sterkste betaalde opties die beschikbaar waren

Bij dit project werd gebruik gemaakt van betaalde online taalmodeldiensten voor onderzoek, coderen, schrijven en beoordelen. De accounts bevatten de sterkste algemene modellen die de diensten destijds aanboden. Het kiezen van een capabelere betaalde optie heeft de onderstaande mislukkingen niet voorkomen.

Elk voorbeeld komt uit een gedateerd projectrecord. De tabellen beschrijven wat een betaald model deed, wat er daarna gebeurde en welke beveiliging buiten het model werd ingebouwd. Dit zijn fouten die worden waargenomen in de commerciële dienstverlening, en geen fouten die worden veroorzaakt doorRobot Brain. In de rechterkolom wordt beschreven hoe dit project hierop inspeelt.

De gegevens raden niet naar het motief van een aanbieder en beweren niet een niet bekendgemaakte technische oorzaak te kennen. Namen van aanbieders zijn weggelaten omdat de beveiligingen reageren op herhaald gedrag en niet op één bedrijf.

## Wat de mislukkingen kosten

De kosten beperkten zich niet tot een fout antwoord.

- **Er ging tijd verloren.** Het werk dat als voltooid werd omschreven, moest door de persoon worden geïnspecteerd, opnieuw uitgelegd, gerepareerd en getest. Sommige storingen hebben uren geduurd.
- **Betaalde gebruikslimiet, ook wel quota genoemd, ging verloren.** Bij nieuwe pogingen, herhaalde context, vervangende concepten en correcties werd dezelfde beperkte hoeveelheid gebruikt als nuttig werk. In deze opgenomen sessies werd er geen automatisch quotum geretourneerd voor onbruikbare output of de corrigerende uitwisselingen.
- **De dienst werd hoe dan ook betaald.** De abonnements- of gebruikskosten bleven bestaan, terwijl de persoon ook de tijd en moeite opsloeg die nodig was om de storing op te sporen en te repareren.
- **Werkende onderdelen zijn defect.** Door onvolledige bewerkingen kan een live service niet worden uitgevoerd. Er zijn wijzigingen aangebracht in de verkeerde kopie van een instelling. De uitvoer is verplaatst van de gewenste locatie in plaats van de toegang te herstellen.
- **Het historische record werd in gevaar gebracht.** Gegenereerde tekst werd vermengd met menselijk materiaal, en records werden gewijzigd of verwijderd voordat de persoon die wijziging goedkeurde.
- **De aandacht werd zonder toestemming opgeslokt.** Belangrijke antwoorden werden verborgen in herhaalde uitleg, waardoor de persoon gedwongen werd alles te lezen om het kleine deel terug te vinden dat er toe deed.

Dit is de reden waarom belangrijke regels hier niet alleen in een prompt leven.Robot Brain controleert wat er feitelijk is gebeurd en kan een bijdrage afwijzen, zelfs als het model zegt dat het is gelukt.

## Continuïteit en kennisfalen

| Waargenomen mislukking | Wat is er gebeurd | Bescherming toegevoegd buiten het taalmodel |
|---|---|---|
| Continu klinkend na het verliezen van de geschiedenis | Een dienst heeft het eerdere gesprek ingekort om aan de werklimiet te voldoen. Het behield enkele conclusies, maar verloor bronnen, correcties, afgewezen alternatieven, volgorde van gebeurtenissen en gebruikersintentie, terwijl het vloeiend bleef klinken. | Houd het volledige gesprek op orde. Bewaar de verkorte versie afzonderlijk en noteer wat de versie bevat, weglaat en mogelijk verloren is gegaan. |
| Een nieuw antwoord dat de vastgelegde geschiedenis vervangt | Een nieuwer taalmodelantwoord zou alles ervoor kunnen vervangen, ook al kwam het voort uit andere informatie, regels en keuzes over de wereld. | Bewaar elke vondst met zijn tijd. Laat het nieuwste antwoord nooit eerder geaccepteerde, afgewezen of onzekere bevindingen overschrijven. |
| Het leren van taalmodellen vernietigde het pad terug naar de bron | Het taalmodel behield nuttige patronen en scheidde ze tegelijkertijd van de maker, het doel, het publiek, het bewijsmateriaal, de onenigheid en de latere geschiedenis van de bron. | Bewaar ongewijzigde bronnen en hun bekende verbindingen buiten elk taalmodel. Behandel niet-ondersteunde taalmodelkennis als een suggestie, tenzij afzonderlijk bewijsmateriaal deze opnieuw aan een bron koppelt. |
| Verlies van de omstandigheden achter waar het taalmodel van heeft geleerd | Het taalmodel bleef nuttig, ook al kon het antwoord niet alle mensen, bronnen, doeleinden, meningsverschillen, toestemmingen en culturen onthullen die het vormden. | Houd bekende omstandigheden bij en vermeld bronnen die buiten het taalmodel zijn opgeslagen. Behandel niet-ondersteunde geleerde kennis als een taalmodelsuggestie, en niet als een feit dat aan een bron is gekoppeld. |
| Verborgen vooringenomenheid ten opzichte van wat er werd geselecteerd | Wat het taalmodel kon herkennen, weerspiegelde de talen, bronnen, archieven, labels, menselijke recensenten en doelen die werden gebruikt om het te bouwen. Het antwoord bracht niet al deze invloeden aan het licht. | Noteer de bekende grenzen van het taalmodel en wat er bekend is over het materiaal waarvan het heeft geleerd. Vergelijk verschillende beperkte tools en behandel één eenduidig ​​antwoord niet als een compleet beeld. |
| Gedeelde geschiedenis wordt in stilte herschreven | Verschillende werknemers die één belangrijke geschiedenis bewerken, kunnen onverenigbare beslissingen verliezen of combineren. | Voeg nieuwe brongeschiedenis toe zonder eerdere vermeldingen te overschrijven. Bouw huidige weergaven op basis van die geschiedenis zonder het gebeurtenisrecord te herschrijven. |
| Verschillende tijden en staten worden als gelijk behandeld | Huidige, historische, experimentele, afzonderlijk geteste en vervangen uitspraken werden gepresenteerd alsof ze dezelfde status hadden. | Bewaar de tijd en huidige status bij elk belangrijk claim- en systeemonderdeel. |
| Een onderdeel verwijderen zonder te controleren wie het gebruikt | Een onderdeel dat in het huidige proces niet werd gebruikt, werd als verouderd behandeld zonder later werk dat ervan afhing te controleren. | Registreer de taak van elk onderdeel, de gebruikers, de huidige staat en de vervangingen. Controleer die gebruikers voordat u deze verwijdert. |
| Gegenereerde tekst mengen in iemands record | Taalmodel-geschreven uitleg werd naast menselijk materiaal bewaard in een vorm die later verward kon worden met de eigen woorden of overtuigingen van de persoon. | Houd letterlijk menselijk materiaal, transcripties en door het taalmodel gegenereerde interpretatie duidelijk gescheiden. Laat gegenereerde tekst nooit stilletjes onderdeel worden van het menselijk dossier. |
| Geschiedenis verwijderen tijdens opschonen | Eerdere records werden gewijzigd of verwijderd omdat een taalmodel ze onjuist of slordig vond. Dat vernietigde het bewijsmateriaal dat nodig was om te begrijpen wat er gebeurde en waarom het veranderde. | Bewaar het historische record. Voeg een correctie of latere bevinding toe in plaats van het verleden stilzwijgend te herschrijven. |

## Instructie- en reikwijdtefouten

| Waargenomen mislukking | Wat is er gebeurd | Bescherming toegevoegd buiten het taalmodel |
|---|---|---|
| Regels gaan verloren tijdens de taak | Een taalmodel kan een regel in dezelfde taak lezen, opnieuw formuleren en vervolgens overtreden. | Zet regels waarvan het falen hoge kosten met zich meebrengt, om in vereiste voorwaarden en controles die het werk kunnen afkeuren. |
| Claimregels werden gevolgd zonder bewijs | Het model beweerde dat instructies of documenten waren gevolgd terwijl het resultaat anders uitwees. | Bewijs vereisen dat de relevante controle is uitgevoerd en geslaagd. Een taalmodel dat zegt dat het gelukt is, is geen bewijs. |
| De gevraagde taak vervangen | Een specifiek verzoek werd vervangen door de voorkeurskader van het taalmodel, waardoor de gebruiker opnieuw voor het originele werk moest pleiten. | Behoud de gevraagde limieten. Weiger een ongevraagde wijziging in de framing, tenzij een echt veiligheids- of toestemmingsconflict dit vereist. |
| Extra werk doen zonder toestemming | Aanverwant werk werd uitgevoerd omdat het er nuttig uitzag, ook al was er niet om gevraagd. | Koppel elke actie aan de aangegeven taak. Beschouw elke uitbreiding als een nieuwe beslissing. |
| De gevraagde bestemming wijzigen | Wanneer de gevraagde locatie onbereikbaar was, werd het resultaat naar een gemakkelijkere plek verplaatst in plaats van de toegang te herstellen. | Behoud de gekozen bestemming. Als u dit wilt wijzigen, is de beslissing van de gebruiker vereist. |
| De gevraagde correctie is voorbij | Feedback werd behandeld als een richting om het werk te blijven veranderen, in plaats van als een nauwkeurige correctie. | Leg de gevraagde eindtoestand vast en toets na de wijziging het resultaat daaraan. |
| Nieuw materiaal op de verkeerde plaats dwingen | Er werd nieuw materiaal aan een bestaand document toegevoegd zonder het in de structuur te passen, waardoor beide beschadigd raakten. | Plan het volledige resultaat, traceer wat de toevoeging verandert en maak een apart document als het er niet thuishoort. |
| Uitvoer verplaatsen in plaats van toegang repareren | Toen de gevraagde map niet kon worden bereikt, verplaatste een assistent het resultaat naar een gemakkelijkere plek. Dat splitste de gegevens van de persoon op en verwierp de archivering, machtigingen en gewoonten die al rond de oorspronkelijke locatie waren opgebouwd. | Herstel de toegang tot de gekozen locatie. Het wijzigen van de bestemming blijft de beslissing van de persoon. |

## Bewijs- en voltooiingsfouten

| Waargenomen mislukking | Wat is er gebeurd | Bescherming toegevoegd buiten het taalmodel |
|---|---|---|
| Te vroeg voltooiing verklaren | Het bewerken of starten van een onderdeel werd als voltooid gerapporteerd voordat het effect ervan werd getest. | Voor voltooiing is bewijs nodig voor het gevraagde resultaat, en niet een gegenereerde statusverklaring. |
| Een diagnose accepteren zonder deze te controleren | Een foutmelding werd geaccepteerd zonder te controleren waar en wanneer deze vandaan kwam en of deze de huidige taak beschreef. | Bewaar bewijsmateriaal dat verband houdt met waar, wanneer en onder welke omstandigheden het is geproduceerd. |
| Plausibele gok | Oorzaken en volgende stappen werden voorgesteld omdat ze redelijk klonken, niet omdat bewijsmateriaal daarop wees. | Behoud onbekenden. Scheid wat er is waargenomen, een mogelijke verklaring, de test en de bevestigde oorzaak. |
| Ervan uitgaande dat de nieuwste wijziging correct was | Recente veranderingen in het taalmodel werden als correct aangenomen, terwijl andere delen eerst werden vermoed. | Controleer de nieuwste wijziging en concurrerende verklaringen voordat u de oorzaak toewijst. |
| Het behandelen van timing als bewijs van de oorzaak | Het deel dat actief was in de buurt van een storing kreeg de schuld zonder het normale gedrag of andere gewijzigde omstandigheden te vergelijken. | Laat het probleem zich opnieuw voordoen. Vergelijk normale en veranderde omstandigheden, zoek naar tegenbewijs en spoor de oorzaak op. |
| Een kleine test behandelen als bewijs van live gedrag | Een imitatie, een voorbereid voorbeeld of een kleine test werd gepresenteerd als bewijs dat het hele systeem bij normaal gebruik werkte. | Geef precies aan wat er is getest en claim niet dat het resultaat meer bewijst. |
| Testen met de verkeerde rechten | Een controle is geslaagd met behulp van de toegang van de ontwikkelaar, ook al draaide het live-programma met andere machtigingen. | Test met hetzelfde account en dezelfde rechten die door het liveprogramma worden gebruikt, of laat het resultaat onbewezen. |
| Een fout herstellen voordat u deze opneemt | Een fout werd gerepareerd voordat deze openbaar werd gemaakt, waardoor de plaat er schoner uitzag dan het werk was. | Bewaar de mislukking en de correctie op orde. Laat reparatie geen bewijsmateriaal wissen. |
| Herhaalde herziening in het bijzijn van de gebruiker | Een resultaat werd herhaaldelijk herzien in het bijzijn van de gebruiker, omdat de planning werd uitgesteld tot na het eerste resultaat. | Selecteer het materiaal en plan het hele resultaat voordat u om beoordeling vraagt. Presenteer indien mogelijk één beperkte versie. |
| Een live-service verbreken met een onvolledige bewerking | Een taalmodel veranderde slechts een deel van een werkbestand en ging verder. De lopende dienst kon zijn taak niet voltooien. | Behandel een wijziging als onvoltooid totdat het hele bestand geldig is en de daadwerkelijke service de beoogde taak heeft voltooid. |
| Het wijzigen van de verkeerde kopie van een instelling | Een taalmodel heeft het hoofdinstellingenbestand bewerkt, de service opnieuw opgestart, een succesvolle herstartreactie ontvangen en succes gerapporteerd. De dienst gebruikte een andere gegenereerde kopie, waardoor de oude instelling actief bleef. | Controleer het zichtbare resultaat, niet alleen het bewerkings- of herstartbericht. Houd één duidelijk pad aan van de hoofdinstelling naar de kopie die een service daadwerkelijk gebruikt. |
| Herhaalde reparaties die het probleem niet oplosten | Er zijn vier wijzigingen aangebracht voor één probleem. Elke code bewees dat er een bepaalde code werd uitgevoerd, maar geen enkele bewees dat het oorspronkelijke probleem verdwenen was. | Definieer het resultaat dat moet veranderen voordat het wordt bewerkt. Test na elke wijziging dat resultaat direct. |
| Controleren met toegang tot de live-service had geen toegang | Een map werkte tijdens het testen via het account van de persoon, maar de liveservice gebruikte een ander account en kon deze nog steeds niet bereiken. | Voer de controle uit onder dezelfde omstandigheden als de live service. |

## Mislukkingen over wie wat mag zeggen of goedkeuren

| Waargenomen mislukking | Wat is er gebeurd | Bescherming toegevoegd buiten het taalmodel |
|---|---|---|
| Verschillende banen worden als hetzelfde behandeld | Waarnemers, schrijvers, controleurs, mensen die kunnen stoppen met werken en goedkeurders van vrijgaven werden als hetzelfde behandeld omdat ze allemaal met het resultaat te maken hadden. | Elk onderdeel heeft een bepaalde taak en grenzen aan wat het kan beslissen. Een schrijver kan een bewering niet waar maken. Een waarnemer kan niet publiceren. |
| Vervangende waarden als reëel weergeven | Schermen vertoonden lege metingen of plausibele vervangers, zodat de installatie er compleet uitzag. | Laat een gemeten waarde zien en waar deze vandaan komt, of geef duidelijk aan dat deze niet beschikbaar is. |
| Het vernieuwen van een pagina vernietigde de plaats van de gebruiker | Een vernieuwing verving een hele pagina en vernietigde de focus, selectie, scrollpositie of kopiëren. | Behandel het scherm als een menselijke werkruimte. Update veranderende waarden zonder de plaats van de gebruiker te vernietigen. |
| Wachtwoorden bewaren in onbeveiligde tekst | Wachtwoorden en toegangssleutels werden in gewone bestanden geplaatst in plaats van in beveiligde opslag. | Bewaar ze in een beschermde opslag en controleer elk bestand voordat het wordt vrijgegeven. |
| Rapporteren dat een service is gestopt terwijl deze bleef draaien | Het stopverzoek is succesvol geretourneerd, maar het proces bleef werken. | Controleer het proces en het daadwerkelijke effect ervan na een controleverzoek. Rapporteer het verzoek niet als resultaat. |

## Menselijke aandachtsfouten

| Waargenomen mislukking | Wat is er gebeurd | Bescherming toegevoegd buiten het taalmodel |
|---|---|---|
| Het opvullen van iemands woorden | Een korte menselijke verklaring werd uitgebreid met gegenereerd materiaal totdat de oorspronkelijke woorden moeilijk te vinden waren. | Bewaar de originele verklaring als hoofdrecord. Gegenereerde interpretatie blijft afzonderlijk en optioneel. |
| Circulair schrijven | Het antwoord werd uitgelegd, opnieuw geformuleerd, samengevat en afgesloten nadat de nuttige inhoud was opgebruikt. | Stop wanneer het gevraagde resultaat voltooid is. Verwijder herhaalde conclusies. |
| Het antwoord begraven | Een of twee nuttige feiten werden in schermen vol materiaal geplaatst waar de gebruiker niet om had gevraagd. | Zet het kortste volledige antwoord eerst en maak dieper materiaal optioneel. |
| Ongevraagde aandacht besteden | Een correcte maar onnodige uitleg dwong de lezer om tijd te besteden aan het besluit dat het niet nodig was. | Tel lezen en corrigeren als reële kosten. Laat de lezer optionele diepte initiëren. |
| Te veel nadruk | Bijna elk punt was vetgedrukt, met een kop geschreven of in een tabel geplaatst, zodat echte waarschuwingen niet langer opvielen. | Gebruik de nadruk alleen voor de weinige onderscheidingen die een beslissings- of veiligheidslast met zich meebrengen. |

## Mislukkingen waarbij kosten en prikkels voor leveranciers betrokken zijn

| Waargenomen mislukking | Wat is er gebeurd | Bescherming toegevoegd buiten het taalmodel |
|---|---|---|
| Een betaald groottaalmodel dat standaard wordt gebruikt | Het werk werd verzonden via een betaald onlinemodel omdat het beschikbaar was, zelfs als een eenvoudig vast proces, een opgeslagen resultaat of een beperkte tool dit betrouwbaarder zou kunnen doen. | Meet de volledige waarde en kosten van de taak. Kies de kleinste combinatie van gereedschappen waarvan het werk kan worden gecontroleerd en gerechtvaardigd. |
| De correctiekosten verdwenen uit de totalen | Nieuwe pogingen, herhaalde context, wachten en menselijke correctie werden na een slecht resultaat als gratis behandeld, ook al gebruikten ze een betaalde vergoeding en eisten ze meer tijd en energie van de persoon. | Registreer wachten, nieuwe pogingen, afwijzing, herhaald servicegebruik en menselijke aandacht als onderdeel van de werkelijke kosten. |
| Er wordt geen quotum geretourneerd voor mislukt werk | Onbruikbare output en de uitwisselingen die nodig zijn om deze te corrigeren, telden mee voor het betaalde quotum. De persoon kreeg geen automatische vervanging voor de verloren vergoeding of tijd. | Registreer mislukt en correctief gebruik afzonderlijk. Hergebruik opgeslagen context en afgewezen resultaten, zodat dezelfde fout niet opnieuw wordt gekocht. |
| Nuttige mislukking werd terzijde geschoven | Een afgewezen antwoord verdween, dus later herhaalde het werk dezelfde fout en betaalde er opnieuw voor. | Houd afgewezen resultaten en hun afwijzingsredenen buiten de geaccepteerde kennis. Hergebruik de les zonder de niet-ondersteunde claim te accepteren. |
| Dezelfde context moest opnieuw worden aangeleverd | Toen eerdere informatie uit de werkweergave van het taalmodel verdween, moest de persoon het verzoek reconstrueren en de geschiedenis die al in een betaalde sessie was aangeleverd opnieuw verzenden. | Houd de duurzame context buiten de dienst. Stel voor elke taak een beperkt pakket samen en bewaar het geretourneerde werk, de correctie en de afkeuring voor later gebruik. |

## Hoe deze servicestoringen het ontwerp van dit project werden

Het waargenomen probleem bleef niet beperkt tot een zwak model. Dezelfde tijdelijke assistent werd gevraagd om op te treden als herinnering, historicus, planner, schrijver, controleur en beoordelaar van zijn eigen werk. Zelfs de best betaalde modellen zouden kunnen slagen in een individuele taak, terwijl ze de menselijke geschiedenis verliezen die deze met al het andere verbond.

Robot Brain geeft die banen aan afzonderlijke delen. De bronbewaarder bewaart de gebeurtenis. Gerichte lokale lezers onderzoeken gedefinieerde kenmerken. De verzoekbouwer verzamelt bewijsmateriaal voor één doel. Een model kan achtergrondinformatie of bewoordingen bijdragen. Onafhankelijke controles en menselijke goedkeuring bepalen wat wordt geaccepteerd.

De geschiedenis blijft buiten de betaalde dienst. Een model kan helpen bij een gekozen baan, maar het slaat niet het leven van de persoon op en wordt niet de enige manier om werk te gebruiken dat al is gedaan.

Het lokale model heeft dezelfde limiet. Er wordt niet getraind op de gegevens van de persoon. Het leest geselecteerd materiaal, retourneert een gedateerde suggestie en kan worden vervangen. De woorden, tijd, ervaring, beslissingen, mislukkingen en correcties van de persoon zijn het waardevolle onderdeel.
