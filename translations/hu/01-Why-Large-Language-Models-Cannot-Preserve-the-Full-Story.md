> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Minden nyelv](../README.md)

# Miért nem tudják megőrizni a teljes történetet a nagy nyelvi modellek?

![Az elmentett darabok elveszítik értéküket, ha forrásaik, kapcsolataik és történelmük elválik egymástól.](../../illustrations/ordinary-storage-loses-context.png)

A projekt felépítése során használt legerősebben fizetett nyelvi modellek lenyűgöző munkát végezhetnek. Írhattak, kutathattak, magyarázhattak, és segíthettek nehéz problémák megoldásában. Még mindig nem tudták megőrizni a teljes történetet egy hosszú projekt mögött.

Egy későbbi válasz emlékezhet a következtetésre, de elveszíti a sikertelen kísérleteket, korrekciókat és bizonyítékokat, amelyek ahhoz vezettek. A korábbi utasítások eltűnhetnek, ha a beszélgetés túl hosszú lett. A modell úgy folytatta az írást, mintha semmi fontos nem veszett volna el.

Komoly probléma, ha a hiányzó történelem valakinek az idejét, tudását vagy tapasztalatát reprezentálja.

## A fájlok nem elegendőek

Egy mappában minden feljegyzés, beszélgetés, kép és feladat elfér, miközben elveszíti az őket összekötő történetet.

Hónapokkal később egy személynek tudnia kell:

- mi indította el a munkát
- mely ötleteket vették figyelembe
- miért nem sikerült az egyik kísérlet
- milyen bizonyítékok változtatták meg a tervet
- melyik következtetés aktuális
- ami még ismeretlen
- miért számít most egy régi jegyzet

A keresés hasonló szavakkal rendelkező fájlokat találhat. Nem tud megbízható választ adni ezekre a kérdésekre. Egy nagyobb halom fájl nyelvi modellre küldése sem hoz létre állandó memóriát. A szolgáltatás látja, hogy mi lett kiválasztva az adott kéréshez. Amikor a kérés véget ér, a hasznos kapcsolatok ismét eltűnhetnek.

## A képzés is elveszti az eredeti beállítást

A nyelvi modellek emberi munka hatalmas gyűjteményéből tanulnak mintákat. Ez teszi őket hasznossá. Ez az oka annak is, hogy nem működhetnek hűséges archívumként mindannak, ami formálta őket.

Egy könyvből, cikkből, beszélgetésből, fordításból vagy közösségből származó ötletek keverednek sok más ötleteivel. A modell nem tartja érintetlenül az egyes műveket a szerzővel, céllal, közönséggel, bizonyítékokkal, nézeteltérésekkel és későbbi javításokkal.

Lehet, hogy az eredeti mű még létezik valahol máshol. A szolgáltató külön másolatokat is őrizhet. Az itt leírt veszteség a betanított modellen belül történik: megtartja a munkából a hasznos hatást, de nem tudja újjáépíteni körülötte a teljes emberi jelentést.

Egy mondat megismétlése nem egyenlő a jelentés megőrzésével. A modell reprodukálhat ismerős szavakat anélkül, hogy tudná, miért írták őket, milyen helyzetet írt le, kinek a nézete hiányzott, vagy mi történt később.

## A hiányzó történelem elfogultságot is rejt

Nincs az egész világtól tanult nyelvi modell.

Ismerete tükrözi, hogy mit írtak le, őriztek meg, gyűjtöttek, fordítottak, engedélyeztek, címkéztek és kiválasztottak. Azt is tükrözi, ami hiányzott. Egyes nyelveken és közösségeken sokkal több publikált anyag található, mint másokon. Az archívumok gyakrabban őrzik meg az erős intézmények nézeteit, mint a magán-, helyi vagy szóbeli ismereteket.

A modellt építő emberek több döntést hoznak arról, hogy mit távolítanak el, jutalmaznak meg, mit tegyünk el, vagy mit kezeljenek jó válaszként. A termékszabályok újabb réteget adnak hozzá. A kész válasz mindezeket a hatásokat hordozhatja anélkül, hogy megmutatná, melyik érintett egy adott mondatot.

Egy új kérés során talált idézet nem fedi fel ezt a teljes előzményt. A kéréshez használt vagy megnevezett forrást mutatja, nem mindent, ami a modellt a téma értelmezésére tanította.

## Amit ez a projekt megtart helyette

Robot Brain megőrzi a forrást, mielőtt bármilyen modelltől segítséget kérne annak értelmezéséhez. A forrás nem változik összefoglalás, javítás vagy új értelmezés hozzáadásakor.

A későbbi munkák dátummal és a megfelelő szövegrészre visszamutató hivatkozással kerülnek elmentésre. A sikertelen kísérlet látható maradhat. A helyesbített következtetés rámutathat arra a bizonyítékra, amely megváltoztatta azt. Ha a változás oka ismeretlen, a jegyzőkönyv ezt írja.

Ha valakinek válaszra vagy dokumentumra van szüksége, a kéréskészítő összegyűjti az előzményeknek a feladathoz szükséges részét. Az eredmény rövidebb is lehet, mint a teljes rekord anélkül, hogy úgy tesz, mintha lecserélné.

Egy nyelvi modell segíthet ebben az eredményben. Nem törölheti ki a forrásokat, nem írhatja át a múltat, és nem tehet egy nem alátámasztott találgatást az elfogadott rekord részévé.

## A gyakorlati teszt

Hasznos eredmény alapján az olvasó négy kérdésre válaszolhat:

1. Mi történt?
2. Milyen bizonyítékok támasztják alá ezt a beszámolót?
3. Mi változott, kudarcot vallott vagy vitatott?
4. Mi az, ami még ismeretlen?

Ha a feljegyzés nem tud válaszolni ezekre a kérdésekre, a csiszolt nyelvezet nem rejtheti el a hiányt.
