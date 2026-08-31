> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Toate limbile](../README.md)

# Eșecuri observate în serviciile de model lingvistic plătite: și garanțiile la care au condus

![Eșecurile înregistrate au devenit teste și garanții pentru lucrările ulterioare.](../../illustrations/failures-became-blueprint.png)

## Acestea au fost cele mai puternice opțiuni plătite disponibile

Acest proiect a folosit servicii de model de limbă online plătite pentru cercetare, codare, scriere și revizuire. Conturile includeau cele mai puternice modele generale oferite de acele servicii la momentul respectiv. Alegerea unei opțiuni plătite mai capabile nu a prevenit eșecurile de mai jos.

Fiecare exemplu provine dintr-o înregistrare a proiectului datată. Tabelele descriu ce a făcut un model plătit, ce s-a întâmplat în continuare și ce protecție a fost construită în afara modelului. Acestea sunt defecțiuni observate în serviciile comerciale, nu defecțiuni cauzate deRobot Brain. Coloana din dreapta descrie modul în care acest proiect răspunde.

Înregistrările nu ghicesc motivul furnizorului și nu pretind că cunosc o cauză tehnică nedezvăluită. Numele furnizorilor sunt lăsate afară, deoarece măsurile de protecție răspund mai degrabă la un comportament repetat decât la o singură companie.

## Cât costă eșecurile

Costul nu s-a limitat la un răspuns greșit.

- **Timpul a fost pierdut.** Lucrarea descrisă ca fiind terminată a trebuit să fie inspectată, explicată din nou, reparată și testată de către persoană. Unele eșecuri au consumat ore întregi.
- **Alocația de utilizare plătită, uneori numită cotă, a fost pierdută.** Reîncercările, contextul repetat, schițele de înlocuire și corecțiile au folosit aceeași alocație limitată ca și munca utilă. În aceste sesiuni înregistrate, nu a fost returnată nicio cotă automată pentru rezultate inutilizabile sau schimburi corective.
- **Serviciul a fost plătit în orice mod.** Taxa de abonament sau de utilizare a rămas, în timp ce persoana a absorbit, de asemenea, timpul și efortul necesar pentru a găsi și repara defecțiunea.
- **Lucrurile funcționale au fost întrerupte.** Modificările incomplete au făcut ca un serviciu live să nu poată rula. S-au făcut modificări la o copie greșită a unei setări. Ieșirea a fost mutată din locația necesară în loc să repare accesul.
- **Înregistrarea istorică a fost pusă în pericol.** Textul generat a fost amestecat cu material uman, iar înregistrările au fost modificate sau eliminate înainte ca persoana să aprobe această modificare.
- **Atenția a fost consumată fără permisiune.** Răspunsurile importante au fost îngropate în explicații repetate, forțând persoana să citească totul pentru a recupera mica parte care a contat.

Acesta este motivul pentru care regulile importante nu trăiesc doar într-un prompt aici.Robot Brain verifică ce sa întâmplat de fapt și poate respinge o contribuție chiar și atunci când modelul spune că a reușit.

## Continuitate și eșecuri de cunoaștere

