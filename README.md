# ArciTessereOCR+ — download

Questo repository contiene **solo i programmi pronti da installare**, non il codice sorgente.

ArciTessereOCR+ digitalizza le domande di iscrizione ARCI compilate a mano: legge l'immagine del modulo (scanner o fotocamera), riconosce i campi, li fa controllare e correggere e prepara i dati per l'esportazione in Excel o CSV.

## Scarica

Vai alla pagina **[Releases](../../releases/latest)** e scarica i file della versione più recente:

| File | Per cosa |
|---|---|
| `ArciTessereOCR-Setup-x.y.z.exe` | **Windows 10/11 a 64 bit** — installer (consigliato) |
| `ArciTessereOCR-x.y.z-windows-portatile.zip` | Windows, senza installazione: si scompatta e si lancia |
| `ArciTessereOCR-x.y.z.apk` | **Android 7.0 o più recente** — telefoni e tablet |
| `Manuale-ArciTessereOCR-x.y.pdf` | Manuale utente |

Le istruzioni di installazione (compresa quella su Android, che richiede di consentire l'installazione da fonte sconosciuta) sono nelle note di ogni Release e nel manuale.

## Segnalare un problema

Scrivi al referente del progetto indicando la versione (schermata *Informazioni*), cosa stavi facendo e, se c'è, il file `errori.log` (su Windows si trova in `%LOCALAPPDATA%\ArciTessereOCR\it.arcitessereocr.app\Data\`). Su Android indica anche il modello del dispositivo e la versione di Android. **Non allegare immagini di moduli reali né dati personali** se non è strettamente necessario.

## Privacy

L'elaborazione dei moduli avviene sul tuo dispositivo. Solo se attivi un servizio di lettura AI (Google Cloud Vision o Azure) le immagini dei moduli vengono inviate a quel servizio, con le tue credenziali. Nel programma non ci sono credenziali, moduli o dati personali.
