# ArciTessereOCR+ — download per i beta-tester

Questo repository contiene **solo i programmi pronti da installare**, non il codice sorgente.

ArciTessereOCR+ digitalizza le domande di iscrizione ARCI compilate a mano: legge l'immagine del modulo (scanner o fotocamera), riconosce i campi, li fa controllare e correggere e prepara i dati per l'esportazione in Excel o CSV.

## Scarica

Vai alla pagina **[Releases](../../releases/latest)** e scarica il file della versione più recente:

| File | Per cosa |
|---|---|
| `ArciTessereOCR-Setup-x.y.z.exe` | **Windows 10/11 a 64 bit** — installer (consigliato) |
| `ArciTessereOCR-x.y.z-windows-portatile.zip` | Windows, senza installazione: si scompatta e si lancia |

La versione per Android non è ancora disponibile.

Le istruzioni di installazione sono nelle note di ogni Release.

## Segnalare un problema

Scrivi a chi ti ha invitato al test indicando la versione (menu *Informazioni*), cosa stavi facendo e, se c'è, il file `errori.log` (si trova in `%LOCALAPPDATA%\ArciTessereOCR\it.arcitessereocr.app\Data\`). **Non allegare immagini di moduli reali né dati personali** se non è strettamente necessario.

## Privacy

L'elaborazione dei moduli avviene sul tuo computer. Solo se attivi un servizio di lettura AI (Google Cloud Vision o Azure) le immagini dei moduli vengono inviate a quel servizio, con le tue credenziali. Nel programma non ci sono credenziali, moduli o dati personali.