| Eșec observat | Ce s-a întâmplat | Protecție adăugată în afara modelului lingvistic |
|---|---|---|
| Sună continuu după pierderea istoriei | Un serviciu a scurtat conversația anterioară pentru a se potrivi limitei sale de funcționare. A păstrat unele concluzii, dar a pierdut surse, corecții, alternative respinse, ordinea evenimentelor și intenția utilizatorului, continuând să sune fluent. | Păstrați întreaga conversație în ordine. Salvați versiunea scurtată separat și înregistrați ceea ce a inclus, a omis și este posibil să fi pierdut. |
| Un nou răspuns care înlocuiește istoricul înregistrat | Un răspuns mai nou-model de limbă ar putea părea să înlocuiască totul înaintea lui, chiar dacă provine din informații, reguli și opțiuni diferite despre lume. | Salvați fiecare descoperire cu timpul său. Nu lăsați niciodată cel mai nou răspuns să suprascrie constatările anterioare acceptate, respinse sau incerte. |
| Învățarea modelului de limbă a distrus calea înapoi la sursă | Modelul de limbaj a păstrat tipare utile, în timp ce le-a separat de creatorul sursei, scop, public, dovezi, dezacord și istoria ulterioară. | Păstrați sursele neschimbate și conexiunile lor cunoscute în afara fiecărui model de limbă. Tratați cunoștințele neacceptate despre modelul lingvistic ca pe o sugestie, cu excepția cazului în care dovezi separate le conectează la o sursă. |
| Pierderea circumstanțelor din spatele a ceea ce a învățat modelul lingvistic | Modelul lingvistic a rămas util, în timp ce răspunsul său nu a putut dezvălui toate persoanele, sursele, scopurile, dezacordurile, permisiunile și culturile care l-au modelat. | Păstrați circumstanțele cunoscute și creditul cu sursele salvate în afara modelului lingvistic. Tratați cunoștințele învățate nesuportate ca pe o sugestie de model de limbaj, nu ca pe un fapt legat de o sursă. |
| Prejudecăți ascunse față de ceea ce a fost selectat | Ceea ce modelul lingvistic putea recunoaște reflecta limbile, sursele, arhivele, etichetele, recenzenții umani și obiectivele utilizate pentru a-l construi. Răspunsul său nu a dezvăluit toate aceste influențe. | Înregistrați limitele cunoscute ale modelului lingvistic și ceea ce se știe despre materialul din care a învățat. Comparați mai multe instrumente limitate și nu tratați un răspuns simplu ca o vedere completă. |
| Istoricul partajat este rescris în tăcere | Mai mulți lucrători care editează un istoric cu aspect principal ar putea pierde sau combina decizii incompatibile. | Adăugați un nou istoric sursă fără a suprascrie intrările anterioare. Creați vizualizări curente din acel istoric fără a rescrie înregistrarea evenimentului. |
| Vremuri și stări diferite tratate ca egale | Declarațiile curente, istorice, experimentale, testate separat și înlocuite au fost prezentate ca și cum ar avea același statut. | Păstrați timpul și prezentați în picioare fiecare revendicare importantă și parte a sistemului. |
| Îndepărtarea unei piese fără a verifica cine o folosește | O parte nefolosită în procesul actual a fost tratată ca învechită fără a verifica lucrările ulterioare care au depins de ea. | Înregistrați munca, utilizatorii, starea actuală și înlocuirile fiecărei piese. Verificați acei utilizatori înainte de a-l elimina. |
| Amestecarea textului generat în înregistrarea unei persoane | Explicația scrisă-model de limbaj a fost salvată alături de material uman într-o formă care mai târziu ar putea fi confundată cu cuvintele sau credințele proprii ale persoanei. | Păstrați materialul uman literal, transcrierile și interpretarea generată de modelul lingvistic în mod clar separate. Nu lăsați niciodată textul generat să devină în tăcere parte a evidenței umane. |
| Eliminarea istoricului în timpul curățării | Înregistrările anterioare au fost modificate sau eliminate deoarece un model de limbă le-a considerat incorecte sau neîngrijite. Asta a distrus dovezile necesare pentru a înțelege ce s-a întâmplat și de ce s-a schimbat. | Păstrează evidența istorică. Adăugați o corecție sau o constatare ulterioară în loc să rescrieți în tăcere trecutul. |

## Eșecuri de instrucțiune și domeniu

