# Una guida su come attivare Windows 11 Pro gratuitamente
## Perchè Windows 11 Pro?
Perché otterrai alcune funzionalità in più come Bitlocker e potrai controllare il tuo pc anche da remoto con Connessione Remota di Windows
## Posso anche passare da qualsiasi altra edizione a Pro?
La risposta è si! Puoi passare da quasi tutte le edizioni a Pro completamente gratuitamente!
## Nota per gli utenti con l'edizione Pro non attivata
Le persone che hanno già Pro, ma non sono attivate, possono saltare i primi step e andare direttamente all'attivazione 

## Iniziamo
La prima cosa che devi fare è aprire CMD (Prompt dei comandi) come amministratore usando questo tasto della tastiera:

<kbd><img src="https://svgshare.com/i/dg_.svg" width="11"></kbd> + <kbd>R</kbd>

E ora digita ``cmd.exe`` nella casella

Ora premi questi tasti sulla tastiera:

<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Enter</kbd>


### Comandi
1. Ora, digita il seguente comando:
``slmgr.vbs /upk``
Ora visualizzerà un messaggio, fai clic su ``OK``

2. ed ora questo comando
``slmgr.vbs /cpky``
Ora visualizzerà un messaggio, fai clic su ``OK``

3. Ed anche questo comando
``slmgr.vbs /ckms``
Ancora una volta clicca su ``OK`` quando ricevi un messaggio

### Comando di verifica aggiornamento dell'edizione
Ora ontrolleremo che la tua edizione sia supportata per l'aggiornamento a Pro, esegui il seguente comando per verificarlo:
``DISM /online /Get-TargetEditions``
Se vedi ``Professional`` nell'elenco, puoi aggiornare la tua edizione di Windows a Pro gratuitamente!

### Running Windows Pro installer
Ora copia e incolla i seguenti comandi:

``sc config LicenseManager start= auto & net start LicenseManager``

``sc config wuauserv start= auto & net start wuauserv``

``changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T``

``exit``

Verrà eseguito un programma di installazione e vedrai un messaggio: ``% complete``

Ora attendi fino a quando non è al 100% e poi ricevi un errore (questo è normale, deve succedere.)

Quando ricevi l'errore, fai semplicemente clic su Esci e quindi riavvia il PC.

## Attivazione Windows Pro
Ora eseguiremo altri comandi per attivare Windows 11 Pro

Premi ancora una volta questi tasti della tastiera:
<kbd><img src="https://svgshare.com/i/dg_.svg" width="11"></kbd> + <kbd>R</kbd>


Premi <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Enter</kbd>

Riceverai un messagio, clicca su ``SI``

Orati si aprira il prompt dei comandi come amministratore.

Digita uno per uno i seguenti comandi per l'attivazione:

``slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX``

``slmgr /skms kms8.msguides.com``

``slmgr /ato``
 
# Last Words
Buon Proseguimento :smile:
