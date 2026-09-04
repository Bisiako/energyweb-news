# Il Digital Product Passport: la “carta d’identità digitale” dei prodotti europei

Immaginate di acquistare una batteria per un'auto elettrica e, invece di avere soltanto una confezione e un manuale, poter conoscere in modo semplice tutta la sua storia: **da quali materiali è composta, da dove provengono, chi l'ha prodotta, come è stata utilizzata, se è stata riparata e come può essere riciclata**.

È questa, in sostanza, l'idea alla base del **Digital Product Passport (DPP)**, il Passaporto Digitale del Prodotto che l'Unione Europea sta introducendo nell'ambito delle nuove politiche sulla sostenibilità e sull'economia circolare.

## Una carta d'identità per ogni prodotto

Il Digital Product Passport può essere immaginato come una **carta d'identità digitale collegata a un prodotto fisico**.

Attraverso un identificativo, un QR code o un altro sistema di accesso, sarà possibile collegarsi alle informazioni relative a quel prodotto.

L'obiettivo è rendere più trasparente il percorso di un prodotto durante tutto il suo ciclo di vita.

Per esempio, nel caso di una batteria, potrebbero essere disponibili informazioni sui materiali utilizzati, sulla provenienza delle materie prime, sulla produzione, sull'utilizzo e, alla fine della sua vita, sulle modalità corrette di recupero e riciclo.

Non si tratta quindi semplicemente di aggiungere un QR code sulla confezione. Dietro quel codice dovrà esistere un sistema in grado di **raccogliere, conservare, condividere e verificare le informazioni**.

## Perché l'Europa ne ha bisogno?

Oggi le informazioni su un prodotto sono spesso distribuite tra molti soggetti diversi.

Il produttore conosce alcuni dati, il fornitore delle materie prime ne conosce altri, il distributore ne possiede altri ancora e il riciclatore potrebbe aver bisogno di informazioni completamente diverse.

Il problema è quindi fare in modo che questi soggetti possano **scambiarsi le informazioni senza dover utilizzare necessariamente lo stesso software o affidarsi tutti a un'unica azienda**.

È proprio questo uno degli aspetti più interessanti del progetto europeo.

## Non ci sarà necessariamente un unico grande database

Un errore facile da fare è immaginare il Digital Product Passport come un enorme database europeo nel quale verranno memorizzate tutte le informazioni di tutti i prodotti.

L'architettura prevista è invece più distribuita.

Il sistema europeo può mantenere i riferimenti necessari per individuare il passaporto, mentre le informazioni vere e proprie possono rimanere presso le aziende che le hanno prodotte o presso i loro fornitori di servizi.

In questo modo ogni azienda può continuare a mantenere il controllo sui propri dati, pur rendendoli disponibili quando necessario.

È un po' come avere una rubrica che indica **dove trovare un'informazione**, senza necessariamente conservare tutta l'informazione nella rubrica stessa.

## Il problema degli strumenti tecnologici

Per costruire un sistema di questo tipo servono moltissimi strumenti diversi.

Servono sistemi per identificare i prodotti, sistemi per gestire le autorizzazioni, strumenti per conservare i dati, sistemi per scambiare informazioni tra aziende e strumenti per verificare che determinati dati siano affidabili.

Il rischio è che ogni azienda costruisca il proprio sistema completamente diverso dagli altri.

In questo scenario, un produttore potrebbe utilizzare un determinato software, un fornitore un altro e un riciclatore un terzo sistema, rendendo molto difficile lo scambio delle informazioni.

Per questo motivo l'Europa punta molto sull'**interoperabilità** e sugli **standard aperti**.

In parole semplici: sistemi diversi devono essere in grado di parlarsi.

## Nasce OpenDPP Catalogue

È in questo contesto che si inserisce **OpenDPP Catalogue**, sviluppato nell'ambito del progetto europeo CIRPASS-2 con il contributo di Energy Web.

Si tratta di un catalogo pubblico che raccoglie **componenti software open-source** che possono essere utilizzati per costruire sistemi di Digital Product Passport.

L'articolo segnala che il catalogo conta già più di 40 soluzioni e continua a crescere.

L'idea è piuttosto semplice: invece di costringere ogni organizzazione a partire da zero, si crea una sorta di **cassetta degli attrezzi digitale**.

Chi vuole costruire un sistema DPP può quindi cercare nel catalogo gli strumenti necessari per le diverse parti del progetto.

## Una vera “cassetta degli attrezzi”

Il catalogo contiene strumenti dedicati a diverse funzioni.

Alcuni servono a identificare un prodotto e a trovare le informazioni associate.

Altri permettono di verificare l'identità di una persona o di un'organizzazione e stabilire se ha il diritto di accedere a determinati dati.

Altri ancora si occupano della conservazione delle informazioni o della comunicazione tra sistemi diversi.