| Eșec observat | Ce s-a întâmplat | Protecție adăugată în afara modelului lingvistic |
|---|---|---|
| Regulile se pierd în timpul sarcinii | Un model de limbaj poate citi, reformula și apoi încălca o regulă în aceeași sarcină. | Transformați regulile a căror eșec are un cost ridicat în condiții și verificări necesare care pot respinge lucrarea. |
| Regulile de revendicare au fost respectate fără dovezi | Modelul susținea că instrucțiunile sau documentele au fost urmate atunci când rezultatul a arătat contrariul. | Solicitați dovezi că verificarea relevantă a fost executată și trecută. Un model de limbaj care spune că a reușit nu este o dovadă. |
| Înlocuirea sarcinii solicitate | O cerere specifică a fost înlocuită cu încadrarea preferată a modelului de limbă, forțând utilizatorul să argumenteze din nou pentru lucrarea originală. | Păstrați limitele solicitate. Respingeți o modificare nesolicitată a cadrului, cu excepția cazului în care o impune un conflict real de siguranță sau permisiuni. |
| Fă muncă suplimentară fără permisiune | Lucrări conexe au fost efectuate pentru că părea utilă, deși nu a fost solicitată. | Leagă fiecare acțiune de sarcina declarată. Tratați orice extindere ca pe o nouă decizie. |
| Schimbarea destinației solicitate | Când locația solicitată nu era accesibilă, rezultatul a fost mutat undeva mai ușor în loc să repare accesul. | Păstrați destinația aleasă. Schimbarea acestuia necesită decizia utilizatorului. |
| Depășirea corecției solicitate | Feedback-ul a fost tratat ca o direcție de a continua schimbarea lucrării în loc de o corecție precisă de atins. | Înregistrați starea finală solicitată și verificați rezultatul după modificare. |
| Forțarea materialului nou în locul greșit | La un document existent a fost adăugat material nou fără a-l potrivi în structură, ceea ce le-a deteriorat pe ambele. | Planificați rezultatul complet, urmăriți ce se modifică adăugarea și creați un document separat atunci când nu aparține. |
| Mutarea ieșirii în loc de a fixa accesul | Când folderul solicitat nu a putut fi accesat, un asistent a mutat rezultatul undeva mai ușor. Acest lucru a împărțit înregistrările persoanei și a eliminat depunerea, permisiunile și obiceiurile deja construite în jurul locației inițiale. | Reparați accesul la locația aleasă. Schimbarea destinației rămâne decizia persoanei. |

## Eșecuri de evidență și finalizare

| Eșec observat | Ce s-a întâmplat | Protecție adăugată în afara modelului lingvistic |
|---|---|---|
| Se declară finalizarea prea devreme | Editarea sau începerea unei părți a fost raportată ca finalizare înainte ca efectul acesteia să fie testat. | Finalizarea necesită dovezi pentru rezultatul solicitat, nu o declarație de stare generată. |
| Acceptarea unui diagnostic fără a-l verifica | Un mesaj de eroare a fost acceptat fără a verifica de unde și când a venit sau dacă descrie sarcina curentă. | Păstrați dovezile legate de locul, când și în ce circumstanțe au fost produse. |
| Ghicire plauzibilă | Cauzele și pașii următori au fost propuși pentru că păreau rezonabile, nu pentru că dovezile le indicau. | Păstrează necunoscutele. Separați ceea ce a fost observat, o posibilă explicație, testul și cauza confirmată. |
| Presupunând că cea mai nouă modificare a fost corectă | Modificările recente ale modelului de limbă scrise au fost presupuse corecte, în timp ce alte părți au fost suspectate mai întâi. | Verificați cea mai nouă modificare și explicațiile concurente înainte de a atribui cauza. |
| Tratarea timpului ca o dovadă a cauzei | Partea activă în apropierea unei defecțiuni a fost învinuită fără a compara comportamentul normal sau alte condiții modificate. | Faceți problema să se întâmple din nou. Comparați condițiile normale și cele modificate, căutați dovezi contrare și urmăriți cauza. |
| Tratarea unui mic test ca o dovadă a comportamentului viu | O imitație, un exemplu pregătit sau un mic test a fost prezentat ca dovadă că întregul sistem a funcționat în utilizare obișnuită. | Spuneți exact ce a fost testat și nu pretindeți că rezultatul dovedește mai mult. |
| Testare cu permisiuni greșite | O verificare a trecut folosind accesul dezvoltatorului, chiar dacă programul live a rulat cu permisiuni diferite. | Testați cu același cont și permisiuni folosite de programul live sau lăsați rezultatul nedovedit. |
| Repararea unei greșeli înainte de a o înregistra | O greșeală a fost reparată înainte de a fi dezvăluită, făcând ca înregistrarea să pară mai curată decât lucrarea. | Păstrați defecțiunea și corectarea în ordine. Nu lăsați reparația să șteargă dovezile. |
| Revizuire repetată în fața utilizatorului | Un rezultat a fost revizuit în mod repetat în fața utilizatorului, deoarece planificarea a fost amânată până după primul rezultat. | Selectați materialul și planificați întregul rezultat înainte de a solicita revizuirea. Prezentați o versiune limitată atunci când este posibil. |
| Ruperea unui serviciu live cu o editare incompletă | Un model de limbă a schimbat doar o parte a unui fișier de lucru și a continuat. Serviciul care rulează a fost lăsat în imposibilitatea de a-și finaliza munca. | Tratați o modificare ca neterminată până când întregul fișier este valabil și serviciul real finalizează lucrarea dorită. |
| Modificarea copiei greșite a unei setări | Un model de limbă a editat fișierul principal de setări, a repornit serviciul, a primit un răspuns de repornire cu succes și a raportat succesul. Serviciul a folosit o altă copie generată, așa că vechea setare a rămas activă. | Verificați rezultatul vizibil, nu doar mesajul de editare sau repornire. Păstrați o cale clară de la setarea principală la copia pe care o folosește de fapt un serviciu. |
| Remedieri repetate care nu au rezolvat problema | Au fost făcute patru modificări pentru o singură problemă. Fiecare a dovedit că un cod a rulat, dar niciunul nu a dovedit că problema inițială a dispărut. | Definiți rezultatul care trebuie schimbat înainte de editare. După fiecare modificare, testați direct rezultatul. |
| Verificarea cu acces serviciul live nu a avut | Un folder a funcționat când a fost testat prin contul persoanei, dar serviciul live a folosit un alt cont și tot nu a putut accesa el. | Rulați verificarea în aceleași condiții ca și serviciul live. |

