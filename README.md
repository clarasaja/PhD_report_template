# Modello LaTeX per la relazione delle attività del primo anno di PhD

🇬🇧 **English instructions are provided in the section below.** 🇬🇧

## Descrizione

Questo repository contiene un **modello LaTeX** per la relazione sulle
attività svolte durante il primo anno del corso di dottorato in Fisica.
Il documento include un frontespizio con i loghi dell'Università degli Studi
di Catania e del DFA, oltre alle sezioni dedicate alle attività di ricerca,
alla didattica, ai seminari, ai periodi all'estero, alle conferenze, alle
altre attività e alle pubblicazioni.

Il file principale da modificare è [`main.tex`](main.tex).

## Prima di iniziare

Il modello è un supporto tipografico e organizzativo e non sostituisce le
indicazioni ufficiali del corso di dottorato. Prima della consegna, verificare
sempre la versione aggiornata delle istruzioni e assicurarsi che il documento
rispetti i requisiti richiesti, comprese sezioni, contenuti, date, firme e
modalità di presentazione.

## Come usare il modello

1. Aprire [`main.tex`](main.tex) con un editor LaTeX.
2. Sostituire i dati di esempio nel frontespizio, tra cui:
   - nome e cognome del/della dottorando/a;
   - ciclo del dottorato;
   - anno accademico;
   - data e luogo;
   - nome del/della tutor e del/della referente del curriculum.
3. Sostituire il testo segnaposto nelle sezioni della relazione.
4. Aggiornare le tabelle con le attività effettivamente svolte.
5. Aggiungere o rimuovere le righe e gli elementi elenco necessari.
6. Aggiornare le informazioni relative alle pubblicazioni e verificare che
   siano state inserite in IRIS, se richiesto dal corso di dottorato.
7. Controllare il documento PDF risultante prima della consegna.

I contenuti di esempio, come `MARIO ROSSI`, le date, i corsi, i seminari e le
attività all'estero, devono essere sostituiti con i dati reali. Rimuovere
inoltre eventuali segnaposto residui, come `[...]`, `XX YY` e `DOI….. HANDLE….`.

## Compilazione

Compilare [`main.tex`](main.tex) usando l'ambiente LaTeX e il motore di
compilazione preferiti. Per ottenere il risultato finale, seguire le
indicazioni del proprio editor o della propria distribuzione LaTeX e verificare
che il PDF generato sia impaginato correttamente.

Il risultato principale della compilazione è [`main.pdf`](main.pdf).

## Immagini

Le immagini utilizzate dal documento devono rimanere nella cartella
[`images/`](images/). I loghi attualmente presenti sono:

- [`images/Monogramma_DFA_black_.png`](images/Monogramma_DFA_black_.png);
- [`images/Logo_UniCT.png`](images/Logo_UniCT.png).

Non spostare né rinominare questi file senza aggiornare i relativi percorsi in
[`main.tex`](main.tex). Per aggiungere un'immagine, usare un percorso relativo,
ad esempio:

```latex
\includegraphics[width=0.8\textwidth]{images/nome-immagine.png}
```

## Struttura della relazione

Le sezioni già predisposte nel modello sono:

- sviluppi della ricerca;
- attività didattiche;
- partecipazione ai seminari;
- periodo all'estero;
- periodo presso aziende o industrie, se previsto;
- partecipazione a conferenze, workshop e scuole;
- altre attività, come tutorato e divulgazione;
- pubblicazioni;
- firme del/della dottorando/a, del/della tutor e del/della referente del
  curriculum.

## File principali

- [`main.tex`](main.tex): contenuto, struttura e impaginazione della relazione;
- [`images/`](images/): loghi e immagini utilizzati dal documento;
- [`main.pdf`](main.pdf): versione PDF del modello;
- [`LICENSE`](LICENSE): licenza del repository.

## Contributi

Ogni correzione e miglioramento è benvenuto. È possibile fare un fork del
repository, apportare le modifiche e aprire una pull request.

---

## English instructions

This repository contains a **LaTeX template** for reporting the activities
completed during the first year of a PhD programme in Physics. It includes a
title page with the logos of the University of Catania and the DFA, as well as
sections for research, teaching, seminars, periods abroad, conferences,
workshops, schools, other activities, and publications.

The main file to edit is [`main.tex`](main.tex).

### Important: follow the official requirements

This template is intended only as a typographical and organisational aid. It
does not replace the official instructions of the PhD programme. Before
submission, always check the latest requirements and make sure that the report
complies with all requested sections, contents, dates, signatures, and
submission procedures.

### Using the template

1. Open [`main.tex`](main.tex) in a LaTeX editor.
2. Replace the example information on the title page, including:
   - the PhD student's name;
   - the PhD cycle;
   - the academic year;
   - the place and date;
   - the tutor's and curriculum representative's names.
3. Replace the placeholder text in the report sections.
4. Update the tables with the activities actually completed.
5. Add or remove rows and list items as needed.
6. Update the publication details and check that they have been entered in
   IRIS, if required by the PhD programme.
7. Check the generated PDF before submitting it.

Example content such as `MARIO ROSSI`, dates, courses, seminars, and travel
activities must be replaced with the relevant information. Also remove any
remaining placeholders, including `[...]`, `XX YY`, and `DOI….. HANDLE….`.

### Compilation

Compile [`main.tex`](main.tex) using the LaTeX environment and compilation
engine of your choice. Follow the instructions provided by your editor or
LaTeX distribution, and check that the generated PDF has the expected layout.

The main compilation output is [`main.pdf`](main.pdf).

### Images

Keep all images used by the document in the [`images/`](images/) folder. The
current logos are:

- [`images/Monogramma_DFA_black_.png`](images/Monogramma_DFA_black_.png);
- [`images/Logo_UniCT.png`](images/Logo_UniCT.png).

Do not move or rename these files without updating their paths in
[`main.tex`](main.tex). To add an image, use a relative path, for example:

```latex
\includegraphics[width=0.8\textwidth]{images/image-name.png}
```

### Report structure

The template already provides sections for:

- research developments;
- teaching activities;
- seminar participation;
- periods abroad;
- periods in companies or industries, if applicable;
- conferences, workshops, and schools;
- other activities, such as tutoring and outreach;
- publications;
- signatures of the PhD student, tutor, and curriculum representative.

### Main files

- [`main.tex`](main.tex): report content, structure, and layout;
- [`images/`](images/): logos and images used by the document;
- [`main.pdf`](main.pdf): PDF version of the template;
- [`LICENSE`](LICENSE): repository license.

### Contributions

Corrections and improvements are welcome. Feel free to fork the repository,
make your changes, and open a pull request.
