# Company brain

Base di conoscenza dell'azienda. Qui sta tutto quello che serve per lavorare senza doverlo chiedere a qualcuno: chi siamo, cosa vendiamo, a quanto, come lavoriamo, con chi e perché abbiamo deciso certe cose.

Se un'informazione esiste solo nella testa di una persona o in una email, non esiste. Va scritta qui.

## Struttura

| Cartella | Cosa contiene |
|---|---|
| `azienda/` | Anagrafica, servizi, listino prezzi |
| `clienti/` | Una scheda per cliente |
| `processi/` | Come si fanno le cose, passo per passo |
| `decisioni/` | Registro datato delle decisioni prese e del perché |
| `modelli/` | Testi pronti: email e offerte |

## Regole di scrittura

1. **Italiano semplice.** Frasi brevi, niente gergo da marketing, niente sigle non spiegate.
2. **Prima il dato, poi il contesto.** Il numero o la conclusione in testa, la spiegazione sotto.
3. **Un argomento per file.** Se un file parla di due cose, dividilo.
4. **Nomi file:** minuscolo, parole separate da trattino, senza accenti. Es. `rossi-srl.md`, `onboarding-cliente.md`.
5. **Date nel formato `AAAA-MM-GG`** (es. `2026-11-21`), sia nel testo sia nei nomi file.
6. **Separa fatti e stime.** Una stima si marca con `(stima)`.
7. **Segnaposto:** ciò che manca si scrive `{{DA COMPLETARE: cosa serve}}`. Per trovarli tutti: `grep -rn "DA COMPLETARE" .`
8. **Niente dati sensibili in chiaro:** password, IBAN completi, documenti d'identità, dati sanitari non vanno qui.
9. **Aggiorna, non duplicare.** Se un'informazione cambia, correggi il file esistente. Se la modifica è una scelta, registrala anche in `decisioni/registro.md`.
10. **I file che iniziano con `_`** sono modelli: copiali, non modificarli.
