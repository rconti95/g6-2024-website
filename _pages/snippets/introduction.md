# Dati ISTAT Agricoltura

Abbiamo scaricato dal sito <b>ISTAT</b> (https://www.istat.it/en/news/statbase-access-to-most-frequently-requested-data/) il file csv relativo all'Agricoltura.

Abbiamo creato un grafico interattivo con un menù a tendina, per la selezione del _"Tipo dato"_. Il grafico mostra i valori del "Tipo dato" selezionato per l'Italia per ogni anno dal 2006 al 2023.

{% capture dataset_details %}
{% include_relative snippets/dataset-details.md %}
{% endcapture %}

{% include modal-component-intro.html title="Dettagli del dataset" content=dataset_details %}