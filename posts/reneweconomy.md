# Germania 2045: come Energy Web può rendere verificabile la transizione dai combustibili fossili

La Germania ha presentato una roadmap per accompagnare il Paese verso l'uscita progressiva da petrolio, carbone e gas, confermando l'obiettivo della **neutralità climatica entro il 2045**.

Il piano interessa diversi settori dell'economia: energia, industria, edifici e trasporti. L'obiettivo non consiste quindi soltanto nella sostituzione delle centrali fossili con impianti rinnovabili, ma in una trasformazione molto più ampia del sistema energetico tedesco.

In questo scenario emerge una domanda tecnologica importante:

> **Come possiamo verificare in modo continuo, trasparente e interoperabile che la transizione energetica stia realmente producendo i risultati dichiarati?**

È proprio in questo spazio che tecnologie come **Energy Web X, Verified Compute Cloud, Green Proofs e Digital Spine** possono trovare un possibile ruolo.

---

## La Germania parte da un sistema ancora fortemente dipendente dai combustibili fossili

La roadmap arriva in un momento in cui la Germania mantiene ancora una forte dipendenza da petrolio, gas e carbone.

Secondo i dati riportati nell'articolo, nel 2025 i combustibili fossili rappresentavano ancora più di tre quarti dell'energia consumata dal Paese. Le importazioni coprivano inoltre circa il 98% del petrolio, il 95% del gas fossile e tutto il carbone fossile utilizzato.

La transizione comporta quindi una trasformazione strutturale:

* elettrificazione dei trasporti;
* maggiore utilizzo delle pompe di calore;
* crescita di eolico e fotovoltaico;
* accumulo energetico;
* maggiore flessibilità della rete;
* trasformazione dell'industria;
* progressiva riduzione del gas e del carbone;
* sviluppo di combustibili a basse emissioni, come l'idrogeno.

Il vantaggio dell'elettrificazione è che tecnologie come veicoli elettrici e pompe di calore possono utilizzare l'energia in modo più efficiente rispetto alla combustione diretta dei combustibili fossili.

Ma un sistema energetico più elettrificato è anche un sistema molto più complesso dal punto di vista digitale.

---

# Il problema non è soltanto produrre energia rinnovabile

Nel 2025 eolico, fotovoltaico, biomassa e idroelettrico hanno coperto circa il **56% del consumo elettrico tedesco**.

Il problema dei prossimi anni sarà quindi sempre più quello di coordinare milioni di risorse distribuite:

* impianti fotovoltaici;
* parchi eolici;
* batterie;
* veicoli elettrici;
* colonnine di ricarica;
* pompe di calore;
* edifici intelligenti;
* impianti industriali;
* sistemi di accumulo;
* sistemi di gestione della domanda.

Tutte queste risorse producono o consumano dati.

La questione diventa:

> **Come facciamo a sapere che quei dati sono autentici, che appartengono realmente a quell'impianto e che il risultato calcolato sulla base di quei dati è verificabile?**

Qui la blockchain può avere un ruolo diverso da quello normalmente associato alle criptovalute.

Non è necessario mettere tutti i dati energetici sulla blockchain.

È molto più interessante utilizzare una blockchain e un'infrastruttura decentralizzata per **registrare identità, prove, risultati e verifiche**.

---

# Energy Web: dalla blockchain alla verifica dei dati energetici

L'evoluzione di Energy Web va proprio in questa direzione.

Il **Verified Compute Cloud (VCC)** è progettato per trasformare un'affermazione o un calcolo in una prova verificabile.

Il modello prevede che diversi operatori indipendenti eseguano lo stesso calcolo e confrontino i risultati. Il risultato viene quindi raggiunto attraverso un processo di consenso e ancorato alla blockchain.

Un aspetto particolarmente importante è che i dati operativi originali possono rimanere nell'ambiente del proprietario.

Non è quindi necessario rendere pubblici tutti i dati industriali o energetici.

Il sistema può verificare il risultato senza esporre necessariamente i dati sottostanti.

Questo apre possibilità interessanti per un sistema energetico come quello tedesco.

---

# Una possibile infrastruttura digitale per la Germania 2045

Possiamo immaginare una struttura composta da diversi livelli:

```text
                   SISTEMA ENERGETICO TEDESCO
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
      TSO                    DSO                 MERCATI
        │                     │                     │
        └─────────────────────┼─────────────────────┘
                              │
                       DIGITAL SPINE
                              │
                dati e identità verificabili
                              │
                    VERIFIED COMPUTE
                              │
             ┌────────────────┼────────────────┐
             │                │                │
          Node A           Node B           Node C
             │                │                │
             └────────────────┼────────────────┘
                              │
                           EWX
                              │
                              ↓
                    PROOF VERIFICABILE
```

Questa architettura non sostituirebbe i sistemi esistenti degli operatori energetici.

Avrebbe invece il compito di creare un **livello comune di interoperabilità e verifica**.

---

# Digital Spine: collegare un sistema energetico sempre più distribuito

Uno degli elementi fondamentali potrebbe essere **Energy Web Digital Spine**.

Digital Spine è progettato come infrastruttura decentralizzata per lo scambio sicuro di dati tra sistemi, organizzazioni e mercati.

L'obiettivo è superare il modello in cui ogni operatore deve creare una connessione separata con ogni altro operatore.

Invece di:

```text
A ↔ B
A ↔ C
A ↔ D
B ↔ C
B ↔ D
C ↔ D
```

si può utilizzare una dorsale condivisa:

```text
             Digital Spine
          /       |       \
         /        |        \
       TSO       DSO      DER
                           │
              ┌────────────┼────────────┐
              ↓            ↓            ↓
             EV         Battery        PV
```

Digital Spine utilizza identità decentralizzate, controllo degli accessi, governance degli schemi dati e scambio dati governato.

Questo è particolarmente rilevante quando aumentano le risorse energetiche distribuite.

---

# Energy Web X: trasformare i dati in prove verificabili

Il ruolo di **Energy Web X** può essere visto come il livello che permette di coordinare e verificare i processi computazionali necessari per trasformare i dati in risultati verificabili.

Immaginiamo, per esempio, che un'azienda dichiari:

> "Il mio stabilimento ha utilizzato il 90% di energia rinnovabile nel mese di settembre."

Il sistema potrebbe ricevere i dati relativi a:

* consumo elettrico;
* produzione rinnovabile;
* provenienza dell'energia;
* intervallo temporale;
* identificazione degli impianti;
* metodologia utilizzata.

Una metodologia digitale definita e firmata stabilisce come effettuare il calcolo.

I nodi di Verified Compute eseguono quindi il calcolo indipendentemente.

Il risultato può diventare una **proof verificabile**.

In questo modo non è necessario fidarsi esclusivamente dell'autodichiarazione dell'azienda.

---

# Dalla dichiarazione alla prova

Il cambiamento concettuale è importante.

### Modello tradizionale

```text
Azienda
   ↓
Report
   ↓
Audit periodico
   ↓
Certificato
```

### Modello basato su verifica continua

```text
Dati operativi
      ↓
Metodologia digitale
      ↓
Verified Compute
      ↓
Verifica indipendente
      ↓
Consensus
      ↓
Proof
      ↓
Regolatore / cliente / mercato
```

Energy Web descrive VCC proprio come un'infrastruttura capace di trasformare dati operativi e regole di calcolo in risultati verificabili, mantenendo i dati originali all'interno dell'ambiente del soggetto che li possiede.

---

# Un possibile sistema di monitoraggio della transizione fossile

Una delle applicazioni più interessanti potrebbe essere la costruzione di un sistema digitale per monitorare la riduzione dell'utilizzo di combustibili fossili.

Per esempio:

```text
              IMPIANTO INDUSTRIALE

       Gas ────────────────┐
                            │
       Elettricità ────────┤
                            │
       H₂ ─────────────────┤
                            ↓
                     DATI OPERATIVI
                            │
                            ↓
                     METODOLOGIA
                            │
                            ↓
                    VERIFIED COMPUTE
                            │
                 ┌──────────┴──────────┐
                 ↓                     ↓
              Node A                Node B
                 │                     │
                 └──────────┬──────────┘
                            ↓
                         EWX
                            ↓
                  RISULTATO VERIFICATO
```

Il risultato potrebbe attestare, secondo una metodologia definita:

* quantità di combustibile fossile utilizzato;
* energia prodotta;
* energia rinnovabile utilizzata;
* quota di elettrificazione;
* emissioni associate;
* eventuale utilizzo di idrogeno;
* riduzione rispetto a un periodo precedente.

La metodologia e i criteri dovrebbero naturalmente essere definiti dagli organismi competenti. Energy Web fornirebbe l'infrastruttura tecnologica per eseguire e verificare il calcolo.

---

