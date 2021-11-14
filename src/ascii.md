# ASCII codes

Lo standard più usato per rappresentare i caratteri base dell'alfabeto latino è l'ASCII (pronuncia IPA: æski, proncia traslitterata in italiano: askii). ASCII è l'acronimo di American Standard Code for Information Interchange. Come dice il nome, è uno standard americano quindi è pensato soprattutto per la lingua inglese, che non prevede lettere con l'accento.

> Per altri dettagli vedete pagg. 58-59 del vostro libro di testo.

# I caratteri non stampabili
I primi 32 caratteri sono detti _caratteri di controllo_, non sono stampabili e servono per vari scopi, come ad esempio per codificare i tasti freccia (su, giù, destra, sinistra), il tasto per cancellare (canc,del), e così via. 

A noi interessano soprattutto i seguenti:

| Bit | Decimale | Codice | Descrizione |
|:---:|:---:|:---:|---|
| 0000 | 0 | NUL | "nessun carattere", ha vari usi in informatica |
| .... | .. | .. | ..... |
| 0110 | 10 | LF | "Line Feed", per andare a capo |
| 0111 | 10 | CR | "Carriage Return", altro carattere per andare a capo |
| .... | .. | .. | ..... |

Perché ci sono due caratteri per andare a capo? Questo deriva direttamente dagli antenati diretti dei computer e delle tastiere, le macchine da scrivere meccaniche e successivamente le "[teletypewriter](https://en.wikipedia.org/wiki/Teleprinter)"(abbreviato "tty", sigla che ritroverete fra qualche anno...). In queste macchine infatti, per "andare a capo" bisognava effettuare due operazioni distinte tra loro: far scorrere la pagina in basso di una riga (line feed) e far tornare il carrello nella posizione più a sinistra della pagina.

<figure class="img-container">
    <video controls>
        <source src="assets/lettera22-lf-cr.mov" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <figcaption>Lettera 22, line feed & carriage return</figcaption>
</figure>

Quando si sono cominciati ad usare i monitor e non la carta, la distinzione non aveva più molto senso. Alcune aziende, come ad esempio Microsoft, hanno deciso di mantenere entrambi i caratteri, quindi per andare a capo in un file alla fine di ogni riga bisogna aggiungere CR+LF. Altri, come ad esempio Unix e derivati (inclusi Linux e macOS) hanno invece semplificato ed ottimizzato utilizzando un solo carattere, LF. È importante sapere queste cose perché quando modificate un file di testo di un programma, potrebbe avere un fine riga diverso da quello che vi aspettate e avere dei problemi. Nella maggior parte degli editor di testo oggi viene specificato nella barra in basso.

> Attenzione: questo discorso non vale per documenti creati con elaboratori di testo come Microsoft Word, perché in questo caso il file non è semplicemente l'insieme dei caratteri che genera il testo ma contiene molte più informazioni, come la formattazione, l'impaginazione, etc.

# I caratteri stampabili
L'ASCII base prevede 95 caratteri, che comprendono:
- 26 lettere minuscole (a..z)
- 26 lettere maiuscole (A..Z)
- 10 numeri (0..9)
- 32 caratteri di punteggiatura

I caratteri di punteggiatura nell'ambito informatico vengono usati per gli scopi più diversi e spesso sono chiamati con un nome diverso nello _slang_ (dialetto) dei programmatori.

| Carattere | Nome ufficiale italiano | Nome ufficiale inglese | Dialetto informatico| 
|:---:|---|---|---|
|   | spazio | space ||
| ! | punto esclamativo | exclamation mark | bang |
| " | doppio apice | double quote ||
| # | cancelletto | hash | sharp |
| $ | dollaro | dollar ||
| % | percento | percent ||
| & | e commerciale | ampersand | |
| ' | apice singolo | single quote ||
| ( ) | parentesi tonde | round bracket ||
| * | asterisco | asterisk | star|
| + | più | plus ||
| , | virgola | comma | |
| - | meno o trattino | minus or dash | |
| . | punto | full stop | dot |
| / | barra | slash ||
| : | due punti | colon ||
| ; | punto e virgola | semicolon ||
| < > | minore / maggiore o parentesi angolari (o angolate) | less-than / more than | angle bracket |
| = | uguale | equal ||
| / | barra | slash ||
| ? | punto interrogativo | question mark ||
| @ | chiocciola | at ||
| ^ | accento circonflesso | circumflex | caret |
| [ ] | parentesi quadre | square bracket ||
| \ | barra rovesciata | backslash ||
| _ | trattino basso | underscore ||
| ` | accento grave | grave accent | backtick (o backquote) |
| { } | parentesi graffe | curly brackets | |
| &#124; | barra verticale | vertical bar | pipe (tubo) |
| ~ | tilde | tilde | |












