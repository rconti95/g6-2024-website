---
layout: section_layout
title:  '"NON SI MOLLA… E CHE DIO CI BENEDICA!"'
subtitle: "Analisi delle proteste agricole nel contesto italiano"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/Immagine1.jpg
header_title: '"NON SI MOLLA… E CHE DIO CI BENEDICA!"'
vega: true
---

# L’industria agroalimentare in Italia: una panoramica

Cosa vuol dire, nel nostro paese, essere un agricoltore o agricoltrice? I dati CREA suggeriscono che significa far parte di un’industria il cui fatturato nel 2022 ha avuto un’incidenza superiore al 4% sull’economia dell’intero paese. Un settore, dunque, con un’importanza altissima ma che, tuttavia, dal 2006 ha visto calare la sua forza produttiva, come dimostra il grafico sottostante. 

<vegachart schema-url="{{site.baseurl}}/assets/charts/chart_istat.json" style="width: 100%"></vegachart>

<div class="container py-3">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
{% capture grafico_istat %}
{% include_relative snippets/tech/grafico_istat.md %}
{% endcapture %}

{% include tech-content.html content=grafico_istat %}
            <br>
            <hr>
        </div>
    </div>
</div>

Ma cosa si produce in Italia, e qual è la quantità di superficie che i vari prodotti occupano sul suolo italiano? Come si vede dai grafici sottostanti, i pascoli occupano buona parte della superficie agricola, seguiti poi dal frumento duro, l’olio d’oliva e il mais. Quanto alla produzione, l’Italia si concentra soprattutto su uva, frumento e mais. 

<img src="{{site.baseurl}}/assets/images/superficie_totale.jpg" width="700" height="500" alt="superficie_totale">

La rilevanza economica dell’industria alimentare è un aspetto importante, ma non il solo. Nel corso degli anni essa ha assunto una crescente importanza culturale, spesso sfociata nella vera e propria rivendicazione identitaria. Un esempio emblematico di questa tendenza è la creazione del marchio “Made in Italy” - di cui i prodotti agroalimentari rappresentano una corposa parte - portata avanti dall’attuale governo di Giorgia Meloni, che ne ha istituito una <a href="https://www.mimit.gov.it/it/made-in-italy/giornata">giornata celebrativa il 15 aprile </a> in occasione della nascita di Leonardo Da Vinci (15 aprile 1452).  

“In generale quando si parla degli agricoltori si ha sempre in mente un'idea da anni 50, in cui l'agricoltore è un maschio col trattore e ha, diciamo, la famiglia che lavora più o meno con lui o con lei, anzi con lui!”, commenta Brunori. Nel settore agroalimentare “Made in Italy” è sinonimo di genuinità dei prodotti, garantita da lavoratori e lavoratrici che si prendono cura di una terra feconda e materna e che operano in una specie di “piccolo mondo antico” - un'immagine rassicurante ma molto lontana dalla realtà dei fatti. Calvani stesso si mostra piuttosto scettico rispetto alla questione del Made in Italy, che non stenta a definire uno specchietto per le allodole. <span class="red-underline">[inserire citazione precisa]</span> .  

La narrazione attorno al Made in Italy ha forse potuto imporsi grazie alla conformazione delle aziende agricole italiane, per lo più di medie-piccole dimensioni e a conduzione famigliare. Le multinazionali italiane e estere rappresentano rispettivamente solo il 12,5% e 4,5% del panorama italiano, secondo i dati Crea. Questo è un aspetto caratterizzante del settore agricolo italiano soprattutto rispetto agli altri Stati europei (sebbene, come si vede dal grafico, il trend di aziende a conduzione famigliare sia generalmente in crescita). 

L’Italia è vicina a paesi come la Romania e la Polonia, dove la maggior parte delle aziende sono interamente possedute da famiglie, una parte minore a conduzione ibrida, in cui le famiglie ancora posseggono una parte delle aziende. Una minima parte delle aziende agricole appartiene a gruppi non famigliari. 
Quella italiana è una realtà fatta di grandi industrie, ma soprattutto di lavoratrici e lavoratori che ereditano terra e lavorano i campi seguendo una spesso longeva tradizione famigliare. 

