# covid-19
## Stima giornaliera del valore R(t) del COVID-19 nelle regioni italiane
Basandoci sul [lavoro svolto per gli USA](https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb) da [Kevin Systrom](https://it.wikipedia.org/wiki/Kevin_Systrom) per la stima del cosidetto valore $R_0$ (ovvero il [numero di riproduzione di base](https://www.iss.it/primo-piano/-/asset_publisher/o4oGR9qmvUz9/content/id/5268851)) del COVID-19, abbiamo provato ad applicare la stessa analisi alle regioni italiane, sulla base dei [dati](http://opendatadpc.maps.arcgis.com/apps/opsdashboard/index.html#/b0c68bce2cce478eaac82fe38d4138b1) forniti dal Dipartimento della Protezione Civile.

I risultati possono essere utili per valutare l'effettiva efficacia delle misure di contenimento sia nazionali che regionali e, in base ad essi, definire i successivi passi nella gestione della pandemia.

Quella presentata è una versione modificata di una soluzione sviluppata da [Bettencourt & Ribeiro 2008](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0002185) per stimare $R_t$ in tempo reale usando un approccio bayesiano. L'articolo di Kevin Systrom migliora la stima del valore statico di $R$, introducendo un modello di processo con rumore gaussiano per stimare un $R_t$ variabile nel tempo.
