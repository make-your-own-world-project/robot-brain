> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../14-Sources-Behind-the-Design.md) | [Minden nyelv](../README.md)

# Kutatás a tervezés mögött

![A különböző kutatási hagyományok korlátozott módszerekhez járulnak hozzá, miközben megtartják saját történetüket.](../../illustrations/academic-framework-lineages.png)

Ez az oldal azoknak az olvasóknak szól, akik kutatási nyomvonalat keresnek. A fő magyarázat nem igényli.

A lista olyan ötleteket és eszközöket tartalmaz, amelyeket használtak, teszteltek, összehasonlítottak, elutasítottak vagy egyszerűen tanulmányoztak. Ezek a kapcsolatok nem ugyanazok. A forrás felsorolása nem jelenti azt, hogy a szerzők részt vettek vagy támogatták a projektet.

## A források és a változások időbeli megőrzése

- A forrástörténeti kutatás és a változó információk határozták meg azt a módot, ahogyan az iratok megőrzik, honnan származnak, mikor alkalmazták, és mi váltotta fel később.
- [Graphiti](https://github.com/getzep/graphiti)Az idő múlásával változó kapcsolatok rögzítésének egyik megközelítéseként vizsgálták.
- A kialakult változásrögzítési módszerek azt a szabályt vezérelték, hogy az aktuális összefoglaló nem helyettesítheti a mögötte lévő forrást.

Ezek az ötletek segítenek megőrizni azt az utat, amelyet egy új modellválasz vagy átírt összefoglaló egyébként elrejtene.

## Az igények, a támogatás és a nézeteltérés szétválasztása

- [Mann és Thompson retorikai struktúraelmélete](https://aclanthology.org/J88-2003/)neveket adott a dokumentum részei közötti kapcsolatokra, például egy fő pontra és annak magyarázatára.
- [Walton, Reed és Macagno érvelési sémái](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2)célzott kérdéseket adott a támogatás és a következtetések vizsgálatához.
- [oAMF](https://github.com/arg-tech/oAMF)és az xAIF megközelítéseket biztosított a követelések és azok kapcsolatainak rögzítésére.
- [PropBank](https://aclanthology.org/J05-1004/)befolyásolta az állítások és a bennük lévő szerepek rögzítését.
- [RSTformer](https://aclanthology.org/2023.acl-long.306/)és a kapcsolódó munkákat teszteltük a dokumentumszerkezet megtalálására. Nem használták őket a jelentés vagy az érvelés végső bíráiként.

Ezek a források segítenek megakadályozni, hogy egyetlen csiszolt bekezdés elrejtse a különbséget egy követelés, annak alátámasztása, helyesbítése és egyet nem értés között.

## Hasznos anyagok keresése anélkül, hogy összetévesztené a hasonlóságot az igazsággal

- [Carbonell és Goldstein maximális marginális relevanciája](https://aclanthology.org/X98-1025/)tájékozott módszerek a relevancia és az ismétlés közötti egyensúly megteremtésére.
- [Lin és Bilmes a szubmoduláris dokumentum-összegzésről](https://aclanthology.org/P11-1052/)tájékozott módszerek egy hasznos átjárócsoport kiválasztására egy mérethatáron belül.
- [FActScore](https://aclanthology.org/2023.emnlp-main.741/)tájékozott kérdéseket tesz fel arra vonatkozóan, hogy pontosan hogyan támasztják alá az állításokat.
- A rögzített kapcsolatokból épített összefoglalók kutatása olyan teszteket eredményezett, amelyek lerövidítik az anyagot anélkül, hogy elvetnék a lényeges összefüggéseket.

A keresés és az összegzés a bizonyíték felé irányíthatja az embert. Nem tudják eldönteni, hogy valami miért számít, és nem tudnak igazzá tenni egy részt.

## Tervezés írás előtt

- [Reiter és Dale természetes nyelvgenerációs rendszereket épít](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD)befolyásolta a tartalomválasztás, a tervezés és a mondatírás szétválasztását.
- [Lépésről lépésre NLG](https://aclanthology.org/N19-1236/)és[adat-szöveg makró tervezés](https://aclanthology.org/D19-1318/)a dokumentumtervezési módszerek megalapozott összehasonlítása.
- [EgyszerűNLG](https://github.com/simplenlg/simplenlg),[Nyelvtani keretrendszer](https://www.grammaticalframework.org/), és[OpenCCG](https://github.com/OpenCCG/openccg)úgy értékelték, mint a tervezett tartalmat mondatokká alakítani.
- Az ismert és új információk, a mondatok közötti összefüggések, a kommunikáció fajtái és a dokumentumformák kutatása befolyásolta a magyarázatok sorrendjét a különböző olvasók számára.

Ez a munka együtt támogatja a dokumentum megtervezését, mielőtt egy nyelvi modellt kérne meg annak megírására.

## Az emberi megértés és az olvasás költsége

- Az arra vonatkozó kutatás, hogy az emberek hogyan építik fel a megértést és kezelik a mentális erőfeszítéseket, a hosszúság, az új fogalmak és az ismétlés korlátaira támaszkodtak.
- [Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270),[TAACO](https://www.linguisticanalysistools.org/taaco.html),[DocuScope](https://docuscope.github.io/), TextDescriptives és LFTK értékelték az írás összehasonlításának módjait.
- Az önmeghatározás elmélete, az élet értelmével kapcsolatos kutatások és az értékek kutatása korlátozott kérdéseket adott a személyes jelentéssel kapcsolatban. Nem támogatják az automatikus diagnózist vagy az emberek széles profilját.

## Korlátozott szerkesztőeszközök

[LaserTagger](https://github.com/google-research/lasertagger),[GECToR](https://github.com/grammarly/gector), és[EditT5](https://aclanthology.org/2022.findings-acl.260/)olyan szerkesztési feladatokat értékeltek, amelyek korlátozzák, hogy mennyi új szöveget lehet bevezetni.

## Jogok és teljesebb nyilvántartás

Ez a dokumentáció nem tartalmazza a megnevezett könyvek, iratok, programok, betanított modellfájlok vagy kutatási gyűjtemények másolatait.[Források, licencek és adatvédelem](../../SOURCES-LICENSES-AND-PRIVACY.md)rögzíti a ténylegesen használt vagy tesztelt programok és betanított fájlok licenc felülvizsgálatát.

A magánkutatási nyilvántartás több papírt, nyilvános szabványt, eszközt, gyűjteményt, kulturális művet, elutasított megközelítést és teszteredményt tartalmaz. A közhitelezés növekedhet, ahogy ezeket a feljegyzéseket ellenőrizzük, beleértve az ötleteket is, amelyek főleg azzal segítettek, hogy megmutatták, mi nem működött.
