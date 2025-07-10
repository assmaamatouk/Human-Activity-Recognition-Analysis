# Human Activity Recognition - HAR Project

Questo progetto è stato realizzato per l'esame del corso di Big Data e si occupa del riconoscimento delle attività umane (Human Activity Recognition) attraverso l'analisi di dati provenienti da sensori.

## Obiettivo

L'obiettivo è costruire modelli di classificazione in grado di riconoscere l'attività svolta da una persona (es. camminare, stare seduti, correre...) partendo da segnali raccolti da dispositivi mobili o sensori wearable.

## Tecnologie utilizzate

- Python
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- TensorFlow (per il modello deep learning)
- Analisi statistica (ANOVA), PCA, Clustering
- Jupyter Notebook

##  Struttura del repository

```
HAR-Activity-Recognition/
├── data/                  <- Contiene i file CSV con i dati
├── HAR_analysis.ipynb     <- Notebook principale con tutta l’analisi
├── requirements.txt       <- Librerie necessarie
├── README.md              <- Descrizione del progetto
├── .gitignore             <- File e cartelle da ignorare in Git

```

##  Dataset

I dati utilizzati per l’analisi sono inclusi nella cartella `data/`:
- `train.csv`: dati per l’addestramento
- `test.csv`: dati per la valutazione finale

## Modelli implementati

- Regressione Logistica
- Random Forest
- TensorFlow
- PCA per la riduzione dimensionale
- Clustering (KMeans)

##  Risultati

I modelli sono stati confrontati in termini di accuratezza, curva di apprendimento, matrice di confusione e altre metriche.


