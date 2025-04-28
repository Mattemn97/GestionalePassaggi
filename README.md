# Gestionale Passaggi

## Descrizione

**Gestionale Passaggi** è un semplice foglio Excel pensato per gestire in modo organizzato i viaggi condivisi tra amici e colleghi, tenendo traccia:
- dei **viaggi effettuati**
- della **suddivisione delle spese**
- delle **statistiche individuali** (credito e debito).

Questo strumento è perfetto per chi, ad esempio, fa regolarmente car sharing per motivi di studio o lavoro, e vuole avere una traccia chiara e trasparente dei costi condivisi.

---

## Struttura del file

Il file Excel è suddiviso in tre fogli principali:

### 1. `Config`
Contiene le configurazioni iniziali:
- **Lista Trentini del sud**: elenco delle persone che partecipano ai passaggi.
- **Tratta**: percorsi abituali dei viaggi (esempio: "Trento - Bolzano").
- **Prezzo tratta**: costo associato a ciascun percorso.

---

### 2. `Viaggi`
Registro completo dei viaggi organizzati:
- **Data** e **Giorno**: quando è avvenuto il viaggio.
- **Pilota** e fino a **4 Passeggeri**: chi ha partecipato.
- **Tratta**: quale percorso è stato effettuato.
- **A&R**: indicazione se il viaggio è di sola andata o andata e ritorno.
- **Costo viaggio**: prezzo totale del viaggio.
- **Quota Pilota** e **Quota Passeggeri**: suddivisione del costo tra i partecipanti.
- **Credito Pilota**: ammontare di cui il pilota è creditore alla fine del viaggio.

---

### 3. `Statistiche`
Riepilogo delle attività dei partecipanti:
- **Viaggi fatti**: numero totale di viaggi effettuati.
- **Viaggi da pilota**: numero di viaggi dove si è stati pilota.
- **Credito Pilota**: totale guadagnato come pilota.
- **Debito Passeggero**: totale dovuto come passeggero.
- **Saldo Totale**: somma di credito e debito, indicando il bilancio complessivo.

---

## Come utilizzarlo

1. Inserisci nella scheda `Config` tutti i partecipanti e le tratte principali.
2. Registra ogni viaggio nella scheda `Viaggi`, indicando pilota, passeggeri e tratta.
3. Verifica nella scheda `Statistiche` l'andamento dei crediti/debiti.
4. A fine periodo, regola i conti sulla base del saldo totale di ciascuno.

---

## Requisiti

- **Software**: Microsoft Excel, LibreOffice Calc o Google Sheets (consigliato Excel per la miglior compatibilità con le convalide dati).
- **Conoscenze**: Uso base dei fogli di calcolo (scrittura, copia/incolla, menù a tendina).

---

## Licenza

Questo progetto può essere liberamente utilizzato e modificato per uso personale o di gruppo.

---

## Note

📌 *Il file è predisposto con menù a tendina per facilitare la selezione dei dati e ridurre errori di compilazione.*  
📌 *Attenzione: la modifica delle formule può compromettere il corretto funzionamento dei calcoli automatici.*
