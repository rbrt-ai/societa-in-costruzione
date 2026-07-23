# Società in Costruzione

Società in Costruzione è una piattaforma civica aperta per studiare problemi pubblici,
confrontare alternative e migliorare proposte verificabili nel tempo.

Non è un partito e non presenta una società perfetta già definita. Il progetto usa evidenze,
principi dichiarati, argomentazione trasparente e revisione pubblica per rendere visibili
benefici, costi, rischi, conflitti tra valori e questioni ancora aperte.

## Contenuti

- manifesto e tredici principi;
- metodo editoriale in sei passaggi;
- roadmap pubblica;
- modello completo per nuove proposte;
- proposta modello sulla salute mentale territoriale;
- proposta modello sull’apprendimento permanente;
- regole di partecipazione, trasparenza e moderazione;
- kit di identità visiva e comunicazione.

## Sito e discussioni

- Sito: <https://rbrt-ai.github.io/societa-in-costruzione/>
- Discussioni: <https://github.com/rbrt-ai/societa-in-costruzione/discussions>

GitHub Discussions è il primo spazio deliberativo sperimentale. Critiche e contributi devono
riguardare idee, fonti, effetti e argomenti, non le persone.

## Esecuzione locale

Richiede Python 3.11 o successivo.

```bash
python -m pip install -r requirements-docs.txt
mkdocs serve
```

Verifica della build:

```bash
mkdocs build --strict
```

## Struttura

```text
docs/
  manifesto.md
  principi.md
  metodo.md
  roadmap.md
  proposte/
    salute-mentale-territoriale.md
    apprendimento-permanente.md
    template.md
  comunicazione/
    identita-social.md
.github/
  workflows/docs.yml
mkdocs.yml
requirements-docs.txt
```

## Privacy

Il repository e il sito non pubblicano nomi, indirizzi email, recapiti, percorsi locali o altri
dati personali del promotore. Non inserire dati personali propri o altrui in issue, pull request
o Discussions.

Il sito non usa cookie, analytics, pubblicità, moduli di contatto o risorse tipografiche esterne.
GitHub può trattare dati tecnici di accesso secondo la propria informativa.

## Contribuire

Leggi [CONTRIBUTING.md](CONTRIBUTING.md) e il
[Codice di condotta](CODE_OF_CONDUCT.md). Le proposte devono distinguere fatti, valori,
interpretazioni, stime e incertezze; indicare fonti reali; descrivere alternative e condizioni
di modifica o abbandono.

## Licenza

Il codice di configurazione è distribuito con licenza MIT. Prima di accettare contributi
editoriali esterni verrà definita esplicitamente anche la licenza dei contenuti.
