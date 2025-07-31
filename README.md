# Cross-Selling-di-polizze-assicurative-
Fourth Project of the Master in Data Science by Professional.AI

Questo progetto si pone alla fine del modulo sui fondamenti del Machine Learning. La problematica da affrontare è stata quella di creare un modello di cross-selling di polizze assicurative, in particolare, sfruttando le tecniche dell'apprendimento supervisionato, dovevo determinare un modello per prevedere quali clienti in possesso di una polizza medica, sarebbero stati propensi all'acquisto di un'assicurazione per la macchina.

Il progetto è stato svolto secondo questi punti:
- Esplorazione del dataset: ricerca duplicati e valori mancanti, analisi descrittiva delle features qualitative e quantitative, analisi multivariata per le features quantitative con matrice di correlazione e pairplot, U-test di Mann-Whitney per determinare la presenza di relazione statisticamente significativa di quest'ultime col target. Per le features qualitative creazione di grafici a barre delle loro modalità normalizzate con quelle del target, test del $$X^2$$ per valutare l'associazione significativa tra le variabili e il target.
- Gestione dello sbilancaimento delle classi: per il bilanciamento delle classi ho svolto esperimenti usando l'attributo balanced ma anche con metodologia SMOTE, undersampling e oversampling.
- Costruzione del modello predittivo: dopo aver diviso il dataset in train e test ho verificato l'equivalenza statistica dei due attraverso il test di Kolmogorov-Smirnov. Dopo aver eseguito la standardizzazione, l'encoding delle variabili quantitative, ho creato dei modelli di regressione logistica, validati tramite cross-validation con ricerca della soglia ottimale (quella che massimizza F1-Score), matrice di confusione e utilizzo delle metriche Recall, Precision e ROC Curve.

Linguaggio di programmazione: Python 
