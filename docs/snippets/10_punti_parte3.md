{% capture onepage_tech %}
{% include_relative snippets/tech/onepage-tech.md %}
{% endcapture %}

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">I lavoratori e le lavoratrici dell’agricoltura non si limitano a chiedere il miglioramento delle loro condizioni materiali. Le loro istanze spaziano anche su temi di natura sociale. Il punto numero 10 del loro manifesto non potrebbe essere più chiaro:</p>

<p style="color: #E0E0E0;">“RIQUALIFICAZIONE DELLA FIGURA DELL’AGRICOLTORE. A partire dalle
scuole, riqualificare la figura dell’agricoltore ed allevatore, valorizzandola e non additandola come responsabile dell’inquinamento ambientale. L’agricoltore è una figura fondamentale per la società in quanto tutore dell’ambiente e produttore di cibo/vita!”</p>

<p style="color: #E0E0E0;">Il prof. Brunori segnala “un’insofferenza e una disaffezione generalizzata per le forme di rappresentanza, per i policy-maker, eccetera”. Calvani, però, non ci gira intorno: “I nostri primi nemici sono i sindacati agricoli, la Coldiretti!  
Ma come catturare la voce di agricoltori e agricoltrici e, soprattutto, coglierne il parere? Un modo efficace è quello di fare ricorso alle “piazze virtuali”, come Facebook, raccogliendo post e commenti.</p>

            <hr>
        </div>
    </div>
</div>

