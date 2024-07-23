Come abbiamo realizzato la sentiment analysis:
- abbiamo estratto con TagMe le entità dai commenti.
- abbiamo filtrato quei commenti che contenessero l'entità "sindacato" oppure "coldiretti".
- abbiamo utilizzato la libreria FEEL-IT per realizzare la sentiment anlysis.

La libreria FEEL-IT dispone di due metodi, uno restituisce se il commento è positivo o negativo, l'altro l'emozione con cui è stato scritto il commento (fra anger, sadness, fear e joy).