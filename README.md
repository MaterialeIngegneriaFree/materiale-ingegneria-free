# materiale-ingegneria-free

Questo progetto nasce da una chiacchierata tra due studenti di Ingegneria.
L'obiettivo è di fornire una raccolta di materiale didattico (che sia preferibilmente sotto licenza libera, o quantomeno di accesso pubblico e gratuito) per studenti dei Corsi di Laurea in Ingegneria.
Attualmente è poco più di una "proof of concept", si spera nell'aiuto di numerosi studenti per poterlo ampliare.

Il sito, realizzato con Jekyll e GitHub Pages, è accessibile all'indirizzo [materialeingegneriafree.github.io/materiale-ingegneria-free/](https://materialeingegneriafree.github.io/materiale-ingegneria-free/)

## Linting

Per ridurre la possibilità di errori nella generazione del sito, i file Markdown vengono controllati con [markdownlint](https://github.com/markdownlint/markdownlint):

```
mdl -r ~MD002,~MD013,~MD026
```

## Licenza

Il codice del sito in questa repository è rilasciato sotto licenza *Creative Commons Zero v1.0 Universal*.
Notare che la licenza si applica solamente al sorgente del sito, che è un insieme di file Markdown con dei link.
__I materiali a cui il sito fa riferimento sono rilasciati sotto le rispettive licenze, riportate assieme ai link nelle pagine del sito.__
__Idem i file nella cartella Resources sono soggetti alle relative licenze, riportate nei file stessi.__
