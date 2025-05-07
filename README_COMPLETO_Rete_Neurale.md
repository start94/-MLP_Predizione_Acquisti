
# 🧠 Rete Neurale - Predizione Acquisti

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/start94/MLP_Predizione_Acquisti/blob/main/Rete_Neurale_Predizione_Acquisto.ipynb)

![Anteprima del progetto](https://raw.githubusercontent.com/start94/MLP_Predizione_Acquisti/main/preview.png)

Questo progetto implementa una rete neurale **feedforward (MLP)** per predire se un utente acquisterà un prodotto in base a dati demografici e comportamentali.

## 🎯 Obiettivo
Addestrare un modello di classificazione binaria (0 = non acquista, 1 = acquista) su un dataset simulato.

## 📊 Dataset Fittizio
Il dataset è generato artificialmente e contiene 500 righe con le seguenti feature:

- `Eta` (18–65 anni)
- `Salario` (euro)
- `Genere` (M/F)
- `Stato_civile` (Single/Sposato)
- `Visite_sito` (numero di visite)
- `Acquisto` (target: 0 = No, 1 = Sì)

## ⚙️ Tecnologie usate
- Python
- Pandas / NumPy
- Scikit-learn (preprocessing, valutazione)
- TensorFlow / Keras (rete neurale)
- Matplotlib (grafici)
- Ipywidgets (interfaccia interattiva)

## 🧪 Architettura della rete neurale
- Input layer: dati preprocessati
- Hidden layer 1: 32 neuroni, ReLU
- Hidden layer 2: 16 neuroni, ReLU
- Output layer: 1 neurone, Sigmoid

Loss function: `binary_crossentropy`  
Ottimizzatore: `adam`

## 📈 Output del notebook
- Accuracy, precision, recall
- Confusion matrix
- Grafici di loss e accuracy
- Interfaccia interattiva per testare nuovi utenti

## ▶️ Come usarlo

1. Apri il notebook con il badge **Open in Colab**
2. Esegui tutte le celle in ordine
3. Prova la rete con l’interfaccia interattiva alla fine

## 📝 Autore
Raffaele Diomaiuto  
GitHub: [@start94](https://github.com/start94)

---

⚠️ *Il dataset è simulato a scopo didattico.*