## Eșecuri cu privire la cine poate spune sau aproba ce

| Eșec observat | Ce s-a întâmplat | Protecție adăugată în afara modelului lingvistic |
|---|---|---|
| Locuri de muncă diferite tratate ca la fel | Observatorii, scriitorii, verificatorii, oamenii care pot opri munca și autorizatorii de eliberare au fost tratați la fel, deoarece fiecare a atins rezultatul. | Fiecare parte are o sarcină declarată și limite asupra a ceea ce poate decide. Un scriitor nu poate face o afirmație adevărată. Un observator nu poate publica. |
| Se afișează valorile de înlocuire ca fiind reale | Ecranele afișau măsurători goale sau înlocuitori plauzibili, astfel încât instalarea părea completă. | Afișați o valoare măsurată și de unde provine sau precizați clar că nu este disponibilă. |
| Reîmprospătarea unei pagini a distrus locul utilizatorului | O reîmprospătare a înlocuit o pagină întreagă și a distrus focalizarea, selecția, poziția de defilare sau copierea. | Tratați ecranul ca pe un spațiu de lucru uman. Actualizați valorile în schimbare fără a distruge locul utilizatorului. |
| Păstrarea parolelor în text neprotejat | Parolele și cheile de acces au fost plasate în fișiere obișnuite în loc de stocare protejată. | Păstrați-le în spațiu de stocare protejat și verificați fiecare fișier înainte de lansare. |
| Raportarea că un serviciu s-a oprit în timp ce continua să ruleze | Solicitarea de oprire a revenit cu succes, dar procesul a continuat să funcționeze. | Verificați procesul și efectul său real după o solicitare de control. Nu raportați cererea ca rezultat. |

## Eșecuri de atenție umană

