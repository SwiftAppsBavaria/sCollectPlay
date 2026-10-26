# Informativa sulla privacy di sCollectPlay e sCollectPlay Lite

Aggiornamento: 2026-10-23

## In breve

sCollectPlay e sCollectPlay Lite non raccolgono, non memorizzano e non trasmettono **alcun**
dato personale. Le app lavorano esclusivamente sul tuo Mac o PC Windows. Non ci sono account, nessun
collegamento al cloud, nessun servizio di analisi e nessuna pubblicità.

## Quali dati elabora l’app

L’app legge i file multimediali nelle cartelle che le hai espressamente affidato —
scegliendole nella finestra di apertura: una cartella da scansionare, un XML di iTunes o di
Apple Music oppure una libreria sCollect. Vengono letti il nome del file, la dimensione del
file, la data e i metadati del file, per un XML o una libreria anche le relative
informazioni di catalogo.

Senza una tua scelta l’app non accede ad alcun file. macOS lo impone attraverso la sandbox
dell’app.

## Che cosa l’app deposita sul tuo Mac

- **Impostazioni e posizioni delle finestre** nella cartella protetta dell’app.
- **Il permesso di macOS di riaprire le tue cartelle al prossimo avvio.** Vengono
  memorizzati i percorsi delle cartelle, non i contenuti dei file. Solo così l’app non deve
  chiedere di nuovo a ogni avvio.
- **In sCollectPlay inoltre:** l’elenco delle cartelle, dei file XML e delle librerie usati
  di recente, le tue playlist, l’ordinamento e lo stato del browser a colonne — anch’essi
  nella cartella protetta dell’app.

Tutto questo viene rimosso quando elimini l’app.

## Due autorizzazioni che possono far sorgere domande

**Accesso alla rete.** L’app lo richiede perché senza questa autorizzazione macOS mostra
vuota la finestra di aiuto integrata — l’aiuto viene visualizzato da un componente di
sistema che ne ha bisogno, anche se carica soltanto file del programma stesso. Di sua
iniziativa l’app **non richiama alcun indirizzo su internet**, non scarica nulla e non
segnala nulla.

Le cartelle su unità di rete (SMB, NFS) l’app le raggiunge attraverso il file system del tuo
Mac, non tramite una connessione propria.

**Controllo di Apple Music.** Quando invii una selezione ad Apple Music come playlist, l’app
apre Apple Music con una playlist generata e, se lo desideri, sostituisce una playlist con
lo stesso nome già presente lì. Per questo macOS richiede il tuo consenso, che viene chiesto
la prima volta. L’app non controlla altri programmi.

## I tuoi file

L’app non scrive tag e non modifica i metadati dei tuoi file.

Se apri una libreria sCollect, l’app salva le tue valutazioni e riproduzioni (con data e ora) nel file `rueckmeldungen.json` nella cartella di quella libreria, perché sCollect possa riprenderle. Non modifica né la libreria stessa né i file multimediali, e nulla di tutto ciò lascia il tuo computer.

Solo se elimini espressamente un file, l’app lo sposta nel Cestino di macOS e lo toglie
dall’elenco; se proviene da una libreria sCollect, anche il suo catalogo viene adeguato di
conseguenza. Sulle unità senza Cestino l’app chiede prima se il file deve essere eliminato
definitivamente.

## Su Windows

Le sezioni precedenti descrivono il Mac. Su Windows, sCollectPlay e sCollectPlay Lite salvano quanto segue
esclusivamente in locale, nella cartella dati dell’app (`%LOCALAPPDATA%\Packages\<pacchetto>\LocalState` e `Settings`):

- **Impostazioni e posizione della finestra.**
- **L’ultima sorgente scelta** — cartelle scansionate, un file XML di iTunes o una libreria sCollect — e il risultato
  dell’ultima scansione.
- **L’associazione tra le cartelle Mac di una libreria e cartelle del tuo PC** (solo percorsi di cartelle).
- **In sCollectPlay inoltre:** le tue playlist, l’elenco delle cartelle, dei file XML e delle librerie usati di
  recente, l’ordinamento e lo stato del browser a colonne.
- **Un registro degli errori** (`fehler.log`), che resta sul tuo PC.

Tutto questo viene rimosso quando disinstalli l’app.

L’app legge file multimediali e file XML solo dove li selezioni tu; una libreria sCollect viene soltanto letta, tranne il file `rueckmeldungen.json` descritto in «I tuoi file». Non
stabilisce connessioni di rete proprie, non usa servizi di analisi e non mostra pubblicità. I file che Windows non
riproduce da sé vengono passati al programma predefinito per quel tipo di file, che scegli in Windows.

Se in sCollectPlay esporti una playlist per VLC o per un dispositivo, l’app ne copia i file nella cartella che
scegli.

Solo se elimini espressamente un file multimediale da cartelle scansionate o da un XML di iTunes, l’app lo sposta nel
Cestino di Windows; su un’unità senza Cestino, per esempio in rete, viene eliminato definitivamente dopo una conferma.
Una libreria sCollect non viene modificata.

## Microsoft Store

Su Windows, acquisto (sCollectPlay), download e aggiornamenti passano attraverso il Microsoft Store; per questi vale
l’informativa sulla privacy di Microsoft. sCollectPlay Lite è gratuita e cita la versione completa.

## Nessuna trasmissione, nessuna analisi

Non c’è pubblicità, non ci sono servizi di analisi, non ci sono rapporti di arresto anomalo
verso terzi e non ci sono account.

## Contatto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
