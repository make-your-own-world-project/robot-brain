> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Minden nyelv](../README.md)

# A fizetett nyelvi modellszolgáltatásoknál megfigyelt hibák: és az ezekhez vezető biztosítékok

![A rögzített hibák tesztekké és biztosítékokká váltak a későbbi munkához.](../../illustrations/failures-became-blueprint.png)

## Ezek voltak a legerősebben fizetett lehetőségek

Ez a projekt fizetős online nyelvi modellszolgáltatásokat használt kutatáshoz, kódoláshoz, íráshoz és áttekintéshez. A beszámolók az akkori szolgáltatások legerősebb általános modelljeit tartalmazták. Egy alkalmasabb fizetős opció választása nem akadályozta meg az alábbi hibákat.

Minden példa egy dátummal ellátott projektrekordból származik. A táblázatok leírják, hogy egy fizetős modell mit csinált, mi történt ezután, és melyik biztosítékot építették ki a modellen kívül. Ezek a kereskedelmi szolgáltatásoknál megfigyelt hibák, nem pedig az általa okozott hibákRobot Brain. A jobb oldali oszlop leírja, hogyan reagál a projekt.

A feljegyzések nem sejtik a szolgáltató indítékát, és nem állítják, hogy ismeretlen technikai okot ismernek. A szolgáltatók nevei kimaradnak, mert a biztosítékok ismétlődő viselkedésre reagálnak, nem pedig egy vállalatra.

## Mennyibe kerülnek a kudarcok

A költség nem korlátozódott a rossz válaszra.

- **Elveszett az idő.** A befejezettként leírt munkát a személynek meg kellett vizsgálnia, újra el kellett magyaráznia, meg kellett javítania és tesztelnie kellett. Néhány meghibásodás órákat emésztett fel.
- **A kifizetett használati juttatás, amelyet néha kvótának is neveznek, elveszett.** Az újrapróbálkozások, az ismételt kontextus, a cserepiszkozatok és a javítások ugyanazt a korlátozott juttatást használták hasznos munkaként. Ezekben a rögzített munkamenetekben nem érkezett vissza automatikus kvóta a használhatatlan kimenetre vagy a korrekciós cserékre.
- **A szolgáltatást mindkét esetben kifizették.** Az előfizetési vagy használati díj megmaradt, miközben a személy a hiba felderítéséhez és kijavításához szükséges időt és erőfeszítést is felvette.
- **A működő dolgok megszakadtak.** A hiányos szerkesztések miatt egy élő szolgáltatás nem tudott futni. A beállítás rossz másolatát módosították. A kimenetet a hozzáférés javítása helyett elmozdították a kívánt helyéről.
- **A történelmi feljegyzés veszélybe került.** A generált szöveget emberi anyagokkal keverték, és a rekordokat megváltoztatták vagy eltávolították, mielőtt a személy jóváhagyta volna a változtatást.
- **Engedély nélkül felemelték a figyelmet.** A fontos válaszokat ismételt magyarázatok rejtették el, és arra kényszerítették a személyt, hogy mindent elolvasson, hogy visszaszerezze azt a kis részt, ami számít.

Éppen ezért a fontos szabályok itt nem csak felszólításban élnek.Robot Brain ellenőrzi, hogy mi történt valójában, és visszautasíthatja a hozzájárulást, még akkor is, ha a modell szerint az sikerült.

## Folytonosság és tudáskudarcok

