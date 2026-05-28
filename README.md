# a11y-dev-public

Materiali didattici per il corso di **sviluppo accessibile**.  
Il repo raccoglie esempi pratici ed esercitazioni organizzati per argomento.

---

## Struttura

```
a11y-dev-public/
├── esempi/
│   ├── dialog/
│   │   ├── dialog-brutta.html   ← implementazione con problemi di accessibilità
│   │   └── dialog-buona.html    ← implementazione corretta
│   └── tabindex/
│       └── esempio-tabindex.html
└── esercitazioni/
    └── audit/
        └── esercitazione-audit.html
```

Gli esempi sono spesso in coppia **brutto / buono**: l'obiettivo è confrontare i due approcci, capire cosa non funziona e perché la versione corretta è migliore.

---

## Come usare i materiali

1. Clona il repo o scarica il file che ti interessa
2. Apri l'HTML direttamente nel browser (non serve un server locale)
3. Esplora la pagina con tastiera e screen reader per verificare il comportamento

### Screen reader consigliati

| Sistema operativo | Screen reader |
|---|---|
| macOS / iOS | VoiceOver (integrato) |
| Windows | NVDA (gratuito) oppure JAWS |
| Android | TalkBack (integrato) |

---

## Argomenti

- **Dialog** — gestione del focus, `role="dialog"`, `aria-modal`, `aria-labelledby`
- **Tabindex** — ordine di navigazione da tastiera, uso corretto di `tabindex`

*(La lista si aggiornerà con i nuovi moduli del corso)*

---

## Contributi

Il repo è pubblico a scopo didattico. Se trovi un errore o vuoi suggerire un miglioramento, apri pure una issue.

---

## Licenza

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — puoi usare e adattare i materiali citando la fonte.
