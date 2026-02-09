# Segnalazioni Mancata attribuzione OSM

Nella sezione [issues](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/issues) è possibile inserire una nuova segnalazione di violazione del copyright che sarà poi presa in gestione dal team. Verrà inviato il testo riportato nel file [MAIL.md](MAIL.md). L'utente del team utilizza l'indirizzo email indicato di fianco al nome.

Tale processo non vuole sostituire quello riconsciuto e indicato nella pagina [wiki](https://wiki.openstreetmap.org/wiki/Lacking_proper_attribution) di OpenStreetMap, ma vuole offrire un'altra opzione per raccogliere le segnalazioni.

GitHub è uno software di proprietà di Microsoft, per inserire una nuova segnalazione è necessario registrarsi. Per offire il servizio a tutti per tutti gli utenti è possibile insere una segnalazione nella [wiki](https://wiki.openstreetmap.org/wiki/IT_talk:Lacking_proper_attribution) di OSM.

Si raccomanda di riempire tutti i campi richiesti nel template delle issues per velocizzare il lavoro.

Nel caso di mappe online dopo la mancata risposta alla terza segnalazione verrà indicato che si procederà nel giro di 3 giorni a rimuovere l'autorizzazione all'utilizzo delle tile tramite segnalazione al repository https://github.com/openstreetmap/tile-attribution

## Team
- Anisa Kuci - Responsabile OpenStreetMap per Wikimedia Italia - anisa.kuci at wikimedia.it
- Lorenzo Stucchi - Coordinatore Nazionale OpenStreetMap per Wikimedia Italia - lorenzo.stucchi at wikimedia.it

## Processo di gestione delle segnalazioni

Si raccomanda prima di ogni passaggio di verificare se l'attribuzione è ancora mancante in quel momento. Può essere che, senza che ci sia stata una risposta, la mancata attribuzione sia stata corretta.

### Arrivo Segnalazione

Tramite l'apertura di una nuova issue si apre una nuova segnalazione, la label [Da contattare](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Da%20contattare) sarà assegnata in automatico.

### Gestione issue e avvio contatto

Una persona del Team prende in carico la segnalazione:

1. Assegnare a sé stessi la issue in modo da vedere che è stata presa in carico
2. Inviare la mail secondo uno dei template [MAIL.md](MAIL.md) o [MAIL v2.md](MAIL%20v2.md)
3. Rimuovere la label [Da contattare](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Da%20contattare) e aggiungere [Inviata segnalazione](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Inviata%20segnalazione)
4. Per meglio tracciare le diverse tipologie di issue è utile anche aggiungere la label corrispondente alla categoria del prodotto senza attribuzione. Tale label è utile anche per capire le possibili azioni da adottare:

   * [Mappa online](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Mappa%20online)
   * [Mappa cartacea](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Mappa%20cartacea)
   * [Screenshot o PDF online](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Screenshot%20o%20PDF%20online)
5. In maniera facoltiva si può inserire un commento nella issue affinché il bot mandi una mail di segnalazione dopo 14 giorni se non ci sono stati aggiornamenti. Per farlo inserire il messaggio `/remind me in 2 weeks`. Il bot andrà in automatico ad aggiungere la label [reminder](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/reminder).

### Incompletezze nella issue creata

Vi è la possibilità di imprecisioni o errori nella issue generalmente catalogabili in questi casi, per i quali è possibile chiedere ulteriori informazioni a chi ha aperto l'issue:

* mancanza di un punto di contatto, da segnalare con la label [Contatto mancante](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Contatto%20mancante)
* errore nella segnalazione, l'attribuzione c'era e non è stata vista: usare la label [Contatto non avvenuto](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Contatto%20non%20avvenuto) e chiudere la issue
* mancata attribuzione già segnalata in un'altra issue: usare la label [doppia](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/doppia) e chiudere la issue
* utilizzo legittimo dei dati di OSM che non rappresenta una violazione: usare la label [Fair Use](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Fair%20Use) e chiudere la issue

### Risposta da contatto

In caso di risposta entro i 14 giorni si deve rimuovere la label [Inviata segnalazione](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Inviata%20segnalazione) ed aggiungere la label [Ricevuta risposta](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Ricevuta%20risposta).

### Risoluzione e chiusura

Dopo la discussione si può arrivare:

* a un'attribuzione completa e corretta da marchiare con la label [Attribuzione corretta](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Attribuzione%20corretta)
* a un'attribuzione parziale ma sufficiente da marchiare con la label [Attribuzione parziale](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Attribuzione%20parziale)
* a una rimozione della mappa [Mappa rimossa](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Mappa%20rimossa)

### Mancata risposta o difficoltà nei contatti

Se dopo 14 giorni dalla prima mail non vi è stata alcuna risposta è necessario inviare una nuova mail, segnalabile tramite la label [Inviata seconda mail segnalazione](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Inviata%20seconda%20mail%20segnalazione).

Dopo ulteriori 14 giorni senza risposta, si possono tentare altri canali più formali, come la PEC.

Se dopo più di un mese dalla prima segnalazione non ci siano stati risultati si può procedere in diversi modi a seconda della violazione:

* per le [Mappe online](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Mappa%20online) si può valutare la segnalazione a OSMF come descritto al paragrafo successivo
* per le [Mappe cartacee](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Mappa%20cartacea) e gli [Screenshot o PDF online](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Screenshot%20o%20PDF%20online) si possono tentare nuovi canali oppure riportare la issue con la label [congelato](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/congelato) in attesa di nuovi canali.

### Segnalazione a OSMF

Per le mappe online che utilizzano i tile forniti da OSMF è possibile richiedere il blocco, si dovrà prima:

* inviare una nuova mail avvertendo che nel giro di 3 giorni si andrà a rimuovere l'autorizzazione all'utilizzo dei tile
* se non c'è stata alcuna risposta andare ad aprire una issue nella repository [openstreetmap/tile-attribution](https://github.com/openstreetmap/tile-attribution)
* inserire nella issue la label [Segnalata a OSMF](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Segnalata%20a%20OSMF).

Fondamentale documentare tutte le date delle mail inviate nelle issue in modo che poi la segnalazione a OSMF abbia tutti gli elementi per far partire immediatamente il blocco.

### Interruzione del dialogo

Durante lo scambio di mail può accadere che non si riceva più una risposta. Attendere almeno 2 settimane dall'ultima risposta e in quel caso è fondamentale andare a riscrivere dando un ultimatum, riportando quanto accaduto nella issue con la label [Inviato sollecito](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Inviato%20sollecito). A quel punto si possono attendere ancora 2 settimane e trattare la issue come se non ci sia mai stata una risposta.

### Promessa di correzione

Durante lo scambio di mail viene indicato che avverrà la correzione in una data o che verrà fatto poi. Riportare la segnalazione e usare la label [Controllare attribuzione](https://github.com/osmItalia/Segnalazioni-Mancata-attribuzione-OSM/labels/Controllare%20attribuzione).