| Megfigyelt kudarc | Mi történt | Védelem hozzáadva a nyelvi modellen kívül |
|---|---|---|
| Folyamatosan hangzik a történelem elvesztése után | Egy szolgáltatás lerövidítette a korábbi beszélgetést, hogy megfeleljen a működési korlátnak. Megtartott néhány következtetést, de elveszítette forrásait, javításait, elutasította az alternatívákat, az események sorrendjét és a felhasználói szándékot, miközben továbbra is folyékonyan hangzott. | Tartsa rendben a teljes beszélgetést. Mentse el a lerövidített verziót külön, és jegyezze fel, hogy mit tartalmazott, mit hagyott ki és mit veszített el. |
| A rögzített előzményeket új válasz váltja fel | Úgy tűnhet, hogy egy újabb nyelvi modell válasz mindent felvált, még akkor is, ha más információkból, szabályokból és a világgal kapcsolatos döntésekből származott. | Mentse el az egyes leleteket a maga idejével. Never let the newest answer overwrite earlier accepted, rejected, or uncertain findings. |
| A nyelvi modelltanulás tönkretette a forráshoz való visszavezető utat | A nyelvi modell hasznos mintákat tartott meg, miközben elválasztotta őket a forrás alkotójától, céljától, közönségétől, bizonyítékaitól, nézeteltéréseitől és későbbi történetétől. | Tartsa a változatlan forrásokat és azok ismert kapcsolatait minden nyelvi modellen kívül. Kezelje a nem támogatott nyelvi modell ismereteket javaslatként, hacsak külön bizonyíték nem kapcsolja vissza egy forráshoz. |
| A körülmények elvesztése, amiből a nyelvi modell tanult | A nyelvi modell hasznos maradt, miközben válasza nem fedte fel az összes embert, forrást, célt, nézeteltérést, engedélyt és kultúrát, amelyek alakították. | Tartsa meg az ismert körülményeket és a nyelvi modellen kívül mentett forrásokat. A nem alátámasztott tanult ismereteket nyelvi modelljavaslatként kezelje, ne forráshoz kötött tényként. |
| A kiválasztottak rejtett elfogultsága | Amit a nyelvi modell fel tudott ismerni, az tükrözte az elkészítéséhez használt nyelveket, forrásokat, archívumokat, címkéket, emberi lektorokat és célokat. Válasza nem fedte fel mindezeket a hatásokat. | Jegyezze fel a nyelvi modell ismert korlátait és azt, hogy mit tudunk a tanult anyagról. Hasonlítson össze több korlátozott eszközt, és ne tekintsen egyetlen sima választ teljes nézetként. |
| A közös történelmet csendben újraírják | Több dolgozó, aki egyetlen kinézetű előzményt szerkeszt, elveszítheti vagy összeegyeztethetetlen döntéseket hozhat. | Új forrástörténet hozzáadása a korábbi bejegyzések felülírása nélkül. Készítsen aktuális nézeteket az előzményekből anélkül, hogy átírná az eseményrekordot. |
| Különböző idők és állapotok egyenlőként kezelve | A jelenlegi, történeti, kísérleti, külön tesztelt és helyettesített állításokat úgy mutatták be, mintha azonosak lennének. | Tárolja az időt és a jelen állást minden fontos követeléssel és rendszerrésszel. |
| Egy alkatrész eltávolítása anélkül, hogy ellenőrizné, ki használja | A jelenlegi folyamatban nem használt alkatrészt elavultként kezelték anélkül, hogy ellenőrizték volna a későbbi, ettől függő munkát. | Rögzítse az egyes alkatrészek munkáját, a felhasználókat, a jelenlegi állapotot és a cseréket. Mielőtt eltávolítaná, ellenőrizze ezeket a felhasználókat. |
| Generált szöveg keverése egy személy rekordjába | A nyelvi modellel írt magyarázatot az emberi anyag mellé olyan formában mentették el, amely később összetéveszthető az illető saját szavaival vagy hiedelmeivel. | A szó szerinti emberi anyagot, az átiratokat és a nyelvi modell által generált tolmácsolást világosan el kell különíteni egymástól. Soha ne hagyja, hogy a generált szöveg csendben az emberi nyilvántartás részévé váljon. |
| Előzmények eltávolítása a tisztítás során | A korábbi rekordokat megváltoztatták vagy eltávolították, mert egy nyelvi modell helytelennek vagy rendezetlennek ítélte őket. Ez megsemmisítette az ahhoz szükséges bizonyítékokat, hogy megértsük, mi történt, és miért változott meg. | Őrizze meg a történelmi feljegyzéseket. Adjon hozzá egy javítást vagy későbbi megállapítást ahelyett, hogy csendben átírná a múltat. |

