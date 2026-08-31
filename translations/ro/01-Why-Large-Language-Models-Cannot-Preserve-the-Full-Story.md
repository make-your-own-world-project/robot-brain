> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Toate limbile](../README.md)

# De ce modelele mari de limbaj nu pot păstra întreaga poveste

![Piesele salvate își pierd valoare atunci când sursele, relațiile și istoria lor sunt separate.](../../illustrations/ordinary-storage-loses-context.png)

Cele mai puternice modele lingvistice plătite utilizate în timpul construirii acestui proiect ar putea face o muncă impresionantă. Ei ar putea scrie, cerceta, explica și ajuta la rezolvarea problemelor dificile. Ei încă nu au putut păstra întreaga istorie din spatele unui proiect lung.

Un răspuns ulterior ar putea să-și amintească concluzia, dar să piardă încercările eșuate, corecțiile și dovezile care au condus la aceasta. Instrucțiunile anterioare puteau dispărea atunci când o conversație devine prea lungă. Modelul va continua să scrie ca și cum nimic important nu s-ar fi pierdut.

Aceasta este o problemă serioasă atunci când istoricul lipsă reprezintă timpul, cunoștințele sau experiența cuiva.

## Fișierele nu sunt suficiente

Un dosar poate păstra fiecare notă, conversație, imagine și sarcină, pierzând totuși povestea care le leagă.

Luni mai târziu, o persoană poate avea nevoie să știe:

- ce a început lucrarea
- care idei au fost luate în considerare
- de ce o încercare a eșuat
- ce dovezi au schimbat planul
- care concluzie este actuală
- ceea ce este încă necunoscut
- de ce contează acum o notă veche

Căutarea poate găsi un fișier cu cuvinte similare. Nu poate răspunde în mod fiabil la aceste întrebări. Trimiterea unui teanc mai mare de fișiere la un model de limbă nu creează nici o memorie permanentă. Serviciul vede ce a fost selectat pentru acea solicitare. Când solicitarea se încheie, conexiunile utile pot dispărea din nou.

## Antrenamentul pierde, de asemenea, setarea originală

Modelele de limbaj învață modele din colecții enorme de lucrări umane. Asta le face utile. De asemenea, ei nu pot acționa ca o arhivă fidelă a tot ceea ce i-a modelat.

Ideile dintr-o carte, articol, conversație, traducere sau comunitate devin amestecate cu idei din multe altele. Modelul nu păstrează intactă fiecare lucrare cu autorul, scopul, publicul, dovezile, dezacordul și corecțiile ulterioare atașate.

Lucrarea originală poate exista încă în altă parte. Un furnizor poate păstra, de asemenea, copii separate. Pierderea descrisă aici are loc în interiorul modelului antrenat: păstrează influența utilă a lucrării, dar nu poate reconstrui semnificația umană completă în jurul acesteia.

Repetarea unei propoziții nu este același lucru cu păstrarea acestui sens. Un model poate reproduce cuvinte familiare fără să știe de ce au fost scrise, ce situație au descris, a cărui vedere lipsește sau ce s-a întâmplat mai târziu.

## Istoria lipsă ascunde, de asemenea, părtinire

Nici un model de limbă învățat din întreaga lume.

Cunoștințele sale reflectă ceea ce a fost scris, păstrat, colectat, tradus, licențiat, etichetat și selectat. De asemenea, reflectă ceea ce lipsea. Unele limbi și comunități au mult mai mult material publicat decât altele. Arhivele păstrează punctele de vedere ale instituțiilor puternice mai des decât cunoștințele private, locale sau orale.

Oamenii care construiesc modelul fac mai multe alegeri cu privire la ceea ce să elimine, să recompenseze, să descurajeze sau să trateze ca pe un răspuns bun. Regulile produsului adaugă un alt strat. Un răspuns final poate purta toate aceste influențe fără a arăta care dintre ele a afectat o anumită propoziție.

O citare găsită în timpul unei noi solicitări nu dezvăluie acest istoric complet. Afișează o sursă folosită sau numită pentru acea cerere, nu tot ceea ce a învățat modelul cum să interpreteze subiectul.

## Ce păstrează în schimb acest proiect

Robot Brain păstrează sursa înainte de a cere ajutor oricărui model pentru a o interpreta. Sursa nu se modifică atunci când se adaugă un rezumat, o corecție sau o nouă interpretare.

Lucrările ulterioare sunt salvate lângă ea cu o dată și un link înapoi la pasajul relevant. O încercare eșuată poate rămâne vizibilă. O concluzie corectată poate indica dovezile care au schimbat-o. În cazul în care motivul modificării este necunoscut, dosarul spune acest lucru.

Când cineva are nevoie de un răspuns sau un document, generatorul de solicitări adună partea din istoria necesară pentru lucrare. Rezultatul poate fi mai scurt decât înregistrarea completă fără a pretinde că îl înlocuiește.

Un model de limbaj poate ajuta cu acest rezultat. Nu poate șterge sursele, nu poate rescrie trecutul sau nu poate face ca o presupunere neacceptată să devină parte din înregistrarea acceptată.

## Proba practică

Un rezultat util ar trebui să permită cititorului să răspundă la patru întrebări:

1. Ce s-a întâmplat?
2. Ce dovezi susțin acest cont?
3. Ce s-a schimbat, a eșuat sau rămâne contestat?
4. Ce este încă necunoscut?

Dacă dosarul nu poate răspunde la una dintre aceste întrebări, limbajul lucios nu ar trebui să ascundă decalajul.
