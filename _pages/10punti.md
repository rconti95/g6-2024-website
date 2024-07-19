---
layout: section_layout
title:  '"NON SI MOLLA… E CHE DIO CI BENEDICA!"'
subtitle: "Analisi delle proteste agricole nel contesto italiano"
show_sidetoc: true
header_type: hero #base, post, hero, image, splash
header_img: assets/images/10punti.jpg
header_title: '"NON SI MOLLA… E CHE DIO CI BENEDICA!"'
vega: true
---

# I 10 punti

Le proteste italiane sono confluite non solo in numerose manifestazioni pubbliche e presidi, ma anche nel documento che guida questa analisi. A gennaio del 2024, sono infatti stati redatti i 10 punti che riassumevano le richieste degli agricoltori. Alcuni simili per temi, sono stati indagati mettendo in luce le cause delle loro mancanze e le motivazioni per tali richieste.

## Punto 1: RIPROGRAMMAZIONE GREEN DEAL
“Revisione completa della Politica Agricola Europea, in quanto di estremismo ambientalista e a discapito della produzione agricola e dei consumatori (Cerealicoltura, allevamenti, regolamenti sui digestati….)”

<div id="area-tematica-1"></div>
{% capture dataset_details %}
{% include_relative snippets/dataset-details.md %}
{% endcapture %}

{% capture section_1_content %}
{% include_relative snippets/section-1.md %}
{% endcapture %}

{% include two-columns.html col-one=introduction_image col-two=section_1_content %}

{% capture section_1_content %}
{% include_relative snippets/section-1.md %}
{% endcapture %}

{% capture timeline_stragi %}
{% include_relative snippets/chart-timeline.md %}
{% endcapture %}

{% capture map_stragi %}
{% include_relative snippets/chart-map.md %}
{% endcapture %}

{% capture introduction_image %}
{% include_relative snippets/gallery-images.md %}
{% endcapture %}

{% capture stragi_all %}
{% include_relative snippets/mappa-stragi-intro.md %}
{% endcapture %}

{% capture mappa_stragi %}
{% include_relative snippets/mappa-stragi-intro.md %}
{% endcapture %}

{% capture video_content %}
{% include snippets/video.html id="UOQEACobAHk" provider="youtube" video_res="hq2" %}
{% endcapture %}

{% comment %}
{% include one-column-sm.html content=introduction_content %}
{% endcomment %}

{% include one-column-sm.html content=timeline_stragi %}
<hr>

{% capture tech_section1 %}
{% include_relative snippets/tech-section-1.md %}
{% endcapture %}

<div class="tech" style="display: none">
  {% include one-column-sm.html content=tech_section1 %}
</div>

{% include two-columns.html col-one=introduction_image col-two=section_1_content %}
<hr>
{% include img-selector.html %}
{% include chart-selector.html %}
<hr>
{% include one-column-sm.html content=mappa_stragi %}
<hr>
{% include one-column-sm.html content=video_content %}
{% include code-explanation.html %}

## Punto 2: Un altro punto importante
<div id="area-tematica-2"></div>
<!-- Contenuto per il secondo punto -->

## Punto 3: Un altro punto importante ancora
<div id="area-tematica-3"></div>
<!-- Contenuto per il terzo punto -->