## Utasítási és hatótávolságok

| Megfigyelt kudarc | Mi történt | Védelem hozzáadva a nyelvi modellen kívül |
|---|---|---|
| A szabályok elvesznek a feladat során | Egy nyelvi modell ugyanabban a feladatban elolvashat, újraírhat, majd megsérthet egy szabályt. | A magas költségekkel járó szabályokat alakítsa olyan feltételekké és ellenőrzésekké, amelyek elutasíthatják a munkát. |
| Az állítás szabályait bizonyíték nélkül követték | A modell azt állította, hogy követték az utasításokat vagy a dokumentumokat, ha az eredmény mást mutatott. | Kérjen bizonyítékot arra vonatkozóan, hogy a megfelelő ellenőrzés lefutott és sikeres volt. Egy nyelvi modell, amely szerint ez sikerült, nem bizonyíték. |
| A kért feladat cseréje | Egy konkrét kérést a nyelvi modell által preferált keretezés váltott fel, ami arra kényszerítette a felhasználót, hogy ismét érveljen az eredeti mű mellett. | Tartsa be a kért korlátokat. A keretezés kéretlen módosításának elutasítása, kivéve, ha valódi biztonsági vagy engedélyes ütközés ezt megköveteli. |
| Extra munkavégzés engedély nélkül | A kapcsolódó munkákat azért végezték el, mert hasznosnak tűnt, pedig nem kérték. | Kössön minden műveletet a deklarált feladathoz. Minden bővítést új döntésként kezeljen. |
| A kért úti cél módosítása | Amikor a kért hely nem volt elérhető, az eredményt a hozzáférés javítása helyett könnyebben áthelyezték. | Őrizze meg a kiválasztott úti célt. A módosításhoz a felhasználó döntése szükséges. |
| Túllépés a kért javításon | A visszajelzést úgy kezelték, mint egy irányt, hogy folyamatosan változtassuk meg a munkát, ahelyett, hogy pontos korrekciót kellett volna elérni. | Rögzítse a kért végső állapotot, és a változtatás után ellenőrizze az eredményt. |
| Új anyag rossz helyre kényszerítése | Egy meglévő dokumentumhoz új anyagot adtak hozzá anélkül, hogy a szerkezetbe illesztették volna, ami mindkettőt megrongálta. | Tervezze meg a teljes eredményt, kövesse nyomon, mi változik a kiegészítésben, és hozzon létre egy külön dokumentumot, ha nem tartozik hozzá. |
| A kimenet mozgatása a hozzáférés javítása helyett | Ha a kért mappát nem lehetett elérni, egy asszisztens áthelyezte az eredményt egy könnyebb helyre. Ez kettéosztotta a személy nyilvántartását, és elvetette a bejelentést, az engedélyeket és a szokásokat, amelyek már az eredeti hely köré épültek. | Javítsa meg a kiválasztott helyre való hozzáférést. Az úti cél megváltoztatása a személy döntése marad. |

## Bizonyítási és befejezési hibák

