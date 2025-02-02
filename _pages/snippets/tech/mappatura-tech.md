**Text analysis sugli articoli di giornale delle testate locali di City News**

Abbiamo analizzato __oltre 400 articoli__ di giornale delle varie __testate locali di City News__ per fare una mappatura delle proteste all'interno del territorio italiano.

Abbiamo utilizzato __TagMe__ per fare una __entity ectraction__.

Abbiamo scaricato la lista dei comuni italiani dal sito ISTAT e abbiamo calcolato l'intersezione con la nostra lista di tokens. 

Abbiamo ottenuto una lista di 487 comuni. Siccome questo risultato indica soltanto che i comuni in lista sono citati all'interno degli articoli di giornale, per fare una mappatura delle proteste più robusta, abbiamo utilizzato la funzione _model.wv.most_similar()_. Tale funzione viene utilizzata per trovare le parole più simili a una determinata parola o vettore all'interno dello spazio vettoriale del modello di word embeddings. Dunque, restituisce le parole che sono più vicine nel significato alla parola o ai vettori dati, basandosi sulla vicinanza nello spazio dei vettori addestrati. Nel nostro caso abbiamo utilizzato come parole target __"manifestazione"__ e __"corteo"__ e abbiamo verificato la vicinanza nello spazio dei vettori addestrati con la lista dei comuni. Abbiamo messo un __threshold di similarità__ molto stringente, a __0.9__.

La lista dei comuni si è ridotta a 133 (che sono quelli che si vedono nella mappa), ma siamo più confidenti nel risultato.






