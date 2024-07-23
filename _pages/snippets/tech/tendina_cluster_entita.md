Report Tecnico del Clustering:
- abbiamo estratto le entità dai commenti utilizzando TagMe e imponendo come parametri rho >= 0.3 e link_probability >= 0.1. Inoltre per ridurre il rumore abbiamo considerato solo le entità con frequenza >= 5.
- abbiamo trasformato le entità in vettori di dimensione 100 utilizzando un modello Wikipedia2Vec in Italiano, e salvando in un dizionario la corrispondenza vettore-entità.
- abbiamo eseguito un algoritmo KMeans al variare di k numero di cluster, e dal confronto tra SSE e silhouette score abbiamo scelto k=8, ottenendo così 8 diversi cluster.
- abbiamo fatto il merge di due cluster per rimuovere un cluster molto piccolo (2 entità).
- dai vettori siamo tornati alle entità sfruttando il dizionario.
- ad ogni cluster abbiamo associato un'entità rappresentativa ottenuta calcolando l'entità più vicina al centroide (sfruttando i vettori corrispondenti alle entità e calcolando le distanze con la distanza Euclidea).

<!-- <div style="text-align: center;">
    <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_gian_dark_bg/chart_entities_clusters.json" style="width: 100%"></vegachart> 
</div> -->