Eventi recenti, tuttavia, ci permettono di complicare questo quadro e considerare la presenza di “realtà sommerse”, che pure caratterizzano il sistema agricolo italiano. Caporalato, lavoro in nero e sottopagato sono degli elementi che non possono essere letti attraverso i dati - poiché non registrati - ma che riemergono al verificarsi di fatti di cronaca, il più recente nel giugno del 2024, l’efferato omicidio dell’agricoltore di origini Satnam Singh, che lavorava a nero in un’azienda agricola dell’agropontino. Nel 2020, la serie di proteste il cui portavoce è stato Aboubakar Soumahoro ha portato l’attenzione sulla situazione dei braccianti migranti, già tristemente nota e documentata in molte occasioni, una delle quali il libro-inchiesta di Fabrizio Gatti Bilal. Viaggiare, lavorare, morire da clandestini del 2008. 

Si tratta di un settore complicato, dunque, che porta in seno delle contraddizioni che è spesso difficile da ricostruire e leggere in prospettiva. Per questo seguiremo i 10 punti del manifesto degli agricoltori per capire più da vicino quale sia lo stato di salute del sistema agricolo italiano. 


<img src="{{site.baseurl}}/assets/images/agricoltura_italiana.jpg" width="700" height="500" alt="agricoltura_italiana">

<img src="{{site.baseurl}}/assets/images/LUC_GIF_TUSCANY.gif" width="700" height="500" alt="Test immagine">

[//]: # (Introduction section)
{% capture introduction_content %}
    {% include_relative snippets/introduction.md %}
{% endcapture %}

{% include one-column.html dimension="fluid" content=introduction_content %}


[//]: # (Chart Timeline Stragi)
<br>
{% capture timeline_stragi %}
{% include_relative snippets/chart-timeline.md %}
{% endcapture %}

{% include one-column.html dimension="small" content=timeline_stragi %}

[//]: # (Big numbers)
<div class="bg-color bg-color-full py-3 my-5">
    {% include one-column.html dimension="small" title="I numeri delle stragi per matrice" %}
    {% include big-numbers-cards.html data="morti-matrice" number="Morti" description="Matrice" %}
</div>

[//]: # (Chart Two columns)
{% capture introduction_images %}
{% include_relative snippets/gallery-images.md %}
{% endcapture %}

{% capture section_1_content %}
    {% include_relative snippets/section-1.md %}
{% endcapture %}

{% include two-columns.html col-one=introduction_images col-two=section_1_content %}

[//]: # (Cards Gallery)
<div class="bg-color bg-color-full py-3 my-5" id="galleria">
    {% include one-column.html dimension="small" title="Gallerie di immagini e chart" %}
</div>
{% include img-gallery-cards.html width='23%' datasource=site.data.img-selector url='url' name='name' description='description' %}


[//]: # (Image selector)
<div class="bg-color-full bg-color py-3 my-5" style="min-height:45vh">
{% include one-column.html dimension="small" title="Seleziona un'immagine" %}
{% include img-selector.html dataset="img-selector" button_name="name" url="url" %}
</div>

[//]: # (Chart selector)
{% include one-column.html dimension="small" title="Numero di morti per tipo di matrice" %}
{% include chart-selector.html dimension="small" dataset="chart-selector" %}


[//]: # (Gallery explanation)
{% capture galleries_explanation %}
{% include_relative snippets/galleries-explanation.md %}
{% endcapture %}
{% include one-column.html dimension="small" content=galleries_explanation %}
<br>

[//]: # (Map with modal)
<hr>
{% capture mappa_stragi_intro %}
{% include_relative snippets/mappa-stragi-intro.md %}
{% endcapture %}
{% include one-column.html dimension="small" content=mappa_stragi_intro %}
<hr>

[//]: # (Video in one column)
{% capture video_content %}
{% include snippets/video.html id="UOQEACobAHk" provider="youtube" video_res="hq2" %}
{% endcapture %}

{% include one-column.html dimension="small" title="Presentazione di Paolo Pezzino" content=video_content %}

{% include code-explanation.html %} 