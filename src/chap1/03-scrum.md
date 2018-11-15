# Scrum

Scrum è un framework agile nato per lo sviluppo software, ma è attualmente usato anche per realizzare altri tipi di progetti non informatici.

Si basa su:
- piccoli gruppi di lavoro, dalle 5 alle 9 persone
- la divisione del ruolo tradizionale del product manager in più ruoli
- cicli di iterazione brevi, detti anche _sprint_, tipicamente due settimane

[Ken Schwaber](https://en.wikipedia.org/wiki/Ken_Schwaber) e [Jeff Sutherland](https://en.wikipedia.org/wiki/Jeff_Sutherland) sono tra i fondatori di questo framework, negli anni '90, ed hanno partecipato alla scrittura del manifesto Agile nel 2001.

Noi applicheremo il framework Scrum a scuola, che è un contesto diverso rispetto a quello aziendale per cui è nato. Per questo motivo apporteremo alcune modifiche, in particolare il nostro team sarà composto da 3 studenti più il docente, come vedremo.

## I 3 ruoli Scrum
Il team scrum prevede che ad ogni membro del team venga assegnato un ruolo ben definito.

> Tradizionalmente esisteva la figura del Product Manager che aveva molti compiti e responsabilità, tra cui:
> - definire gli obiettivi e le scadenze
> - assegnare le attività
> - interfacciarsi con i livelli alti dell'azienda ed il cliente
> - validare i requisiti
> - decidere se gli obiettivi sono stati raggiunti
> - fare da coach a tutti
> - assicurarsi che siano seguite le linee guida aziendali
>
> Tutte le altre persone del team erano sostanzialmente dei semplici esecutori, con poteri decisionali molto limitati.
>
> Questo modello si è rivelato un fallimento, per motivi abbastanza evidenti: una singola persona non può avere né il tempo né tutte le capacità tecniche e relazionali richieste. Scrum vuole quindi suddividere questi compiti in più ruoli e più figure all'interno del team.

### Team di sviluppo (self-organizing)
Fanno parte del team di sviluppo i programmatori che andranno effettivamente a realizzare e testare il codice.

Il team di sviluppo scrum si dice che si auto-organizza (self-organizing) perché ha le seguenti caratteristiche.
- decide autonomamente come dividersi il lavoro: i task non vengono assegnati ai singoli individui dall'esterno ma i membri del team si dividono i compiti tra di loro in autonomia
- decide autonomamente il tempo necessario ad implementare i singoli task
- può scegliere gli strumenti e le tecnologie da usare per raggiungere gli obiettivi, all'interno delle linee guida aziendali
- dimostra il lavoro realizzato al Product Owner per validazione ed accettazione

### Product Owner
La responsabilità principale del Product Owner è che il prodotto rispetti le aspettative del cliente.

Nel dettaglio:
- definisce le funzionalità del progetto
- decide le date di rilascio ed il relativo contenuto
- responsabile del ROI (Return On Investment)
- può cambiare funzionalità solo oltre i 30 giorni
- accetta o rifiuta il lavoro del team

Il Product Owner **non** è equivalente al tradizionale Product Manager: ha infatti solo parte delle responsabilità di quest'ultimo. Inoltre non è il _capo_, dimenticatevi questa organizzazione gerarchica all'interno del team: tutti i membri sono pari, con ruoli e responsabilità differenti.

### Scrum Master
Lo Scrum Master deve assicurarsi che il team sia produttivo e che il metodo Scrum sia applicato correttamente.

In particolare:
- rimuove gli impedimenti, ad esempio computer rotti, licecnze mancanti, problemi burocratici, etc.
- si assicura che le regole scrum e le linee guida aziendali siano rispettate
- protegge il team dalle interferenze esterne (amministratore delegato invadente, clienti ansiosi, etc.)

Lo Scrum Master è un po' il vigile del team, che si assicura che tutto vada per il verso giusto. È la figura meno coinvolta nello specifico progetto, e non è raro che segua più progetti contemporaneamente o che sia esterno all'azienda.

Nel nostro caso, il vostro Scrum Master è il docente, che quindi avrà questo ruolo in tutti i team della classe.

## Ciclo di sviluppo
Il ciclo di sviluppo Scrum è tipicamente di due settimane, al termine del quale si deve presentare un piccolo _prototipo funzionante_.

In altre parole, Scrum (ed in generale Agile) si concentra sul fatto che bisogna **rilasciare il più frequentemente possibile** dei prodotti che possano essere testati non solo dal team di sviluppo, ma anche dal cliente ed eventualmente dal cliente finale per **ricevere feedback** il prima possibile.

Volendo fare il classico paragone con la creazione di una macchina, in Scrum si sviluppa prima un triciclo, poi una bicicletta, poi un motorino, e così via fino ad arrivare al prodotto finale. Questo si contrappone al tradizionale metodo di sviluppare i componenti finali separatamente: prima il motore, poi la carrozzeria, le ruote, etc. In questo modo si può provare il prodotto (la macchina) solo alla fine del progetto. È abbastanza evidente quindi che il metodo Scrum è più adatto nei constesti in cui i requisiti sono incerti e mutevoli, mentre il metodo tradizionale dove si ha la ragionevole certezza che nulla cambierà durante lo sviluppo del prodotto. Nel mondo contemporaneo, tuttavia, quest'ultima situazione non accade praticamente mai.

Ogni ciclo di sviluppo in termine tecnico viene chiamato anche **sprint**.

Nel nostro contesto scuola, adatteremo la lunghezza dello sprint in base alle esigenze del calendario scolastico.

## Meetings
Il ciclo di sviluppo Scrum prevede i seguenti incontri:
- planning meeting, all'inizio dello sprint
- review meeting, alla fine dello sprint
- daily meeting, ogni giorno

> Può esserci un ulteriore incontro chiamato "retrospettiva", dopo la review, dove si analizza cosa è andato bene e cosa male, e come migliorare.

### Planning meeting
Si decidono le **storie** ed i **task** da realizzare nello Sprint che sta iniziando.

#### Storie
Le storie sono la forma con cui si definiscono i requisiti in Scrum. Hanno un aspetto più informale rispetto ai requisiti classici, e si concentrano sulla _narrazione_ del progetto, in modo tale che ogni progetto non sia solo un insieme di cose da fare ma acquisisca un _senso_ chiaro e definito sia nelle menti sia del cliente che degli sviluppatori

Ogni storia ha la forma:
<center>
Come `qualcuno`, voglio che `qualcosa` perché `valore`.
</center>

Come ogni storia che conosciamo, gli elementi fondamentali sono: i personaggi (_qualcuno_), l'azione (_qualcosa_) ed il fine che muove il personaggio all'azione (_valore_). Le storie devono essere scritte in modo che possano essere comprese da chiunque, quindi non devono contenere termini tecnici, perché sono il mezzo di comunicazione scritto privilegiato tra tutti i membri del team, dell'azienda e con il cliente.

Dopo aver definito le storie, queste vanno messe in **priorità** dal Product Owner. Si comincieranno ad implementare quindi prima le storie con priorità più alta.

#### Task
Le storie solitamente, prima di essere implementate, devono essere suddivise in _task_ operativi che contengono invece i dettagli su cosa in pratica deve essere fatto. I task possono contenere anche un linguaggio tecico, perché sono strumenti interni al team di sviluppo, di solito non escono fuori da quest'ambito.

#### Punti
Ad ogni storia o task vengono inoltre assegnati dei punti, che ne definiscono la _difficoltà_. Ad esempio:
- 1 punto: facilissimo
- 2 punti: facile
- 4 punti: impegnativo
- 8 punti: esageratamente impegnativo

Si preferisce assegnare punti e non ore alle singole storie, perché per gli esseri umani è molto più facile valutare la difficoltà di un compito che il suo tempo di esecuzione, e quindi alla fine la stima viene più precisa. Inoltre evita che si creeino situazioni di tensione, spesso inutili, nel caso in cui i tempi non vengano rispettati esattamente.

Ogni team ha un proprio numero di punti che riesce a completare in uno sprint, chiamato velocità (_velocity_). La velocity viene calcolata empiricamente dopo un certo numero di sprint. Per ogni sprint, si possono pianificare un numero di punti uguale o inferiori alla velocity fissata, **mai** un numero maggiore: infatti non è teoricamente corretto prevedere di fare straordinari già in fase di planning. Scrum insiste molto sul fatto che il ritmo di lavoro deve essere sostenibile, e che non bisogna fare continuamente sforzi oltre le proprie possibilità.

#### Story/task owner
Ad ogni storia o task si assegna un proprietario (owner), in modo che sia chiaro chi è che ha la responsabilità che quella storia o task venga completata.

#### Note
Le storie devono essere tra di loro quanto più possibili indipendenti, da eseguire in serie o in parallelo, ma non intrecciarsi fra di loro. Se questo accade, conviene spezzare le storie, per renderle indipendenti.

### Esecuzione
In questa fase ogni membro del team di sviluppo implementa le proprie storie o task. Quando comincia l'implementazione, lo sviluppatore segna il task o la storia in "Work in progress" nel cartellone del team o qualche altro strumento di tracciamento, anche digitale. Man mano che li completa, segna la storia o task come completato (done) e passa al successivo. Ad ogni momento, ognuno deve essere su un unico task.

Non è possibile cambiare i storie o task in questa fare, per nessun motivo, neanche da parte dell'amministratore dell'azienda o del cliente: è cura dello Scrum Master assicurarsi di questo.

### Review meeting
Alla fine della fase di esecuzione, i vari owner dimostrano le storie e task **che hanno completato** al Product Owner, che valuta se sono effettivamente complete come si aspetta il cliente, o c'è qualcosa di incogruente e devono essere riviste. Quest'ultime devono essere sempre ri-pianificate nello sprint successivo e ricominciare il ciclo, non possono per nessun motivo essere "corrette al volo", perché in questo modo si perde facilmente il controllo della situazione.

Attenzione: **non** si possono dimostrare **storie incomplete** (non in done), anche se manca solo il 10%: una storia o è completa, o è fallita, nessuna via di mezzo. Una storia parzialmente completa si considera fallita e si rivaluta nella pianificazione successiva. Il Product Owner decide se le storie sono effettivamente complete o no.

Lo Scrum Master si assicura che tutto il processo sia eseguito correttamente.

### Daily meeting
C'è un ulteriore importante cerimonia Scrum che si celebra ogni mattina, il _"Daily Meeting"_: è un incontro giornaliero di massimo 15 minuti, _interno al team_ (gli esterni non possono partecipare), in cui ci si assicura che tutto stia procedendo come previsto. Visto che i partecipanti devono stare in piedi per favorire la concentrazione, viene anche detto "Stand-up meeting". Noi non faremo ogni giorno perché sarebbe molto difficile da eseguire nel contesto scolastico, ma vediamo se riusciamo a inserirlo in qualche occasione.
