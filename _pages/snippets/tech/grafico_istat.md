**Dati ISTAT sull'Agricoltura in Italia**

Questo grafico è stato ottenuto dai dati relativi all'__Agricoltura in Italia (dal 2006 al 2023)__, scaricati in formato .csv dal <a href="https://www.istat.it/statistiche-per-temi/economia/agricoltura/">sito dell'Istat </a>.

Il dataset contiene delle metriche relative all'Agricoltura per ogni tipologia di coltivazione, per ogni anno e per ogni territorio (Italia, regione, provincia e zona).

Dal dataset di partenza sono state selezionate le seguenti colonne di interesse:

1. __Tipo dato.__ Contiene i nomi delle metriche:
   - __superficie totale - ettari__, rappresenta la SAU + i territori boschivi;
   - __superficie totale - are__, rappresenta i territori boschivi;
   - __superficie in produzione - ettari__, rappresenta la SAU;
   - __produzione totale - quintali__;
   - __produzione raccolta - quintali__;

2. __Tipo di coltivazione.__ Contiene tutte le tipologie di coltivazione presenti in Italia;

3. __TIME.__ Contiene gli anni dal 2006 al 2023;

4. __Value.__ Contiene il valore delle metriche;

5. __Territorio.__ Contiene i nomi delle regioni, delle provincie e delle zone d'Italia.

Le fasi che hanno portato alla produzione del grafico sono le seguenti:

1. __Pulizia dei dati.__ Dal 2020 l'Istat ha iniziato a raccogliere i dati in una modalità diversa rispetto a prima. Dunque abbiamo dovuto pulire i dati per uniformarli al passato;

2. __Aggregazione dei dati.__ Abbiamo raggruppato i dati per _metrica_, _anno_ e _territorio_ e calcolato la somma dei valori delle metriche di tutti i tipi di coltivazione. 

3. __Filtraggio dei dati.__ Abbiamo filtrato solamente i dati riferiti al territorio __Italia__;

3. __Creazione del grafico.__ Abbiamo creato il grafico interattivo in `Altair` con un menù a tendina, per la selezione del __Tipo dato__. Il grafico mostra i valori dell'Italia per la metrica selezionata per ogni anno dal 2006 al 2023.