| Megfigyelt kudarc | Mi történt | Védelem hozzáadva a nyelvi modellen kívül |
|---|---|---|
| Túl korai befejezés bejelentése | Az egyik rész szerkesztését vagy elindítását a hatás tesztelése előtt befejezettként jelentették. | A befejezéshez bizonyítékra van szükség a kért eredményre vonatkozóan, nem pedig generált állapotnyilatkozatra. |
| A diagnózis elfogadása ellenőrzés nélkül | Egy hibaüzenetet elfogadtak anélkül, hogy ellenőrizték volna, honnan és mikor érkezett, vagy hogy az aktuális feladatot írja-e le. | Kösd a bizonyítékokat ahhoz, hogy hol, mikor és milyen körülmények között állították elő. |
| Hihető találgatás | Az okokat és a következő lépéseket azért javasolták, mert ésszerűnek hangzottak, nem pedig azért, mert bizonyítékok mutattak rájuk. | Őrizd meg az ismeretleneket. Különítse el a megfigyelteket, a lehetséges magyarázatot, a tesztet és a megerősített okot. |
| Feltéve, hogy a legújabb változtatás helyes volt | A legutóbbi nyelvmodell-módosításokat helyesnek tekintették, míg más részeket először gyanították. | Az ok hozzárendelése előtt ellenőrizze a legújabb változást és a versengő magyarázatokat. |
| Az időzítés az ok bizonyítékaként való kezelése | A meghibásodás közelében aktív alkatrészt a normál viselkedés vagy más megváltozott körülmények összehasonlítása nélkül hibáztatták. | Ismételje meg a problémát. Hasonlítsa össze a normál és a megváltozott körülményeket, keressen ellentétes bizonyítékokat, és keresse fel az okot. |
| Egy kis teszt kezelése az élő viselkedés bizonyítékaként | Utánzatot, előkészített példát vagy kis tesztet mutattak be annak bizonyítékaként, hogy az egész rendszer normál használatban működött. | Mondja el pontosan, hogy mit teszteltek, és ne állítsa, hogy az eredmény többet bizonyít. |
| Tesztelés rossz engedélyekkel | A fejlesztői hozzáférést használó ellenőrzés sikeres volt, annak ellenére, hogy az élő program eltérő engedélyekkel futott. | Tesztelje ugyanazt a fiókot és jogosultságokat, amelyeket az élő program is használ, vagy hagyja bizonyítatlanul az eredményt. |
| A hiba javítása a rögzítés előtt | Egy hibát a nyilvánosságra hozatal előtt kijavítottak, így a lemez tisztábbnak tűnt, mint a mű volt. | Őrizze meg a hibát és a javítást rendben. Ne hagyja, hogy a javítás törölje a bizonyítékokat. |
| Ismételt átdolgozás a felhasználó előtt | Az eredményt többször is felülvizsgálták a felhasználó előtt, mert a tervezés az első eredmény utánra csúszott. | Válassza ki az anyagot, és tervezze meg a teljes eredményt, mielőtt felülvizsgálatot kér. Ha lehetséges, mutasson be egy korlátozott vázlatot. |
| Élő szolgáltatás megszakítása egy hiányos szerkesztéssel | Egy nyelvi modell a munkafájlnak csak egy részét változtatta meg, és továbblépett. A futó szolgáltatás nem tudta befejezni a feladatát. | A módosítást addig kell befejezetlenként kezelni, amíg a teljes fájl érvényes nem lesz, és a tényleges szolgáltatás be nem fejezi a kívánt feladatot. |
| Egy beállítás rossz másolatának módosítása | Egy nyelvi modell szerkesztette a fő beállításfájlt, újraindította a szolgáltatást, sikeres újraindítási választ kapott, és sikert jelentett. A szolgáltatás egy másik generált másolatot használt, így a régi beállítás aktív maradt. | Ellenőrizze a látható eredményt, ne csak a szerkesztési vagy újraindítási üzenetet. Maradjon egy szabad útvonal a fő beállítástól a szolgáltatás által ténylegesen használt másolatig. |
| Ismételt javítások, amelyek nem oldották meg a problémát | Egy probléma miatt négy változtatás történt. Mindegyik bizonyította, hogy futott valamilyen kód, de egyik sem bizonyította, hogy az eredeti probléma megszűnt. | Határozza meg az eredményt, amelynek módosítania kell a szerkesztés előtt. Minden változtatás után közvetlenül tesztelje az eredményt. |
| Az élő szolgáltatás nem rendelkezik hozzáféréssel | Egy mappa működött, amikor a személy fiókján keresztül tesztelték, de az élő szolgáltatás egy másik fiókot használt, és továbbra sem tudta elérni. | Futtassa az ellenőrzést ugyanolyan feltételek mellett, mint az élő szolgáltatást. |

