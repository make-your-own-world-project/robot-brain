> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../README.md) | [Minden nyelv](../README.md)

# Tartsa a nyilvántartást. Cserélje ki a modellt.

![Egy személy nyilvántartása egy helyen marad, míg a különálló munkarészek korlátozott feladatokat kezelnek.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain olyan szoftver, amely megőrzi a hosszú távú emberi munka történetét és jelentését. Ez nem egy nyelvi modell, egy chatbot vagy egy szolgáltatás, amely minden kérdést továbbít egy modellnek.

A nagy nyelvi modellek kutathatnak, írhatnak, magyarázhatnak, és segíthetnek megoldani a nehéz problémákat. A köréjük épített fizetős szolgáltatások továbbra is ideiglenes munkaterületek. Lerövidíthetik a hosszú beszélgetést, elveszíthetik a korábbi utasításokat, elválaszthatják a következtetéseket a bizonyítékaiktól, és úgy folytathatják az írást, mintha a hiányzó történelem még mindig jelen lenne. Ezután egy személy több időt és fizetett használatot fordít a már biztosított környezet újraépítésére.

Ez a szoftver megváltoztatja azt, ahol a maradandó érték él. A személy beszélgetései, dokumentumai, döntései, sikertelen próbálkozásai, javításai és megválaszolatlan kérdései a személy által kezelt nyilvántartásokban maradnak. A helyi programok megvizsgálhatják ezeket a rekordokat. A nyelvi modell segíthet egy kiválasztott munkában, de hozzájárulása dátumozott, áttekinthető munkaként jelenik meg a rekordban. A modell ezután cserélhető anélkül, hogy az előzményeket magával vinné.

[Olvassa el ezt a dokumentációt egy másik nyelven.](../README.md)

## A különbség egy nézetben

| Kereskedelmi nyelvi mintaszolgáltatás | Robot Brain |
|---|---|
| Választ ad a jelenleg munkanézetben lévő anyagból. | Megtartja a teljes forrást és az előzményeket körülötte. |
| A munka növekedésével lerövidítheti vagy elveszítheti a korábbi beszélgetést. | Minden modellen kívül elmenti a beszélgetéseket, így azok újra felhasználhatók. |
| Egyesíti a sok forrásból tanult tudást anélkül, hogy teljes út vezetne vissza az egyes forrásokhoz és körülményeihez. | Minden ismert forrást, későbbi megtalálást, javítást és nézeteltérést külön rekordként vezet. |
| Egy cserében tud írni, keresni, megtervezni és megítélni saját válaszát. | Mentést, keresést, elemzést, írást, ellenőrzést és jóváhagyást ad a különálló részeknek korlátozott jogosultsággal. |
| Szabályozza a modellt, a szolgáltatási szabályokat, a használati korlátokat és a termékmódosításokat. | A maradandó feljegyzést a személy ellenőrzése alatt hagyja. |
| Sikertelen próbálkozásokért és korrekciós cserékért, valamint hasznos munkáért fizetik. | Megtartja a hibákat és a javításokat, így a leckéket nem kell újra megvásárolni. |

Robot Brain helyi vagy online nyelvi modellt hívhat. Ettől még nem lesz modellproxy. Megőrizheti, keresheti, összehasonlíthatja, rendszerezheti és újraépítheti a korábbi munkákat anélkül, hogy meghívná az eredeti beszélgetésben részt vevő modellt. Ha egy modell hasznos, a kérés egy lépés egy nagyobb folyamatban, amely ettől a modelltől függetlenül létezik.

## Miért épült ez

A fejlesztés során elérhető legerősebben fizetett általános célú modellek a hosszú munka képes, de megbízhatatlan letéteményesei voltak.

A rögzített hibák között szerepelt az elveszett utasítások, hiányzó bizonyítékok, feltalált kapcsolatok, idő előtti befejezési állítások, nem kívánt változtatások és a működő fájlok sérülése. A hibák kijavítása több kérést, több vizsgálatot, több kifizetett juttatást, és több időt és energiát igényelt. A szervizek nem térítették vissza automatikusan a használhatatlan munkára elköltött használatot, illetve a javításhoz szükséges cseréket.

A probléma nagyobb volt, mint bármelyik rossz válasz. Egy ideiglenes szöveggenerátort kértek fel emlékező, történész, kutató, író, ellenőrző és végső bíró szerepére. A modellváltás nem változtatott ezen az elrendezésen.

Robot Brain egy másik elrendezés köré épült: először tartsa meg az emberi nyilvántartást, hagyja, hogy több cserélhető alkatrész járuljon hozzá, és kérjen bizonyítékot a generáló modellen kívülre, mielőtt fontos munkát elfogadna.

## Amit egy képzett modell nem tud megtartani

Egy nagy nyelvi modell az emberi munka hatalmas gyűjteményéből tanul mintákat. Ezek a minták hasznossá teszik a modellt, de a modell nem az azt formáló teljes alkotások könyvtára.

A modellben a könyvek, cikkek, beszélgetések, fordítások, közösségek, címkék és emberi visszajelzések hatásai keverednek. A modell általában nem tudja megmutatni, hogy egy adott mondatot mely források alakítottak. Nem állíthatja vissza minden szerző célját, közönségét, bizonyítékát, nézeteltérését, későbbi javítását vagy hiányzó nézőpontját.

Ez még akkor is jelentésvesztéssel jár, ha az eredeti mű máshol még létezik. A modell megőrzi a munka hasznosságát, miközben elveti az emberi környezethez vezető megbízható utat.

Ugyanez a probléma a szokásos használat során jelentkezik. A végső válasz a jelentést adó beszélgetés lerövidítése után maradhat fenn. A következtetés megmarad, de a sikertelen próbálkozások, a bizonytalanság és a mögötte meghúzódó okok eltűnnek a modell működési nézetéből.

Ez a projekt nem ad választ erre a problémára azáltal, hogy egy másik modellt tanít az ember életére. A személyes történelem olvasható és nyomon követhető marad, ahelyett, hogy egy másik képzett modellbe keveredne. A modellek kiválasztott rekordokkal dolgoznak; nem válnak a rekordokká.

## Mit csinál az egyes részek

A működő szoftver szétválasztja azokat a munkákat, amelyeket egy chat-szolgáltatás gyakran egyetlen tevékenységnek tesz ki:

1. **A forrás őrzője elmenti a történteket.** Megőrzi a beszélgetést, dokumentumot, képet vagy egyéb anyagot anélkül, hogy összefoglalóval helyettesítené.
2. **A kereshető másolatok megkönnyítik a forrás megtalálását.** A másolt szöveg, leírások és indexek a változatlan forrásra mutatnak vissza, és újraépíthetők.
3. **A koncentrált helyi olvasók konkrét jellemzőket vizsgálnak.** Külön módszerek vizsgálják a nyelvet, a kijelentéseket, a kapcsolatokat, az érvelést, az időt, az emberi tapasztalatokat és az értékeket. Mindegyik csak a saját megállapításairól és a mögöttük rejlő szövegrészekről számol be.
4. **Az előzmények nyilvántartása láthatóvá teszi a változásokat.** Az új megállapítások, javítások, nézeteltérések, sikertelen próbálkozások és nyitott kérdések a korábbi események átírása nélkül kerülnek hozzáadásra.
5. **A kéréskészítő összegyűjti, mire van szüksége egy munkának.** Kiválasztja a releváns forrásokat és megállapításokat, és rögzíti, hogy mi került bele vagy mi maradt ki.
6. **A nyelvi modell korlátozott segítséget jelenthet.** A helyi modell széles körű hátteret biztosíthat. Egy online modell segíthet a nehéz kutatásban vagy írásban. Bármelyik válasz keltezett hozzájárulás marad, amely ellenőrizhető, elutasítható vagy helyettesíthető.
7. **Külön ellenőrzések vetik össze az eredményt a kéréssel és bizonyítékkal.** A választ író modell nem nyilváníthatja a saját munkáját elfogadottnak.
8. **A képernyő lehetővé teszi a szoftver használatát.** A mellékeltLibreChatA villa az egyik ilyen képernyő. A csere nem helyettesíti a rekordokat vagy a többi működő alkatrészt.

Egyetlen részt sem mutatnak be mindent tudó asszisztensként. A korlátozott munkájuk miatt mindegyik alkatrész cserélhető.

## Egy befejezett beszélgetés ismét hasznossá tétele

A befejezett beszélgetés tartalmazza a személy kérését, a nyelvi modell tényleges válaszait, a megkísérelt munkát, a kudarcokat, a javításokat és azt a pontot, ahol a csere véget ért. Ezek az üzenetek megőrzik azt, amit az eredeti modell hozzájárult anélkül, hogy a modellnek később magyarázatot kellene adnia.

A koncentrált helyi olvasók több oldalról is megvizsgálják az elmentett üzenetváltást. Részletes mintákat és kapcsolatokat találhatnak anélkül, hogy széles körű világismeretre támaszkodnának. Külön megállapításaik továbbra is a beszélgetés pontos részeihez kapcsolódnak.

Ezeknek a megállapításoknak még mindig szükségük lehet a szokásos háttérismeretekre, mielőtt egyértelmű beszámolót alkotnának. Ehhez a korlátozott lépéshez egy kicsiQwenmodell helyileg fut átvLLM. Dátumozott áttekintést ad hozzá, amely segít a részletes megállapítások összekapcsolásában, és elmagyarázza, mit ért el a csere.

Qwennem állítja vissza az online modell rejtett gondolatait vagy edzéstörténetét. Széleskörű háttérismereteket biztosít, amelyek nem egyediek az eredeti modellre. Az eredeti modell hasznos hozzájárulását már az általa készített szavak is megőrzik.

AQwenaz áttekintést a forrás és a korábbi leletek mellett tároljuk. Javítható vagy cserélhető. Az eredeti beszélgetés és a részletes helyi elemzés változatlan marad.

## Mi működik most

A jelenlegi implementáció képes megőrizni a befejezett beszélgetést, megvizsgálni külön helyi módszerekkel, hozzáadni egy helyi általános ismereteket, és minden megőrzött hozzájárulást egy rekordba gyűjteni, amely később újraépíthető.

Korlátozott kérést is készíthet egy online modellre, ha a külső segítség hasznos. Ez a szolgáltatás csak a kiválasztott anyagot kapja meg. Válasza visszatér a helyi nyilvántartásba, ahol ellenőrzések és emberi jóváhagyás: nem a modell: döntik el, hogy mit őrizzünk meg.

Ez a központi vívmány: az egykor egy ideiglenes beszélgetésen alapuló munka hasznos maradhat, miután a csevegőképernyő, a modell és a szolgáltató eltűnt.

## Olvassa el a teljes magyarázatot

- [Miért nem tudják megőrizni a teljes történetet a nagy nyelvi modellek?](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Mit csinálnak az egyes részek: és amit egyetlen modell sem vezérel](02-A-Lasting-Record-Outside-the-Model.md)
- [Tartsa meg a javítást a hiba törlése nélkül](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Kövesse az állítást a bizonyítékokhoz](04-How-Every-Claim-Can-Be-Checked.md)
- [A próza megírása előtt készítse el a dokumentumot](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Magyarázza el ugyanazt az igazságot a különböző olvasóknak](06-One-Meaning-Different-Readers.md)
- [Tartsa a személyes előzményeket a személy ellenőrzése alatt](07-Privacy-and-Control-Stay-With-People.md)
- [Mit csinál a jelenlegi megvalósítás](08-What-Works-Today.md)
- [Miért merít a design sok területről](09-How-Research-Strengthens-the-System.md)
- [Segítség személyes iratok átadása nélkül](11-Contribute-Without-Giving-Up-Control.md)
- [A dokumentumokban használt szavak](12-A-Short-Guide-to-Key-Terms.md)
- [Kövessen egy kérést a munkarészeken keresztül](13-The-Parts-Running-Today.md)
- [Használjon nyelvi modellt a munkához, ne memóriaként](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [A fizetett nyelvi modellszolgáltatásoknál megfigyelt hibák: és az ezekhez vezető biztosítékok](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Tanulságok, amelyek megváltoztatták a tervezést](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Nyilvános használatra, hitelre vonatkozó és adatvédelmi megjegyzések](18-Use-Attribution-and-Limits.md)
- [Hogyan lesz egy befejezett beszélgetésből maradandó tudás](19-What-the-System-Accomplishes.md)
- [Mi jön ezután](20-Where-the-System-Goes-Next.md)

## Hitelek, források és jogok

- [Mi segített ennek a műnek a kialakításában](10-What-Helped-Shape-This-Work.md)
- [Kutatás a tervezés mögött](14-Sources-Behind-the-Design.md)
- [Források, licencek és nyilvános ellenőrzések](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Engedély

A projekt eredeti írása, diagramjai és illusztrációi a szervezet alatt érhetők el[Creative Commons Nevezd meg! 4.0 nemzetközi licenc](../../LICENSE.md), kivéve, ha egy dokumentum eltérő feltételeket tartalmaz. A mások által készített anyag fenntartja saját jogait és feltételeit.

## Függetlenség és magánélet

Ez egy független személyes projekt, amelyet személyes időre, felszerelésekre, számlákra és fizetős szolgáltatásokra fejlesztettek ki. Ebben egyetlen munkáltató sem vett részt. Bármely személy, munkáltató, intézmény, modellszolgáltató, kutatócsoport, közös szabály vagy külső projekt megemlítése nem jelent részvételt, jóváhagyást, partnerséget vagy jóváhagyást.

A nyilvános közzététel nem tartalmazza a magánfeljegyzéseket, az azonosító adatokat, a jelszavakat, a privát csatlakozási információkat, a munkáltatói információkat és a magánszolgáltatások eléréséhez szükséges utasításokat. A modellhibák leírása a rögzített viselkedésre és annak hatására korlátozódik; nem állítanak nyilvánosságra nem hozott okokat vagy indítékokat. A dokumentumok nem szakmai tanácsok vagy eredmények ígérete.

![Útvonal a szolgáltató által vezérelt memóriától a feljegyzések felé, amelyek az érintett személyeknél maradnak.](../../illustrations/open-door-human-future.png)
