> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../08-What-Works-Today.md) | [Minden nyelv](../README.md)

# Mit csinál a jelenlegi megvalósítás

![Az ötletek, tesztek, kudarcok és bizonyított képességek egyértelműen elkülönülnek egymástól.](../../illustrations/evidence-implementation-gates.png)

Robot Brain szoftvert futtat a rögzített munka jelentésének megőrzésére és újjáépítésére. Ez nem egy chatbot-javaslat, és a jelenlegi megvalósítása nem nyelvi modell.

## Lehetőségek a jelenlegi megvalósításban

A rögzített futtatások azt mutatják, hogy a szoftver képes:

- megőrzi a befejezett beszélgetést anélkül, hogy összefoglalóval helyettesítené
- tartsa külön a személy szavait a modellválaszoktól és a későbbi értelmezésektől
- részletes megállapításokat készíteni a nyelvről, jelentésről, érvelésről, időről, emberi tapasztalatokról és értékekről
- az egyes megőrzött leleteket a beszélgetés mögötte lévő részhez kapcsolja
- megtartani a javításokat, a nézeteltéréseket, a sikertelen munkát és a megválaszolatlan kérdéseket
- adjon hozzá egy keltezett helyi általános ismeretek áttekintését az eredeti online modell meghívása nélkül
- összegyűjti a visszatartott hozzájárulásokat a kért rekonstrukcióhoz
- rögzítse, hogy mit ellenőriztek, utasítottak el, javítottak és fogadtak el
- cserélje ki a képernyőt vagy a résztvevő nyelvi modellt a mentett előzmények cseréje nélkül

Ezek a modellek körüli szoftver funkciói. Ezek nem olyan képességek, amelyekre igényt tartanakQwen,LibreChat, vagy egy online asszisztens.

## Mi történt a befejezett beszélgetés mérföldkövében

A tesztelt beszélgetést a személy üzeneteivel és az online modell válaszaival sorrendben mentettük.

A fókuszált helyi módszerek ezután külön rekordokat hoztak létre a cseréről. Munkájuk kiterjedt a nyelvre és a jelentésre, az érvelésre, a pszichológiai megfigyelésekre, a filozófiai megfigyelésekre, a kapcsolatokra és az idő múlásával kapcsolatos változásokra. Minden megőrzött hozzájárulás a forrásanyaghoz és az azt előállító módszerhez kötődött.

Ezek a részletes módszerek szándékosan nem hordozzák az általános célú modell széleskörű háttérismeretét. Egy kis helyiQwenmodell, szolgáljavLLM, elolvasta a kiválasztott anyagot, és dátumozott áttekintést adott hozzá. Feladata az volt, hogy hétköznapi hátteret biztosítson, amely összekapcsolta a különálló megállapításokat, és egészében érthetővé tette a cserét.

Qwennem tudta visszanyerni az eredeti modell rejtett gondolatait, edzéstörténetét vagy magánéleti belső állapotát. Az eredeti modell hasznos hozzájárulása már a mentett üzenetekben is jelen volt. A széleskörű háttérismereteket egy helyettesíthető helyi modell biztosította, mivel ez a tudás nem volt egyedi az eredeti szolgáltató számára.

## Mit jelent ennél a mérföldkőnél a „teljes”?

A szó az ehhez a futáshoz tartozó hozzájárulások karbantartott listájára utal. Minden forrásüzenet és minden hozzájárulás, amit a folyamat megtartott a rekonstrukcióhoz, újra megtalálható és összegyűjthető.

Ez nem jelenti azt, hogy egy modell teljes értelmezést adott. A megvalósulás az, hogy az átvett darabokat megőrizzük, forrás és módszer szerint elválasztjuk, és az eredeti online csere újraindítása nélkül rekonstruáljuk.

## Hogyan támasztják alá az állítást

A futtatás rögzíti, hogy mely alkatrészeket hajtották végre, mit kapott mindegyik, mit adtak vissza, mely hozzájárulásokat utasították el, és mely ellenőrzések mentek át. A rekonstrukciót a várható rekordok saját mentett listájához mérik.

Az alkatrésztesztet alkatrésztesztként írják le. A csatlakoztatott futás leírása összekapcsolt futás. A tervezett munka elkülönül a jelenlegi megvalósítástól.

A következő munka kiterjed a szélesebb körű független tesztelésre, több fajta irat támogatására, több nyelvre és kultúrára, tisztább áttekintési képernyőkre, valamint az eredmények olvasásával és javításával töltött idő jobb mérésére.
