> Italiano: Traduzione assistita da macchina dell'autorevole fonte inglese. Sono gradite correzioni nella lingua madre. [Inglese](../../02-A-Lasting-Record-Outside-the-Model.md) | [Tutte le lingue](../README.md)

# Ciò che fa ciascuna parte e ciò che nessun modello controlla

![Le fonti originali supportano una storia duratura mentre gli strumenti sostituibili svolgono un lavoro limitato.](../../illustrations/core-architecture-layers.png)

Robot Brain è una raccolta di parti cooperanti costruite attorno a un record duraturo. Non è un grande modello linguistico, un gruppo di modelli che fingono di esserlo, o un servizio di chat con ricerca extra.

La distinzione è importante perché i problemi affrontati derivano dal chiedere a un servizio temporaneo di modello linguistico di fungere da memoria, ricercatore, scrittore, controllore e giudice allo stesso tempo. Questo software separa questi lavori e mantiene la storia della persona fuori da ogni modello.

## Salvare l'evento prima di interpretarlo

Il custode della fonte salva la conversazione, la nota, l'immagine, il documento, l'attività o altro elemento così come è arrivato. Salva anche fatti effettivamente noti, come l'ora di arrivo, la fonte, il creatore quando stabilito e l'autorizzazione quando registrato.

Un nome di file, un'ipotesi di modello o un'interpretazione successiva non possono diventare silenziosamente un fatto relativo alla fonte. Le informazioni mancanti restano mancanti.

## Rendi utile la ricerca senza sostituire la fonte

Il software crea copie ricercabili come testo estratto, descrizioni e indici. Queste copie rimandano alla fonte invariata. Possono essere ricostruiti quando diventa disponibile un metodo migliore.

Ciò è diverso dal chiedere a un modello linguistico di riassumere una pila di file e poi trattare il riepilogo come memoria. Un riepilogo è una visualizzazione successiva. Non sostituisce mai il materiale che descrive.

## Lasciamo che i lettori locali focalizzati facciano risultati limitati

Metodi locali separati esaminano le caratteristiche definite della fonte. Alcuni guardano alla struttura del linguaggio. Altri identificano affermazioni, possibili relazioni, ragionamenti, cambiamenti nel tempo o osservazioni sull'esperienza e sui valori umani.

Questi metodi non sono piccoli chatbot. Eseguono lavori ristretti contro il materiale risparmiato. Ogni reperto identifica il brano esaminato, il metodo utilizzato, la data e i limiti conosciuti. Un metodo può trovare qualcosa, non trovare nulla, rifiutarsi di rispondere o fallire. Non può riscrivere il lavoro di un altro metodo.

## Mantieni la storia come storia

Nuovi risultati vengono aggiunti accanto agli eventi precedenti. Le correzioni non cancellano gli errori. Una conclusione successiva può diventare attuale mentre la conclusione precedente rimane visibile con le prove e le circostanze che un tempo la supportavano.

Ciò consente al lavoro successivo di rispondere non solo a “cosa si crede ora?” ma anche “cosa è cambiato, perché è cambiato e quanto è costato il cambiamento?”

## Raccogli prove per una richiesta

Il generatore di richieste inizia con lo scopo della risposta o del documento. Identifica ciò di cui il lettore ha bisogno, raccoglie le fonti e i risultati che riguardano tali domande e registra ciò che è stato incluso e ciò che è stato escluso.

Un servizio di chat commerciale di solito chiede al modello di lavorare da qualunque testo si adatti alla richiesta corrente. Qui, la selezione delle prove è un passo registrato al di fuori del modello. Il modello non può decidere tranquillamente che la storia mancante non abbia importanza.

## Utilizzare i modelli come contributori

Un modello linguistico può essere utile per la ricerca, un background ampio o la scrittura. Riceve il materiale selezionato per un lavoro dichiarato.

L'attuale installazione utilizza anche un piccolo localeQwenmodello per uno scopo specifico: dopo che un'analisi locale mirata ha esaminato una conversazione completata,Qwenaggiunge conoscenze di base ordinarie che aiutano a collegare i risultati separati. Non diventa memoria, non recupera pensieri nascosti, né decide cosa significa lo scambio.

Sia locale che online, una risposta modello viene salvata come contributo datato. Può essere controllato, corretto, rifiutato o sostituito senza modificare la fonte.

## Controlla il lavoro esterno allo scrittore

Controlli separati confrontano una risposta o un documento finito con le sue fonti, la copertura richiesta e i limiti dichiarati. Viene registrata la versione esatta passata.

Un modello linguistico non può rendere vera la propria affermazione scrivendo con sicurezza. Né può far accettare il proprio operato affermando di aver seguito le istruzioni.

## Utilizzare qualsiasi schermo adatto

L'inclusoLibreChatfork fornisce una schermata di conversazione per richiedere lavoro e leggere i risultati. Non memorizza la documentazione duratura, non dirige ogni altra parte o approva le risposte.

LibreChatpuò essere sostituito da un'altra schermata.Qwenpuò essere sostituito da un altro modello adatto. Un fornitore online può essere modificato o omesso. La cronologia della fonte e il lavoro accettato rimangono utilizzabili perché nessuna di queste parti li possiede.

## Il confine che definisce il progetto

I modelli linguistici generano contributi temporanei dal materiale che vengono mostrati.Robot Brain preserva la fonte, organizza il lavoro attorno ad essa, registra le modifiche, prepara richieste limitate e controlla ciò che ritorna.

Ecco perché questo non è un altro modello linguistico, un modello proxy o un chatbot migliore. I modelli possono partecipare al lavoro. Il lavoro non dipende da nessun modello.
