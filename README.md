# ML-AI-APPLICATIONS-TO-HEALTH-DOMAIN
Codice sorgente e materiali computazionali della tesi di laurea sul machine learning applicato alla diagnosi precoce del diabete e alla previsione delle riammissioni ospedaliere.

La tesi analizza due casi di studio:

1. **Diagnosi precoce del diabete** utilizzando il *Pima Indians Diabetes Dataset* (Capitolo 4).
2. **Previsione delle riammissioni ospedaliere** utilizzando il *Diabetes 130-US Hospitals Dataset* (Capitolo 5).

## Struttura del repository

```text
├── Chapter_4_Diabetes_Classification/
│   ├── diabetes_analysis.ipynb   # Notebook completo del Capitolo 4
│   └── diabetes.csv              # Pima Indians Diabetes Dataset
│
├── Chapter_5_Hospital_Readmission/
│   └── Diabetes_hospitals.ipynb  # Notebook completo del Capitolo 5
│
└── README.md
```

## Dataset

* **Pima Indians Diabetes Dataset**: incluso in questo repository (`Chapter_4_Diabetes_Classification/diabetes.csv`).
* **Diabetes 130-US Hospitals Dataset**: *non incluso* in questo repository per motivi di dimensione. È disponibile pubblicamente su:

  * UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

## Contenuto dei notebook

### Capitolo 4 – Diagnosi precoce del diabete

* Analisi esplorativa (EDA) e gestione dei valori mancanti/anomali
* Pre-processing e scaling delle feature
* Confronto tra modelli classici: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, SVM
* Hyperparameter tuning (Grid Search)
* Rete neurale MLP (scikit-learn)
* Reti neurali profonde in PyTorch (architetture Base, Advanced, Ultimate)
* Rete neurale in TensorFlow/Keras
* Valutazione clinica tramite bootstrap, AUC-ROC, Brier Score, analisi di soglia

### Capitolo 5 – Previsione delle riammissioni ospedaliere

* Feature engineering su dataset ad alta dimensionalità (>100.000 record)
* Mappatura delle diagnosi ICD-9
* Gestione dello sbilanciamento delle classi con SMOTE
* Split basato sul paziente (Group-based split / Stratified Group K-Fold) per evitare data leakage
* Confronto modelli classici e hyperparameter tuning
* Reti neurali profonde in PyTorch e TensorFlow
* Valutazione tramite bootstrap, AUC-ROC, analisi delle probabilità

## Tecnologie utilizzate

* Python
* NumPy, pandas
* scikit-learn
* imbalanced-learn (SMOTE)
* Matplotlib, Seaborn
* PyTorch
* TensorFlow / Keras

## Note

I notebook non contengono credenziali, chiavi API o dati sensibili identificativi. I dataset utilizzati sono pubblici e de-identificati.
