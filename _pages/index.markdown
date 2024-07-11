---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

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
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <hr>
            <p>Dal novembre del 2023, in Italia e in altri stati europei, abbiamo assistito a manifestazioni dall’impatto mediatico molto forte degli agricoltori. Media e giornali hanno così iniziato una narrazione di quanto stava accadendo nel nostro paese, dividendosi tra cronaca e politicizzazione dei fatti.
Ma dove sono le cause, le motivazioni, le origini e le spinte di tutto ciò?
Abbiamo deciso di adottare strumenti analitici e letteratura critica per capire cosa stesse succedendo, al di là delle (anche e soprattutto nostre) prime apparenze.</p>
            <hr>
        </div>
    </div>
</div>

<vegachart schema-url="{{site.baseurl}}/assets/charts/chart_trattori.json" style="width: 100%"></vegachart>

<div class="row pb-5">
    <div class="col-md-12 col-sm-12">
        <div class="card-container">
            {% for image in site.data.home-cards %}
            <div class="card" style="width: 18rem;">
                    <a href="{{site.baseurl}}{{ image.path}}">
                    <div class="card-img"  ><img src="{{site.baseurl}}{{ image.url}}" class="card-img-top" alt="{{ image.name }}">
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">{{ image.name }}</h5>
                        <p class="card-text">{{ image.description }}</p>
                    </div>
                    </a>    
            </div>
            {% endfor %}
        </div>
    </div>
</div>

<!--
<div class="container py-3 mb-0 bg-color-full bg-color">
    <div class="row">
        <div class="col-md-3 col-md-offset-3">
        </div>
        <div class="col-md-6">
            <p>Prima di affrontare la realizzazione del sito è necessario installare Jekyll</p>
            <a href="{{site.baseurl}}/installation" class="btn btn-info" role="button">Installazione di Jeykll</a>
        </div>
    </div>
</div>
-->