# UNICAM Notes :: Community

Italiano · [English](i18n/en/README.md)

UNICAM Notes raccoglie appunti, esercizi e materiali didattici condivisi da studenti e tutor dell’Università di Camerino. Questo repository contiene il [profilo dell’organizzazione](profile/README.md), le linee guida e i moduli dello spazio Discussions centralizzato.

## Dove contribuire

Le pull request devono essere aperte nel repository del corso interessato. Le Discussions devono essere aperte esclusivamente nello [spazio centralizzato di `unicam-notes/.github`](https://github.com/unicam-notes/.github/discussions).

## Discussions

Usa lo [spazio Discussions centralizzato](https://github.com/unicam-notes/.github/discussions) per tutti i corsi. Indica il corso o repository in ogni intervento; pull request e materiali didattici restano nei repository dei corsi. Non serve abilitare Discussions nei singoli repository dei corsi.

| Categoria | Utilizzo | Slug |
| --- | --- | --- |
| Q&A | Domande e discussioni generali su corsi, esercizi e materiali. | `q-a` |
| Contribution | Condivisione di nuovi appunti, esercitazioni e altri materiali. | `contribution` |
| Correction | Segnalazioni di errori e proposte di correzione. | `correction` |

Per condividere PDF, ZIP, Markdown, soluzioni o altri file pertinenti, apri una Discussion nella categoria **Contribution** dello spazio centralizzato, indicando il corso, oppure proponi una pull request nel repository del corso. Gli allegati dipendono dai formati e dai limiti supportati da GitHub: se un file non è accettato, usa un link accessibile o una pull request per aggiungerlo al repository.

Condividi soltanto materiali che hai il diritto di distribuire. Indica autore originale e fonte, conserva firme, crediti e avvisi di copyright. La [BSD 3-Clause](LICENSE) si applica ai contenuti coperti dalla licenza; non rende automaticamente BSD i materiali di terzi e non autorizza a distribuirli.

Tutti i repository di UNICAM Notes adottano la BSD 3-Clause. Ogni contributo deve rispettarne i termini; inviando materiali originali, accetti di renderli disponibili con questa licenza.

## Condividere file in un messaggio

Per condividere materiali, apri **New discussion → Contribution**, inserisci un titolo e scrivi il messaggio indicando il corso. Trascina i file supportati direttamente nel messaggio, incolla immagini oppure aggiungi link. Non è necessaria una pull request per proporre materiali tramite Discussion; gli allegati non vengono aggiunti automaticamente al repository del corso.

## Guide

- [Come contribuire](CONTRIBUTING.md) · [English](i18n/en/CONTRIBUTING.md)
- [Codice di condotta](CODE_OF_CONDUCT.md) · [English](i18n/en/CODE_OF_CONDUCT.md)
- Moduli bilingui italiano/inglese: [Q&A](.github/DISCUSSION_TEMPLATE/q-a.yml), [Contribution](.github/DISCUSSION_TEMPLATE/contribution.yml), [Correction](.github/DISCUSSION_TEMPLATE/correction.yml).

## Configurazione centralizzata

1. Pubblica i moduli nel branch predefinito del repository pubblico `unicam-notes/.github`.
2. Abilita **Settings → General → Features → Discussions** soltanto in `.github`. Per mostrarle anche a livello di organizzazione, abilita le Discussions dell’organizzazione e scegli `.github` come repository sorgente.
3. Configura tre categorie: **Q&A** (domanda/risposta, slug `q-a`), **Contribution** e **Correction** (discussioni aperte, slug `contribution` e `correction`). Prima di eliminare categorie aggiuntive, sposta le discussioni esistenti nelle categorie appropriate.
4. Verifica gli slug negli URL e apri una nuova discussione in ogni categoria per controllare i campi bilingui. Non occorre replicare categorie o moduli nei repository dei corsi.

I moduli attivi in `.github/DISCUSSION_TEMPLATE/` hanno istruzioni e campi in italiano e inglese. Il titolo usa il campo nativo di GitHub. Le pull request per aggiungere o correggere materiali vanno aperte nel repository del corso, non in `.github`.
