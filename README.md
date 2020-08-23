# Progetto Clingo
Questo progetto è stato realizzato per l'esame di Intelligenza Artificiale e Laboratorio del corso di Laurea Magistrale all'Università di Torino.

## Setup
- Installare [Clingo](https://github.com/potassco/clingo/releases/).
- Installare [VSCode](https://code.visualstudio.com/download) e l'apposita estensione [Answer Set Programming syntax highlighter](https://marketplace.visualstudio.com/items?itemName=abelcour.asp-syntax-highlight).
- Clonare il progetto.

## Il problema
Consultare il punto 2 del [testo di progetto](https://github.com/lorenzofavaro/IA-Clingo/blob/master/Testo%20Progetto.pdf)

## Struttura del progetto
- `parser` contiene le classi Java e i file di testo necessari a parsificare l'output restituito da `calendar.cl`.
  - `Slot.java` definisce un oggetto rappresentante il singolo slot di insegnamento.
  - `Parser.java` prende in input `output.txt` e lo parsifica restituendo in output `parsed_output.txt`.
  - `output.txt`.
  - `parsed_output.txt`.