# Rinnovabili: dal "green" al matching verificabile

Un'altra applicazione riguarda l'energia rinnovabile.

Non basta sapere che un'azienda ha acquistato una certa quantità di energia rinnovabile.

Con un sistema digitale più avanzato si può cercare di verificare:

**quando è stata prodotta l'energia?**

**dove è stata prodotta?**

**quanto è stato consumato?**

**il consumo può essere associato alla produzione secondo le regole stabilite?**

Energy Web sta sviluppando infrastrutture di verifica per mercati dell'energia e commodity ambientali attraverso Green Proofs e Verified Compute Cloud.

Questo potrebbe essere particolarmente utile in un sistema tedesco con una quota crescente di produzione variabile da eolico e fotovoltaico.

---

# Batterie, EV e pompe di calore

La transizione energetica tedesca non significa soltanto sostituire le centrali.

Significa anche trasformare milioni di consumatori in **risorse energetiche flessibili**.

Un veicolo elettrico può essere:

* consumatore;
* batteria;
* risorsa di flessibilità.

Una batteria domestica può:

* accumulare energia;
* restituirla alla rete;
* partecipare a un programma di flessibilità.

Una pompa di calore può modificare il proprio profilo di consumo in funzione delle condizioni della rete, quando tecnicamente e contrattualmente possibile.

Digital Spine è progettato proprio per supportare l'interoperabilità e il coordinamento delle **Distributed Energy Resources (DER)** e dei servizi di rete.

---

# Energy Web ha già esperienza in Germania

Un elemento interessante è che questa prospettiva non parte completamente da zero.

Energy Web ha già partecipato a progetti con la **German Energy Agency (dena)**.

Tra questi viene indicato il **Blockchain Identity Ledger**, nel quale Energy Web ha contribuito a un registro decentralizzato per identificare asset energetici come impianti fotovoltaici e collegare la loro identità a dati verificabili.

Energy Web indica inoltre il progetto **DIVE**, dedicato all'infrastruttura di identità decentralizzata per permettere a società energetiche e asset connessi di scambiare credenziali verificabili.

Questo rappresenta un punto importante:

> **la tecnologia Energy Web non sarebbe completamente estranea all'ecosistema energetico tedesco.**

Esiste già una storia di collaborazione su identità digitale e asset energetici.

---

# Un precedente ancora più interessante: OMEGA-X

Energy Web indica inoltre **OMEGA-X**, progetto Horizon Europe nel quale il proprio Verified Compute Cloud è stato utilizzato per consentire a impianti fotovoltaici, caricabatterie EV e asset energetici distribuiti di partecipare a servizi federati di dati energetici.

Il progetto ha incluso anche processi relativi all'emissione, tracciamento e ritiro di garanzie di origine per energia rinnovabile.

Questo è molto vicino alla direzione richiesta da un sistema energetico sempre più digitalizzato.

---

# Anche il settore industriale potrebbe beneficiarne

Il piano tedesco riguarda anche l'industria.

Qui il valore della tecnologia può aumentare ulteriormente perché le aziende devono gestire contemporaneamente:

* energia;
* emissioni;
* supply chain;
* materie prime;
* certificazioni;
* carbon accounting;
* requisiti normativi.

Energy Web sta già sviluppando applicazioni di Verified Compute per ambiti come **CBAM, CSRD e supply chain**, con l'obiettivo di produrre evidenze verificabili e utilizzabili nei processi di compliance.

La stessa infrastruttura potrebbe quindi essere adattata a diversi settori della transizione tedesca.

---

# Non una nuova blockchain energetica, ma un livello di fiducia

Il punto fondamentale è evitare un equivoco.

Energy Web X non dovrebbe essere considerato come una blockchain che sostituisce:

* la rete elettrica;
* i TSO;
* i DSO;
* i mercati energetici;
* i sistemi SCADA;
* i sistemi ERP;
* i database aziendali.

Il suo ruolo può essere complementare.

```text
SISTEMI ESISTENTI
       │
       ↓
Digital Spine
       │
       ↓
Dati verificabili
       │
       ↓
Verified Compute
       │
       ↓
Energy Web X
       │
       ↓
Proof verificabile
```

La blockchain diventa quindi il **livello di fiducia**, non il sistema operativo della rete elettrica.

---

# Un possibile "Germany 2045 Verification Layer"

Da questa prospettiva si potrebbe immaginare un'infrastruttura digitale denominata, ad esempio:

## Germany 2045 Verification Layer

Un sistema capace di produrre prove verificabili relative a:

| Area              | Possibile verifica                       |
| ----------------- | ---------------------------------------- |
| Elettricità       | Produzione e consumo rinnovabile         |
| Industria         | Consumo energetico ed emissioni          |
| Trasporti         | Elettrificazione e utilizzo di energia   |
| Edifici           | Elettricità, pompe di calore e consumi   |
| Gas               | Riduzione progressiva dell'utilizzo      |
| Idrogeno          | Provenienza e caratteristiche dichiarate |
| Batterie          | Origine e ciclo di vita                  |
| EV                | Identità e capacità degli asset          |
| Rete              | Flessibilità fornita dalle DER           |
| Carbon accounting | Calcoli verificabili delle emissioni     |

Non sarebbe necessario pubblicare tutti i dati.

Il sistema potrebbe pubblicare principalmente:

**metodologia + risultato + timestamp + identità + prova crittografica.**

---

# Il vantaggio per regolatori e cittadini

Un sistema di questo tipo potrebbe creare un nuovo modello di trasparenza.

Un'autorità, un'azienda o un altro soggetto autorizzato potrebbe verificare:

```text
Chi ha prodotto il dato?
        ↓
Quale asset?
        ↓
Quale metodologia?
        ↓
Quale versione delle regole?
        ↓
Quale calcolo?
        ↓
Quali operatori lo hanno verificato?
        ↓
Quale risultato?
```

Energy Web descrive VCC come un sistema nel quale le metodologie sono versionate e firmate, i calcoli sono eseguiti da operatori indipendenti e il risultato viene pubblicato come prova verificabile.

Questo può ridurre la distanza tra **dato energetico** e **dato verificato**.

---

# Dalla roadmap politica all'infrastruttura digitale

La roadmap tedesca stabilisce una direzione politica e industriale: uscire progressivamente da petrolio, carbone e gas e raggiungere la neutralità climatica entro il 2045.

Energy Web non può stabilire gli obiettivi della Germania e non sostituisce le autorità che devono definire metodologie, regolamenti e criteri di misurazione.

Può però contribuire alla parte tecnologica:

> **rendere i dati della transizione più interoperabili, verificabili e trasferibili tra gli attori del sistema energetico.**

La combinazione potrebbe essere:

```text
GERMANIA 2045
      │
      │ obiettivi e regole
      ↓
METODOLOGIE DIGITALI
      │
      ↓
DIGITAL SPINE
      │
      │ dati + identità
      ↓
VERIFIED COMPUTE CLOUD
      │
      │ verifica indipendente
      ↓
ENERGY WEB X
      │
      ↓
VERIFIABLE PROOFS
      │
      ├── aziende
      ├── operatori energetici
      ├── regolatori
      ├── auditor
      └── cittadini
```

---

# Conclusione

La transizione energetica tedesca rappresenta soprattutto una grande sfida industriale e infrastrutturale. Ma è anche una **sfida digitale**.

Man mano che aumentano gli impianti rinnovabili, i veicoli elettrici, le batterie, le pompe di calore e le risorse distribuite, aumenta anche la quantità di dati che deve essere scambiata e verificata.

In questo contesto, **Energy Web X non deve necessariamente essere visto come una blockchain per l'energia**, ma come parte di un'infrastruttura più ampia per trasformare i dati energetici in **prove verificabili**.

La combinazione di:

* **Digital Spine** per l'interoperabilità e lo scambio dei dati;
* **identità decentralizzate** per identificare operatori e asset;
* **Verified Compute Cloud** per verificare i calcoli;
* **Green Proofs** per gli attributi ambientali;
* **Energy Web X** per l'infrastruttura decentralizzata di verifica;

potrebbe fornire un livello digitale complementare ai sistemi energetici esistenti.

La vera innovazione non sarebbe quindi semplicemente **"mettere l'energia sulla blockchain"**.

Sarebbe creare un sistema nel quale una dichiarazione come:

> *"questo impianto ha utilizzato questa quantità di energia rinnovabile e ha ridotto le proprie emissioni di questa quantità"*

possa diventare una **prova digitale verificabile, trasferibile e controllabile da soggetti diversi senza dover ripetere ogni volta l'intero processo di audit**.

Per un percorso lungo fino al 2045, questa capacità di misurare e verificare continuamente i progressi potrebbe diventare importante quanto la capacità di produrre nuova energia pulita.