| Eșec observat | Ce s-a întâmplat | Protecție adăugată în afara modelului lingvistic |
|---|---|---|
| Completarea cuvintelor unei persoane | O scurtă declarație umană a fost extinsă cu materialul generat până când cuvintele originale au fost greu de găsit. | Păstrați declarația originală ca înregistrare principală. Interpretarea generată rămâne separată și opțională. |
| Scrierea circulară | Răspunsul a fost explicat, reformulat, recapitulat și încheiat după ce conținutul util s-a epuizat. | Opriți când rezultatul solicitat este complet. Eliminați concluziile repetate. |
| Îngropând răspunsul | Unul sau două fapte utile au fost plasate în ecrane pline de material pe care utilizatorul nu le-a solicitat. | Puneți primul răspuns complet și scurt și opțional materialul mai profund. |
| Cheltuind o atenție neoferită | Explicația corectă, dar inutilă, l-a forțat pe cititor să petreacă timp hotărând că nu este necesar. | Considerați citirea și corectarea drept costuri reale. Lăsați cititorul să inițieze profunzimea opțională. |
| Prea mult accent | Aproape fiecare punct a fost îndrăzneț, cu cap sau plasat într-un tabel, așa că avertismentele reale nu au mai ieșit în evidență. | Folosiți accentul numai pentru puținele distincții care poartă povara deciziei sau a siguranței. |

## Eșecuri care implică costuri și stimulente ale furnizorilor

| Eșec observat | Ce s-a întâmplat | Protecție adăugată în afara modelului lingvistic |
|---|---|---|
| Un model de limbă mare plătit utilizat implicit | Lucrarea a fost trimisă printr-un model online plătit, deoarece era disponibil, chiar și atunci când un proces simplu fix, un rezultat salvat sau un instrument limitat ar putea face acest lucru mai fiabil. | Măsurați valoarea totală și costul lucrării. Alegeți cea mai mică combinație de instrumente a cărei muncă poate fi verificată și justificată. |
| Costul corecției a dispărut din totaluri | Reîncercările, contextul repetat, așteptarea și corecția umană au fost tratate ca gratuite după un rezultat prost, chiar dacă au folosit alocația plătită și au cerut mai mult timp și energie persoanei. | Înregistrați așteptarea, reîncercările, respingerea, utilizarea repetată a serviciului și atenția umană ca parte a costului real. |
| Nu s-a returnat nicio cotă pentru lucru eșuat | Ieșirea inutilizabilă și schimburile necesare pentru a o corecta au fost luate în considerare din cota plătită. Persoana nu a primit nicio înlocuire automată pentru alocația sau timpul pierdut. | Înregistrați separat utilizarea eșuată și cea corectivă. Reutilizați contextul salvat și rezultatele respinse, astfel încât același eșec să nu fie achiziționat din nou. |
| Eșecul util a fost eliminat | Un răspuns respins a dispărut, așa că mai târziu munca a repetat aceeași greșeală și a plătit din nou. | Păstrați rezultatele respinse și motivele respingerii lor în afara cunoștințelor acceptate. Reutilizați lecția fără a accepta revendicarea nesusținută. |
| Același context trebuia furnizat din nou | Când informațiile anterioare au dispărut din perspectiva de lucru a modelului de limbă, persoana a trebuit să reconstruiască cererea și să retrimite istoricul deja furnizat într-o sesiune plătită. | Păstrați contextul de durată în afara serviciului. Creați un pachet limitat pentru fiecare lucrare și păstrați munca returnată, corectarea și respingerea pentru o utilizare ulterioară. |

## Cum acele defecțiuni ale serviciului au devenit designul acestui proiect

Problema observată nu sa limitat la un model slab. Același asistent temporar i s-a cerut să acționeze ca memorie, istoric, planificator, scriitor, verificator și judecător al propriei sale lucrări. Chiar și cele mai puternice modele plătite ar putea reuși la o sarcină individuală, pierzând în același timp istoria umană care a legat-o de orice altceva.

Robot Brain dă acele locuri de muncă unor părți separate. Deținătorul sursei păstrează evenimentul. Cititorii locali concentrați examinează caracteristicile definite. Constructorul cererii adună dovezi într-un singur scop. Un model poate contribui la fundal sau la formulare. Controalele independente și aprobarea umană decid ce este acceptat.

Istoricul rămâne în afara serviciului plătit. Un model poate ajuta la o slujbă aleasă, dar nu stochează viața persoanei și nu devine singura modalitate de a folosi munca care a fost deja făcută.

Modelul local are aceeași limită. Nu este instruit pe evidențele persoanei. Citește materialul selectat, returnează o sugestie datată și poate fi înlocuit. Cuvintele persoanei, timpul, experiența, deciziile, eșecurile și corecțiile sunt partea valoroasă.