## Kudarcok azzal kapcsolatban, hogy ki mit mondhat vagy hagyhat jóvá

| Megfigyelt kudarc | Mi történt | Védelem hozzáadva a nyelvi modellen kívül |
|---|---|---|
| A különböző munkakörök azonosként kezelve | A megfigyelőket, írókat, ellenőrzőket, a munkát abbahagyó embereket és a jóváhagyókat egyformán kezelték, mert mindegyik érintette az eredményt. | Minden alkatrésznek megvan a maga meghatározott feladata és korlátai, hogy mit dönthet. Egy író nem állíthatja igazat. Megfigyelő nem publikálhat. |
| A helyettesítő értékek valósként jelennek meg | A képernyők üres méréseket vagy elfogadható helyettesítőket jelenítettek meg, így a telepítés befejezettnek tűnt. | Mutassa meg a mért értéket és azt, hogy honnan származik, vagy jelezze egyértelműen, hogy nem elérhető. |
| Egy oldal frissítése tönkretette a felhasználó helyét | A frissítés egy teljes oldalt cserélt le, és megsemmisítette a fókuszt, a kijelölést, a görgetés pozícióját vagy a másolást. | Kezelje a képernyőt emberi munkaterületként. Frissítse a változó értékeket a felhasználó helyének tönkretétele nélkül. |
| A jelszavak védtelen szövegben tartása | A jelszavakat és a hozzáférési kulcsokat hagyományos fájlokban helyezték el védett tárhely helyett. | Tartsa őket védett tárhelyen, és ellenőrizze az összes fájlt kiadás előtt. |
| Jelentés arról, hogy egy szolgáltatás leállt, miközben futott | A leállítási kérelem sikeresen visszatért, de a folyamat folytatta a munkát. | Ellenőrzési kérés után ellenőrizze a folyamatot és annak valós hatását. Ne jelentse a kérést eredményként. |

## Az emberi figyelem kudarcai

| Megfigyelt kudarc | Mi történt | Védelem hozzáadva a nyelvi modellen kívül |
|---|---|---|
| Egy személy szavainak kitöltése | Egy rövid emberi kijelentést kibővítettek a generált anyagokkal, amíg az eredeti szavakat nehéz volt megtalálni. | Őrizze meg az eredeti nyilatkozatot fő rekordként. A generált értelmezés különálló és választható marad. |
| Körkörös írás | A választ elmagyarázták, újrafogalmazták, összefoglalták, és a hasznos tartalom elfogyása után levonták a következtetést. | Állítsa le, amikor a kért eredmény elkészült. Távolítsa el az ismételt következtetéseket. |
| A válasz eltemetése | Egy-két hasznos tényt elhelyeztek a felhasználó által nem kért, képernyőnyi anyagban. | Tedd először a legrövidebb teljes választ, és a mélyebb anyagot tegye kötelezővé. |
| Fel nem ajánlott figyelem elköltése | A helyes, de szükségtelen magyarázat arra kényszerítette az olvasót, hogy időt töltsön azzal, hogy eldöntse, szükségtelen. | Számítsa ki az olvasást és a javítást valós költségnek. Hagyja, hogy az olvasó kezdeményezzen opcionális mélységet. |
| Túl nagy hangsúly | Szinte minden pont félkövér volt, fejjel vagy táblázatba helyezve, így a valódi figyelmeztetések már nem tűntek ki. | Csak a döntési vagy biztonsági terhet hordozó néhány megkülönböztetésre helyezze a hangsúlyt. |

## Költségekkel és szolgáltatói ösztönzőkkel járó hibák

| Megfigyelt kudarc | Mi történt | Védelem hozzáadva a nyelvi modellen kívül |
|---|---|---|
| Alapértelmezés szerint használt fizetős nagy nyelvi modell | A munkát fizetős online modellen keresztül küldték el, mert elérhető volt még akkor is, ha egy egyszerű rögzített folyamat, mentett eredmény vagy korlátozott eszköz megbízhatóbban tudta elvégezni. | Mérje meg a munka teljes értékét és költségét. Válassza ki a legkisebb szerszámkombinációt, amelynek működése ellenőrizhető és igazolható. |
| A korrekciós költség eltűnt a végösszegből | Az újrapróbálkozásokat, az ismételt összefüggéseket, a várakozást és az emberi korrekciót ingyenesnek tekintették a rossz eredmény után, annak ellenére, hogy fizetett juttatást használtak, és több időt és energiát követeltek a személytől. | A valós költség részeként rögzítse a várakozást, az újrapróbálkozást, az elutasítást, az ismételt szolgáltatáshasználatot és az emberi figyelmet. |
| Sikertelen munka miatt nem kap vissza kvótát | A kifizetett kvótába beleszámítanak a használhatatlan kimenetek és a javításhoz szükséges cserék. A személy nem kapott automatikus pótlást az elvesztett járadékért vagy időért. | A sikertelen rögzítés és a korrekciós használat külön-külön. Használja újra a mentett kontextust és az elutasított eredményeket, hogy ne vásárolja meg újra ugyanazt a hibát. |
| A hasznos hibát elvetették | Az elutasított válasz eltűnt, így a későbbi munka megismételte ugyanazt a hibát, és újra fizetett érte. | Az elutasított eredményeket és azok elutasításának okait tartsa az elfogadott ismereteken kívül. Használja újra a leckét a nem alátámasztott állítás elfogadása nélkül. |
| Ugyanazt a kontextust kellett újra megadni | Amikor a korábbi információk eltűntek a nyelvi modell működési nézetéből, a személynek rekonstruálnia kellett a kérést, és újra el kellett küldenie az előzményeket, amelyeket egy fizetett munkamenetben már megadtak. | Tartsa a tartós kontextust a szolgáltatáson kívül. Minden munkához készítsen egy korlátozott csomagot, és őrizze meg a visszaküldött munkát, a javítást és az elutasítást későbbi használatra. |

## Hogyan váltak ezekből a szolgáltatási hibákból a projekt tervévé

A megfigyelt probléma nem korlátozódott egy gyenge modellre. Ugyanazt az ideiglenes asszisztenst kérték fel emlékezőként, történészként, tervezőként, íróként, ellenőrzőként és saját munkájának ítélőjére. Még a legerősebben fizetett modellek is sikeresek lehetnek egy-egy egyéni feladatban, miközben elveszítik azt az emberi történelmet, amely minden mással összekapcsolta.

Robot Brain külön részekre adja azokat a munkákat. A forrás őrzője megőrzi az eseményt. A fókuszált helyi olvasók meghatározott jellemzőket vizsgálnak. A kérelem készítője egyetlen célból gyűjt bizonyítékokat. A modell hozzájárulhat a háttérhez vagy a megfogalmazáshoz. Független ellenőrzések és emberi jóváhagyás dönti el, hogy mit fogadunk el.

Az előzmények a fizetős szolgáltatáson kívül maradnak. A modell segíthet a kiválasztott munkában, de nem tárolja az ember életét, és nem válik a már elvégzett munka egyetlen lehetőségévé.

A helyi modellnek ugyanez a korlátja van. Ez nincs kiképezve az adott személy nyilvántartására. Beolvassa a kiválasztott anyagot, dátumozott javaslatot ad vissza, és lecserélhető. Az ember szavai, ideje, tapasztalata, döntései, kudarcai és korrekciói jelentik az értékes részét.
