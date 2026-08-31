> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../README.md) | [Toate limbile](../README.md)

# Păstrați evidența. Înlocuiți modelul.

![Evidențele unei persoane rămân într-un singur loc, în timp ce părțile de lucru separate se ocupă de sarcini limitate.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain este un software pentru păstrarea istoriei și a sensului din spatele muncii umane de lungă durată. Nu este un model de limbă, un chatbot sau un serviciu care trimite fiecare întrebare către un model.

Modelele mari de limbaj pot cerceta, scrie, explica și pot ajuta la rezolvarea problemelor dificile. Serviciile plătite construite în jurul lor sunt încă spații de lucru temporare. Ei pot scurta o conversație lungă, pot pierde instrucțiunile anterioare, pot separa concluziile de dovezile lor și pot continua să scrie ca și cum istoria lipsă ar fi încă prezentă. Apoi, o persoană petrece mai mult timp și utilizarea plătită reconstruind contextul care a fost deja furnizat.

Acest software schimbă locul unde trăiește valoarea durabilă. Conversațiile, documentele, deciziile, încercările eșuate, corecțiile și întrebările fără răspuns ale persoanei respective rămân în înregistrările pe care persoana le controlează. Programele locale pot examina acele înregistrări. Un model de limbă poate ajuta cu un loc de muncă selectat, dar contribuția acestuia revine în evidență ca lucrare datată, care poate fi revizuită. Modelul poate fi apoi înlocuit fără a lua istoricul cu el.

[Citiți această documentație într-o altă limbă.](../README.md)

## Diferența într-un singur punct de vedere

| Un serviciu de model de limbaj comercial | Robot Brain |
|---|---|
| Produce un răspuns din materialul aflat în prezent în vizualizarea sa de lucru. | Păstrează sursa completă și istoria din jurul acesteia. |
| Poate scurta sau pierde conversația anterioară pe măsură ce munca crește. | Salvează conversațiile din afara fiecărui model, astfel încât să poată fi utilizate din nou. |
| Combină cunoștințele învățate din mai multe surse fără o cale completă înapoi la fiecare sursă și circumstanțele ei. | Păstrează fiecare sursă cunoscută, descoperirea ulterioară, corectarea și dezacordul ca o înregistrare separată. |
| Poate scrie, căuta, planifica și judeca propriul răspuns într-un singur schimb. | Oferă salvare, căutare, analiză, scriere, verificare și aprobare părților separate cu autoritate limitată. |
| Controlează modelul, regulile de serviciu, limitele de utilizare și modificările produsului. | Lasă înregistrarea de durată sub controlul persoanei. |
| Este plătit pentru încercările eșuate și schimburile corective, precum și pentru munca utilă. | Păstrează eșecurile și corecțiile, astfel încât lecțiile lor să nu fie achiziționate din nou. |

Robot Brain poate apela un model de limbă locală sau online. Asta nu îl transformă într-un proxy model. Poate păstra, căuta, compara, organiza și reconstrui lucrările anterioare fără a apela modelul care a luat parte la conversația originală. Când un model este util, cererea este un pas într-un proces mai amplu care există independent de acel model.

## De ce a fost construit asta

Cele mai puternice modele de uz general plătite disponibile în timpul dezvoltării au fost gardieni capabili, dar nesiguri, ai muncii îndelungate.

Eșecurile înregistrate au inclus instrucțiuni pierdute, dovezi lipsă, conexiuni inventate, cereri premature de finalizare, modificări nedorite și deteriorarea fișierelor de lucru. Corectarea acelor eșecuri a necesitat mai multe solicitări, mai multe teste, mai multă indemnizație plătită și mai mult din timpul și energia persoanei. Serviciile nu au returnat automat utilizarea cheltuită pentru lucrări inutilizabile sau schimburile necesare pentru a o repara.

Problema a fost mai mare decât orice răspuns prost. I s-a cerut unui generator de text temporar să servească drept memorie, istoric, cercetător, scriitor, verificator și judecător final. Schimbarea modelelor nu a schimbat acest aranjament.

Robot Brain a fost construit în jurul unui aranjament diferit: păstrați mai întâi evidența umană, lăsați mai multe părți înlocuibile să contribuie la aceasta și necesită dovezi în afara modelului generator înainte de a accepta lucrările importante.

## Ce nu poate păstra un model antrenat

Un model de limbaj mare învață tipare din colecții enorme de muncă umană. Aceste modele fac modelul util, dar modelul nu este o bibliotecă a lucrărilor complete care l-au modelat.

În interiorul modelului, influența din cărți, articole, conversații, traduceri, comunități, etichete și feedback uman este amestecată. De obicei, modelul nu poate arăta care surse au modelat o anumită propoziție. Nu poate restabili scopul fiecărui autor, audiența, dovezile, dezacordul, corectarea ulterioară sau punctul de vedere lipsă.

Aceasta este o pierdere a sensului chiar și atunci când opera originală există încă în altă parte. Modelul păstrează o anumită utilitate din lucrare, în timp ce renunță la calea sigură înapoi la setarea umană.

Aceeași problemă apare în timpul utilizării obișnuite. Un răspuns final poate supraviețui după ce conversația care i-a dat sens a fost scurtată. Concluzia rămâne, dar încercările eșuate, incertitudinea și motivele din spatele acesteia dispar din perspectiva de lucru a modelului.

Acest proiect nu răspunde acestei probleme prin antrenarea unui alt model asupra vieții unei persoane. Istoria personală rămâne lizibilă și urmăribilă în loc să fie amestecată într-un alt model antrenat. Modelele funcționează cu înregistrări selectate; nu devin înregistrări.

## Ce face fiecare parte

Software-ul de lucru separă joburile pe care un serviciu de chat le face adesea să arate ca o singură activitate:

1. **Deținătorul sursei salvează ceea ce sa întâmplat.** Păstrează conversația, documentul, imaginea sau alt material fără a le înlocui cu un rezumat.
2. **Copiile care pot fi căutate fac sursa mai ușor de găsit.** Textul, descrierile și indexurile copiate indică înapoi la sursa neschimbată și pot fi reconstruite.
3. **Cititorii locali concentrați examinează caracteristicile specifice.** Metodele separate privesc limbajul, afirmațiile, relațiile, raționamentul, timpul, experiența umană și valorile. Fiecare raportează doar propriile sale constatări și pasajele din spatele lor.
4. **Înregistrarea istoricului păstrează vizibilă schimbarea.** Noile constatări, corecții, dezacorduri, încercări nereușite și întrebări deschise sunt adăugate fără a rescrie evenimentele anterioare.
5. ** Generatorul de solicitări adună ceea ce are nevoie un loc de muncă.** Selectează sursele și constatările relevante și înregistrează ceea ce a fost inclus sau omis.
6. **Un model de limbă poate adăuga ajutor limitat.** Un model local poate oferi un fundal larg. Un model online poate ajuta la cercetarea sau scrierea dificilă. Oricare răspuns rămâne o contribuție datată care poate fi verificată, respinsă sau înlocuită.
7. **Verificări separate compară rezultatul cu cererea și dovezile.** Modelul care a scris un răspuns nu poate declara propria lucrare acceptată.
8. **Un ecran permite unei persoane să utilizeze software-ul.** Este inclusLibreChatfurca este un astfel de ecran. Înlocuirea acestuia nu înlocuiește înregistrările sau celelalte părți de lucru.

Nici o singură parte nu este prezentată ca un asistent atotștiutor. Lucrările lor limitate fac ca fiecare parte să fie înlocuită.

## Faceți din nou utilă o conversație finalizată

O conversație finalizată conține cererea persoanei, răspunsurile reale ale modelului lingvistic, munca încercată, eșecurile, corecțiile și punctul în care s-a încheiat schimbul. Aceste mesaje păstrează ceea ce a contribuit modelul original fără a solicita ca modelul să se explice mai târziu.

Cititorii locali concentrați examinează schimbul salvat din mai multe unghiuri. Ei pot găsi modele și relații detaliate fără a se baza pe cunoașterea amplă a lumii. Descoperirile lor separate rămân legate de părți exacte ale conversației.

Aceste descoperiri pot avea nevoie în continuare de cunoștințe generale obișnuite înainte de a forma o relatare clară. Pentru acel pas limitat, un micQwenmodelul rulează local prinvLLM. Acesta adaugă o imagine de ansamblu datată care ajută la conectarea constatărilor detaliate și explică ceea ce a realizat schimbul.

Qwennu recuperează gândurile ascunse ale modelului online sau istoricul antrenamentului. Oferă cunoștințe generale care nu sunt unice pentru modelul original. Contribuția utilă a modelului original este deja păstrată în cuvintele pe care le-a produs.

TheQwenPrezentare generală este stocată lângă sursă și constatările anterioare. Poate fi corectat sau înlocuit. Conversația originală și analiza locală detaliată rămân neschimbate.

## Ce merge acum

Implementarea actuală poate păstra o conversație finalizată, o poate examina prin metode locale separate, poate adăuga o citire locală de cunoștințe generale și poate aduna fiecare contribuție reținută într-o înregistrare care poate fi reconstruită ulterior.

De asemenea, poate pregăti o solicitare limitată pentru un model online atunci când ajutorul extern este util. Serviciul respectiv primește doar materialul selectat. Răspunsul său revine la evidența locală, unde verificările și aprobarea umană: nu modelul: decid ce se păstrează.

Aceasta este realizarea centrală: munca care depindea cândva de o conversație temporară poate rămâne utilă după ce ecranul de chat, modelul și furnizorul său dispar.

## Citiți explicația completă

- [De ce modelele mari de limbaj nu pot păstra întreaga poveste](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Ce face fiecare parte și ceea ce nu controlează niciun model](02-A-Lasting-Record-Outside-the-Model.md)
- [Păstrați corectarea fără a șterge greșeala](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Urmați o revendicare înapoi la dovezi](04-How-Every-Claim-Can-Be-Checked.md)
- [Construiește documentul înainte de a scrie proza](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Explicați același adevăr diferiților cititori](06-One-Meaning-Different-Readers.md)
- [Păstrați istoricul privat sub controlul persoanei respective](07-Privacy-and-Control-Stay-With-People.md)
- [Ce face implementarea actuală](08-What-Works-Today.md)
- [De ce designul atrage din multe domenii](09-How-Research-Strengthens-the-System.md)
- [Ajutor fără a preda înregistrările private](11-Contribute-Without-Giving-Up-Control.md)
- [Cuvintele folosite în aceste documente](12-A-Short-Guide-to-Key-Terms.md)
- [Urmați o solicitare prin părțile de lucru](13-The-Parts-Running-Today.md)
- [Utilizați un model de limbaj pentru job, nu ca memorie](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Eșecuri observate în serviciile de model lingvistic plătite: și garanțiile la care au condus](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Lecții care au schimbat designul](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Note de utilizare publică, credit și confidențialitate](18-Use-Attribution-and-Limits.md)
- [Cum o conversație finalizată devine cunoaștere durabilă](19-What-the-System-Accomplishes.md)
- [Ce urmează](20-Where-the-System-Goes-Next.md)

## Credite, surse și drepturi

- [Ce a ajutat la modelarea acestei lucrări](10-What-Helped-Shape-This-Work.md)
- [Cercetare în spatele designului](14-Sources-Behind-the-Design.md)
- [Surse, licențe și verificări publice](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Licenţă

Scrierile, diagramele și ilustrațiile originale ale proiectului sunt disponibile în cadrul organizației[Licență internațională Creative Commons Atribuire 4.0](../../LICENSE.md), cu excepția cazului în care un document prevede termeni diferiți. Materialul creat de alții își păstrează propriile drepturi și termeni.

## Independență și confidențialitate

Acesta este un proiect personal independent dezvoltat pe timp personal, echipamente, conturi și servicii plătite. Niciun angajator nu a participat la ea. Menționarea oricărei persoane, angajator, instituție, furnizor de model, grup de cercetare, regulă comună sau proiect din afara nu implică participare, aprobare, parteneriat sau aprobare.

Eliberarea publică exclude înregistrările private, detaliile de identificare, parolele, informațiile despre conexiunea privată, informațiile despre angajator și instrucțiunile pentru accesarea serviciilor private. Descrierile defecțiunilor modelului sunt limitate la comportamentul înregistrat și efectul acestuia; nu pretind cauze sau motive nedezvăluite. Documentele nu sunt sfaturi profesionale sau o promisiune de rezultate.

![O cale de la memoria controlată de furnizor către înregistrările care rămân la persoanele pe care le privesc.](../../illustrations/open-door-human-future.png)
