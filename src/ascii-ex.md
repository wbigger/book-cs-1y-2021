# Esercizio

## Windows
Aprite l'applicazione Blocco note (Notepad, in inglese). Se avete una versione abbastanza recente, nella barra in basso vi dovrebbe comparire quale ritorno a capo l'editor sta usando, che per un nuovo file dovrebbe essere CRLF.

> Notepad ha introdotto il [supporto](https://devblogs.microsoft.com/commandline/extended-eol-in-notepad/) per altri terminatori di linea nel 2018.

Lasciate il file perfettamente vuoto e salvatelo con il nome che preferite, lasciate l'estensione `.txt`. Per salvare il file in modo veloce potete usare la scorciatoia "ctrl-s". Aprite Esplora Risorse e navigate nella cartella in cui si trova il file. Cliccate con il tasto destro sul file appena creato e selezionate "Proprietà". Cercate la dimensione del file, dovrebbe essere esattamente 0 byte.

Ora per esercizio provate a fare le seguenti cose:
1. scrivete "ciao" su Blocco note e salvate (ricordatevi che potete usare ctrl-s). Quanto è diventata adesso la dimensione del file in byte?
2. dopo ciao, alla fine della riga, premete invio per andare a capo. La dimensione del file è cambiata? di quanti byte?
3. scrivete di nuovo ciao nella seconda riga e ricontrollate la dimensione del file per vedere cosa sta succedendo

Cosa avete notato? Vi tornano i conti con quanto detto finora?

Ora provate ad inserire un carattere che non fa parte dello standard ASCII (né base né esteso), come ad esempio un emoji o un carattere in un alfabeto diverso da quello latino (come ad esempio il greco, il rumeno, il turco, il cinese, il giapponese, etc.). Salvate il file e controllate la dimensione. Cosa è successo? di quanti byte è cambiato il file? Secondo voi perché?

## Apple
Eseguire lo stesso esercizio precedente, usando "Finder" invece di "Esplora risorse" e "Get Info" invece di "Proprietà". Per salvare il file, bisogna usare la scorciatoia ⌘S.