Ci sono inoltre strumenti dedicati ai cosiddetti *data spaces*, alle autorizzazioni, alla sicurezza e alla verifica dei dati.

L'importante è che questi componenti possano essere combinati tra loro.

È un approccio simile a quello con cui oggi costruiamo molti sistemi informatici: **non necessariamente si inventa tutto da zero, ma si assemblano componenti diversi che rispettano regole comuni**.

## Open-source non significa automaticamente “buono”

C'è però un altro problema.

Un progetto open-source può essere molto interessante, ma se non viene più aggiornato può diventare rischioso utilizzarlo in un sistema importante.

Per questo OpenDPP Catalogue indica anche lo stato di manutenzione dei progetti.

Le soluzioni vengono classificate come:

- **Active** – aggiornate negli ultimi sei mesi;
- **Stale** – nessun aggiornamento da sei a dodici mesi;
- **Inactive** – nessun aggiornamento da oltre dodici mesi.

Questo permette a chi sta progettando un sistema DPP di capire non soltanto **che cosa fa un determinato software**, ma anche se il progetto è ancora attivamente sviluppato.

È un'informazione particolarmente importante quando si deve costruire un'infrastruttura destinata a funzionare per molti anni.

## Il contributo di Energy Web

L'articolo presenta anche due tecnologie sviluppate da Energy Web.

La prima è **Energy Web Digital Spine**, un sistema pensato per facilitare lo scambio di informazioni tra organizzazioni diverse.

Immaginiamo una catena composta da:

**fornitore → produttore → distributore → riciclatore**

Ognuno possiede informazioni diverse.

Il sistema permette di stabilire quali informazioni possono essere inviate, da chi e a chi, senza che tutte le aziende debbano creare una serie di collegamenti separati tra loro.

Il vantaggio è soprattutto quello di evitare una situazione nella quale ogni nuovo partecipante richieda la creazione di una nuova integrazione informatica.

## Ma come facciamo a sapere se un dato è affidabile?

C'è poi un'altra questione fondamentale.

Supponiamo che il Digital Product Passport dichiari:

**“Questo prodotto contiene il 40% di materiale riciclato.”**

Chi ci garantisce che quel numero sia stato calcolato correttamente?

È qui che entra in gioco il secondo componente presentato nell'articolo, **Energy Web Verified Compute Cloud**.

L'obiettivo è permettere di verificare non soltanto il risultato finale, ma anche il metodo con cui quel risultato è stato ottenuto.

Questo può diventare particolarmente importante quando i dati contenuti nel passaporto vengono utilizzati da auditor, autorità pubbliche o altre aziende.

## Un cambiamento importante nel modo di conoscere i prodotti

Il Digital Product Passport potrebbe quindi rappresentare un cambiamento significativo.

Oggi, quando compriamo un prodotto, spesso conosciamo soltanto una piccola parte della sua storia.

In futuro potrebbe essere possibile avere accesso a molte più informazioni durante tutto il suo ciclo di vita.

Per il consumatore questo potrebbe significare maggiore trasparenza.

Per il produttore potrebbe significare maggiore responsabilità e la necessità di organizzare meglio i propri dati.

Per chi ripara o ricicla un prodotto potrebbe significare avere finalmente informazioni che oggi sono difficili da ottenere.

E per le autorità potrebbe diventare uno strumento per controllare meglio la conformità e la sostenibilità dei prodotti.

## La parte più interessante è forse quella che non si vede

Il QR code o l'identificativo che vedremo sul prodotto sarà soltanto la parte visibile del sistema.

Dietro ci sarà una rete molto più complessa di tecnologie e organizzazioni che dovranno collaborare.

Ed è proprio per questo che iniziative come OpenDPP Catalogue possono avere un ruolo importante: **mettere a disposizione una mappa degli strumenti disponibili e permettere a organizzazioni diverse di costruire sistemi compatibili tra loro**.

L'obiettivo finale non è creare un unico software per tutti.

È creare un ecosistema nel quale **software diversi possano collaborare seguendo regole e standard comuni**.

## Verso il 2027

Il processo europeo è già in corso.

L'articolo ricorda che il registro europeo del DPP è previsto operativo dal **20 luglio 2026**, mentre per diverse categorie di batterie il Digital Product Passport diventerà obbligatorio dal **18 febbraio 2027**.

Nel frattempo sono stati definiti anche nuovi standard europei dedicati agli aspetti fondamentali del sistema, come identificazione, scambio dei dati, API, interoperabilità, gestione degli accessi e autenticazione dei dati.

Il Digital Product Passport, quindi, non è più soltanto un'idea futuristica.

**È una delle infrastrutture digitali che l'Europa sta iniziando concretamente a costruire.**

E la vera sfida sarà fare in modo che questa nuova "carta d'identità digitale" dei prodotti non diventi un insieme di sistemi isolati, ma una rete aperta, interoperabile e utilizzabile da aziende grandi e piccole.