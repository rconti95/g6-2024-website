**Classificazione dell'uso del suolo**

Abbiamo generato una classificazione dell'uso del suolo e della copertura del suolo di 4 regioni italiane utilizzando la libreria `Pytorch` per la classificazione delle immagini satellitari in un range che va dal 2015 al 2023.  

Per la classificazione delle immagini satellitari abbiamo usato un dataset con 10 categorie LULC (EuroSAT) e un modello __CNN Resnet-50__.    

__EuroSAT__ contiene 27,000 immagini satellitari etichettate (64x64 pixel) con 10 diverse categorie LULC. In questo progetto ci siamo concentrati sulla classificazione delle immagini RGB. 

L’approccio è stato di usare un modello pre-addestrato Resnet-50 facendo un fine-tuning del modello Resnet-50 sul dataset EuroSAT.  

Per scaricare le immagini su abbiamo usato __Google Earth Engine (GEE)__: un archivio pubblico di immagini satellitari e dataset geospaziali storici.

Infine viene generato un grafico interattivo in `Altair` con un menù a tendina, per la selezione del __Tipo dato__. Il grafico mostra i valori dell'Italia per la metrica selezionata per ogni anno dal 2015 al 2023.
