---
layout: default-full
title:  '"NON SI MOLLA… E CHE DIO CI BENEDICA!"'
subtitle: "Analisi delle proteste agricole nel contesto italiano"
show_sidetoc: true
header_type: hero #base, post, hero,image, splash
header_img: assets/images/Immagine1.jpg
header_title: '"NON SI MOLLA… E CHE DIO CI BENEDICA!"'
vega: true
---

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<h2 style="color: #E0E0E0;">L’industria agroalimentare in Italia: una panoramica</h2>

<p style="color: #E0E0E0;">Cosa vuol dire, nel nostro paese, essere un agricoltore o agricoltrice? I dati CREA suggeriscono che significa far parte di un’industria il cui fatturato nel 2022 ha avuto <a href= "https://creafuturo.crea.gov.it/10568/"> un’incidenza superiore al 4% sull’economia dell’intero paese </a>. Un settore, dunque, con un’importanza altissima ma che, tuttavia, dal 2006 ha visto calare la sua forza produttiva, come dimostra il grafico sottostante.</p>

<hr>
        </div>
    </div>
</div>

<div style="text-align: center;">
    <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_ric_dark_bg/ISTAT_Italia_smooth.json" style="width: 100%"></vegachart>
</div>

<!-- <vegachart schema-url='E:/Gianluca/Master Big Data Pisa/Progetto_Finale/Sito/g6-2024-website/assets/charts/chart_ric_dark_bg/chart_istat.json' style="width: 100%"></vegachart> -->

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
{% capture grafico_istat %}
{% include_relative snippets/tech/grafico_istat.md %}
{% endcapture %}

{% include tech-content.html content=grafico_istat %}
            
        </div>
    </div>
</div>

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">Ma cosa si produce in Italia, e qual è la quantità di superficie che i vari prodotti occupano sul suolo italiano? Come si vede dai grafici sottostanti, i pascoli occupano buona parte della superficie agricola, seguiti poi dal frumento duro, l’olio d’oliva e il mais. Quanto alla produzione, l’Italia si concentra soprattutto su uva, frumento e mais.</p>
            <hr>
        </div>
    </div>
</div>

<div style="text-align: center;">
  <vegachart schema-url="{{site.baseurl}}/assets/charts/Produzione_Italia_smooth.json" style="width: 60%;"></vegachart>
</div>

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>
<p style="color: #E0E0E0;">La rilevanza economica dell’industria alimentare è un aspetto importante, ma non il solo. Nel corso degli anni essa ha assunto una crescente importanza culturale, spesso sfociata nella vera e propria rivendicazione identitaria. Un esempio emblematico di questa tendenza è la creazione del marchio “Made in Italy” - di cui i prodotti agroalimentari rappresentano una corposa parte - portata avanti dall’attuale governo di Giorgia Meloni, che ne ha istituito una <a href="https://www.mimit.gov.it/it/made-in-italy/giornata">giornata celebrativa il 15 aprile </a> in occasione della nascita di Leonardo Da Vinci (15 aprile 1452).</p>  

<p style="color: #E0E0E0;">“In generale quando si parla degli agricoltori si ha sempre in mente un'idea da anni 50, in cui l'agricoltore è un maschio col trattore e ha, diciamo, la famiglia che lavora più o meno con lui o con lei, anzi con lui!”, commenta Brunori. Nel settore agroalimentare “Made in Italy” è sinonimo di genuinità dei prodotti, garantita da lavoratori e lavoratrici che si prendono cura di una terra feconda e materna e che operano in una specie di “piccolo mondo antico” - un'immagine rassicurante ma molto lontana dalla realtà dei fatti. Calvani stesso si mostra piuttosto scettico rispetto alla questione del Made in Italy, che non stenta a definire uno specchietto per le allodole. </p>  

<p style="color: #E0E0E0;">La narrazione attorno al Made in Italy ha forse potuto imporsi grazie alla conformazione delle aziende agricole italiane, per lo più di medie-piccole dimensioni e a conduzione famigliare. Le multinazionali italiane e estere rappresentano rispettivamente solo il 12,5% e 4,5% del panorama italiano, secondo i dati Crea. Questo è un aspetto caratterizzante del settore agricolo italiano soprattutto rispetto agli altri Stati europei (sebbene, come si vede dal grafico, il trend di aziende a conduzione famigliare sia generalmente in crescita).</p> 

            <hr>
        </div>
    </div>
</div>

<div style="text-align: center;">
  <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_bea_dark_bg/ita_eu_confronto_unita_famil_agric.json" style="width: 60%;"></vegachart>
</div>

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">L’Italia è vicina a paesi come la Romania e la Polonia, dove il numero più corpose di aziende è posseduto interamente da famiglie, mentre un numero minore ancorché consistente è a conduzione ibrida (famigliare ed extra-famigliare). Una minimissima parte delle aziende agricole appartiene interamente a gruppi non famigliari.</p>

            <hr>
        </div>
    </div>
</div>

<div style="text-align: center;">
  <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_bea_dark_bg/tipologie_realta_agricole_eu.json" style="width: 60%"></vegachart>
</div>
                
<!-- 
            <br>
            <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_bea_dark_bg/tipologie_realta_agricole_eu.json" style="width: 100%"></vegachart>
        </div>
    </div>
</div>
-->

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">Insomma, quella italiana è una realtà fatta di grandi industrie, ma soprattutto di lavoratrici e lavoratori che ereditano terra e lavorano i campi seguendo una spesso longeva tradizione famigliare.</p> 

<p style="color: #E0E0E0;">Eventi recenti, tuttavia, ci permettono di complicare questo quadro e considerare la presenza di “realtà sommerse”, che pure caratterizzano il sistema agricolo italiano. Caporalato, lavoro in nero e sottopagato sono degli elementi che non possono essere letti attraverso i dati - poiché non registrati - ma che pure riemergono al verificarsi di fatti di cronaca. Il più recente è quello avvenuto a giugno 2024, con l’efferato omicidio dell’agricoltore <a href="https://www.ilpost.it/2024/06/20/inchiesta-morte-satnam-singh-agro-pontino-latina/"> Satnam Singh </a>, che lavorava a nero in un’azienda agricola dell’agropontino. Nel 2020, la serie di proteste il cui portavoce è stato <a href="https://www.ilpost.it/2020/06/17/protesta-aboubakar-soumahoro/Aboubakar"> Aboubakar Soumahoro </a> ha portato l’attenzione sulla situazione dei braccianti migranti, già tristemente nota e documentata in molte occasioni, una delle quali il libro-inchiesta di Fabrizio Gatti Bilal. Viaggiare, lavorare, morire da clandestini del 2008. </p> 

<p style="color: #E0E0E0;">Si tratta di un settore complicato, dunque, che porta in seno delle contraddizioni che è spesso difficile da ricostruire e leggere in prospettiva. Per questo seguiremo i 10 punti del manifesto degli agricoltori per capire più da vicino quale sia lo stato di salute del sistema agricolo italiano.</p>

            <hr>
        </div>
    </div>
</div>

<img src="{{site.baseurl}}/assets/images/infografiche/Infog agric.png" width="1400" height="1400" alt="agricoltura_italiana">

{% include code-explanation.html %} 