# RISEN Builder

Un costruttore di prompt basato sul metodo **R.I.S.E.N.**: cinque form da compilare, un prompt che si scrive in tempo reale.

Serve per qualsiasi compito — correggere, scrivere, analizzare, intervistare, insegnare — e mostra l'anatomia di un prompt invece di descriverla.

## Le cinque sezioni

| Elemento | Cosa contiene |
|---|---|
| **R**ole | Il ruolo che il modello assume prima ancora di aprire bocca |
| **I**nstructions | Cosa deve fare esattamente — è qui che si trasferisce il proprio metodo |
| **S**teps | La sequenza di passaggi, ricalcata sul processo reale |
| **E**nd goal | Il risultato che resta a chi usa il prompt |
| **N**arrowing | I vincoli espliciti: cosa NON deve fare, tono, lunghezza, casi limite |

## Come si usa

1. Apri la pagina.
2. Compila le cinque sezioni. Il contatore in alto a destra segna quante sono complete.
3. **Copia il prompt**, oppure scarica il `.md` (il prompt pronto) e il `.json` (la scheda, riapribile con **Carica .json**).

## Pubblicare su GitHub Pages

1. Crea un repository e caricaci `index.html` e `README.md`.
2. `Settings` → `Pages` → Source: **Deploy from a branch** → branch `main`, cartella `/ (root)`.
3. Dopo un minuto la pagina è online su `https://<utente>.github.io/<repository>/`.

## Note tecniche

File singolo, nessuna dipendenza se non i font di Google. Tutto gira nel browser: nessun dato lascia la pagina, nessun backend, nessuna chiave API.

## Licenza

MIT.
