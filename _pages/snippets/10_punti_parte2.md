{% capture onepage_tech %}
{% include_relative snippets/tech/onepage-tech.md %}
{% endcapture %}


Dal 2020, la Commissione Europea ha introdotto, all’interno della PAC, il Green Deal: un piano di supporto economico per preservare la biodiversità e mitigare il cambiamento climatico. La spesa della PAC è sempre stata in cima alla lista di priorità europee, per riqualificare aree rurali, incentivare il lavoro agricolo, promuovere il benessere di agricoltori mantenendo quello dell’ambiente e gestione dei cambiamenti climatici. Eppure, in questa situazione di urgenza, si può osservare una netta decrescita dei fondi destinati alla PAC al netto della spesa Europea. Un primo aspetto di difficile comprensione, al netto dell’emergenza climatica. 

<img src="{{site.baseurl}}/assets/images/grafici bea/finanziamento_per_categorie.svg" style="background: transparent;" alt="categ"> 

{% capture introduction_tech %}
{% include_relative snippets/tech/introduction-tech.md %}
{% endcapture %}

{% include tech-content.html content=introduction_tech %}

<br>
{% capture dataset_details %}
{% include_relative snippets/dataset-details.md %}
{% endcapture %}

{% include modal-component.html title="Dettagli del dataset" content=dataset_details id="dataset-details" size="lg" %}

{% capture modal_tech %}
{% include_relative snippets/tech/modal-tech.md %}
{% endcapture %}

{% include tech-content.html content=modal_tech %}