[//]: # (Big numbers)
<div class="bg-color bg-color-full py-3 my-5">
    {% include one-column.html dimension="small" title="Dati sui commenti" %}
    {% include big-numbers-cards.html data="comments" number="Morti" description="Matrice" %}
</div>

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">Anche un’analisi dei commenti sulla pagina Facebook "CRA Agricoltori traditi" rivela che il termine “sindacato” suscita quasi esclusivamente rabbia.</p>

            <hr>
        </div>
    </div>
</div>

 [//]: # (Big numbers)
<div class="bg-color bg-color-full py-3 my-5">
    {% include one-column.html dimension="small" title="Sentiment analysis sui commenti di argomento i sindacati agricoli" %}
    {% include big-numbers-cards.html data="sindacati_emotions" number="Morti" description="Matrice" %}
</div>

{% capture sentiment %}
{% include_relative snippets/tech/sentiment.md %}
{% endcapture %}

{% include tech-content.html content=sentiment %}

<br>

<!--<p style="color: #E0E0E0;"><span class="red-underline">[GRAFICO]?</span></p> -->

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">Agricoltori e agricoltrici si sentono quindi abbandonati/e. “Prima noi, negli anni nostri, vi parlo di 20, 30 anni fa, noi avevamo dei punti di riferimento o destra o sinistra o al centro, condivisibili o no, però erano punti di riferimento! Oggi non ci sono più.” Addirittura, secondo Calvani, lavoratori e lavoratrici si sentono strumentalizzati/e, come pedine in un gioco politico di cui non vogliono far parte: “Io sono stato chiamato da tutti questi politici da Nord a Sud non per di’ “Come si risolve il problema o guarda che c’hai torto, se risolve così”. No. Solo per compramme! Secondo voi un Paese così c’ha futuro?”.</p>

<p style="color: #E0E0E0;">Fraintesi/e, strumentalizzati/e, mal rappresentati/e: il punto del manifesto che chiede di riqualificare la loro figura e il loro lavoro appare come un tentativo di riappropriarsi della narrazione che riguarda agricoltori e agricoltrici, al di là degli stereotipi e del senso comune.</p>

<p style="color: #E0E0E0;">Effettivamente, l'interazione con Calvani e con il Prof. Brunori ha posto più volte noi stessi/e davanti a certi pregiudizi. A più riprese ci siamo sorpresi e sorprese a riprodurre alcuni preconcetti o a partire da assunti che abbiamo poi riconsiderato attraverso il dialogo con entrambe queste figure: un agricoltore e un esperto di politiche agricole, agli antipodi sono in apparenza. Se da una parte il confronto ci ha resi/e estremamente consapevoli/e rispetto al nostro posizionamento socio-culturale, dall’altra ci ha aiutato a comprendere che la rappresentazione di agricoltori e agricoltrici come persone bigotte e più o meno ignoranti è talmente radicata nel discorso della nostra società che difficilmente può essere evitata.</p>

<p style="color: #E0E0E0;">A questo punto, la giusta domanda da farsi, forse, è piuttosto quella che poneva la filosofa Gayatri Spivak nel suo famoso “Can the subaltern speak?” (“La persona subalterna può parlare?”). In questo saggio, molto importante nel campo degli studi postcoloniali, Spivak identifica la persona subalterna nel non-occidentale che, sostiene la filosofa, viene cancellata dalla classe egemonica (occidentale), poiché quest’ultima si dimostra accogliente solo verso ciò che può essere riportato entro le sue strutture senza metterle in discussione.</p>

<p style="color: #E0E0E0;">Utilizzando un approccio intersezionale che identifica la persona subalterna in chi occupa una posizione socio-culturale considerata inferiore, lo schema di Spivak si adatta bene a parecchie nostre osservazioni, offrendo una chiave di lettura interessante.</p>

<p style="color: #E0E0E0;">Il problema principale è che la persona subalterna e la classe egemonica non parlano la stessa lingua, cosa che porta a un cortocircuito comunicativo che limita le possibilità di comprensione e, dunque, di mutuo riconoscimento. Il linguaggio utilizzato da lavoratori e lavoratrici dell’agricoltura viene spesso liquidato come “populista”, tradizionalista e retrogrado, e utilizzato come ennesima conferma della loro ignoranza e incapacità di capire ciò di cui hanno davvero bisogno. In ultima analisi, il loro stesso linguaggio viene utilizzato per silenziarli/e.</p>

<p style="color: #E0E0E0;">Uno sguardo alle parole frequenti utilizzate nei post comincia a far comprendere quali sono i temi più dibattuti all'interno della pagina C.R.A. Agricoltori traditi: dall'agricoltura, alla religione e politica.</p>

            <hr>
        </div>
    </div>
</div>

<img src="{{site.baseurl}}/assets/images/circle_packing_entities_3.svg" width="800" height="800" alt="word cloud">

{% capture word_cloud %}
{% include_relative snippets/tech/word_cloud.md %}
{% endcapture %}

{% include tech-content.html content=word_cloud %}

<br>

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">Un'analisi più approfondita e semantica delle parole porta alla seguente ripartizione in temi:</p>

            <hr>
        </div>
    </div>
</div>

<div style="text-align: center;">
    <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_gian_dark_bg/tendina_cluster_entita3.json" style="width: 80%"></vegachart> 
</div>

{% capture tendina_cluster_entita %}
{% include_relative snippets/tech/tendina_cluster_entita.md %}
{% endcapture %}

{% include tech-content.html content=tendina_cluster_entita %}

<br>

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">Dal calcolo delle sequenze di parole più frequenti è interessante notare come tutte esprimano un sentimento di incoraggiamento ed unità. Come del resto era stato osservato dal professor Brunori, l'unità che ha saputo dimostrare il movimento degli agricoltori nel trasmettere la propria immagine è stato un elemento comunicativo molto efficacie.</p>

            <hr>
        </div>
    </div>
</div>

<div style="text-align: center;">
    <vegachart schema-url="{{site.baseurl}}/assets/charts/chart_gian_dark_bg/n_grammi_frequenti.json" style="width: 100%"></vegachart> 
</div>

{% capture ngrammi %}
{% include_relative snippets/tech/ngrammi.md %}
{% endcapture %}

{% include tech-content.html content=ngrammi %}

<div class="container py-3">
    <div class="row">
        <div class="col-md-2 col-md-offset-2">
        </div>
        <div class="col-md-8">
            <hr>

<p style="color: #E0E0E0;">È indubbio che i temi affrontati e le parole utilizzate siano molto vicini a un certo tipo di retorica in un certo modo populista e vicina alla destra. Tuttavia, questo è probabilmente il principale tipo di linguaggio a cui agricoltori e agricoltrici sono esposti/e, e quello rispetto al quale sono diventati/e più permeabili fino ad assimilarlo, finendo così per esprimersi e pensarsi attraverso di esso.</p>

<p style="color: #E0E0E0;">D’altro canto, sono proprio i partiti di destra (ed estrema destra) che si sono fatti portavoce delle istanze di agricoltori e agricoltrici. Questo è particolarmente vero a livello europeo per il PPE (Partito Popolare Europeo), che ha centrato buona parte della sua campagna elettorale sulle proteste agricole. Tuttavia, gli/le esponenti del PPE si sono limitati a commentare la nuova PAC 2023-2027 nei suoi risvolti ambientali, criticando punti come la riduzione dei pesticidi o la messa a riposo di una porzione delle terre coltivate, rafforzando così l’idea che questo fosse il principale motivo di malcontento tra i lavoratori e le lavoratrici del settore agricolo.</p>

<p style="color: #E0E0E0;">Un altro punto di vista interessante può essere fornito dal lavoro del filosofo e sociologo francese Didier Eribon, che ci aiuta non solo a capire meglio le dinamiche che hanno portato la classe operaia a distaccarsi dalla sinistra per avvicinarsi sempre di più alla destra, ma anche all’importanza che ha il linguaggio nella rappresentazione e comunicazione del sé, quando il sé appartiene a una categoria “ai margini”. Nel suo “Retour à Reims. Pour une théorie du sujet”, Eribon parte della sua soggettivà di uomo gay proveniente da un milieu operaio per esplorare i meccanismi, ad un tempo personali e sociali, che l’hanno accompagnato nel processo di “transfusion sociale” (il passaggio da una classe sociale all’altra). Eribon parla di come l’intellettualismo e la frammentazione della sinistra, accompagnate alla progressiva indulgenza verso ideologie neoliberiste, abbiano permesso alla destra populista del Front National di prendere sempre più favore nella classe operaia, che ne ha internalizzato la retorica, le istanze e addirittura i nemici - dalla borghesia allo straniero migrante.</p>

<p style="color: #E0E0E0;">Eribon ammette anche che, benché doloroso, identificarsi come gay gli ha permesso di entrare a far parte di una comunità che disponeva di risorse teorico-linguistiche per pensarsi, attraverso le quali era capace di comprendersi ed imporre la sua stessa narrazione del sé. Mentre aveva superato la vergogna di essere gay, non aveva superato quella di provenire da un ambiente proletario. L'iniqua distribuzione del capitale culturale, dell’accesso a canali educativi, aveva impedito alla “marginalità operaia" di riuscire ad imporsi come aveva fatto la marginalità queer.</p>

<p style="color: #E0E0E0;">In breve, riallacciandosi alla domanda di Spivak su se le persone subalterne possano parlare (essendo ascoltate), Eribon suggerisce di sì, ma a patto che si approprino del linguaggio della classe egemone.</p>

<p style="color: #E0E0E0;">Tuttavia, sembra ancora mancare per gli agricoltori e le agricoltrici una voce di raccordo, che colleghi il campo o il trattore al Parlamento, Italiano o Europeo. Se i sindacati non sono riusciti a farsi carico di questo compito, chi o cosa potrebbe contribuire a facilitare questo dialogo?</p>

<p style="color: #E0E0E0;">Quello della comunicazione, con Brunori, è un punto fondamentale, tanto da auspicare un cambiamento nella narrazione collettiva rispetto alla produzione agricola.</p>



            <hr>
        </div>
    </div>
</div>
