# 02-digit-classification-mnist

# ENG 🇬🇧
## MNIST handwritten digit classification with TensorFlow/Keras.  
This repo contains a TensorFlow/Keras project for classifying MNIST handwritten digits (0–9), a compact CNN implemented in a Jupyter notebook, a minimal data pipeline, and cells to evaluate the model on the standard test split or on your own images after resizing to 28×28 grayscale. Reproducible seeds, saved weights, and simple prediction/visualization cells included.

## Dataset
We use the MNIST Handwritten Digit Database (60k train / 10k test, 28×28 grayscale).  
The dataset is distributed and maintained by Yann LeCun and collaborators at NYU: https://yann.lecun.com/exdb/mnist/

## Quick start
1. Clone the repo and create a virtual environment.
2. Install dependencies and run the notebook.

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt  # or: pip install tensorflow numpy matplotlib jupyter
jupyter lab  # or: jupyter notebook
```

# ITA 🇮🇹
## Classificazione di cifre scritte a mano del dataset MNIST con TensorFlow/Keras.  
Questo repository contiene un progetto TensorFlow/Keras per classificare le cifre manoscritte MNIST (0-9): una CNN compatta implementata in un notebook Jupyter, una pipeline dati semplice, un griglia di output per valutare il modello sul test set standard oppure su immagini proprie dopo il ridimensionamento a 28×28 in scala di grigi. Include seed per la riproducibilità, pesi salvati e una griglia semplici per la visualizzazione.

## Dataset
Utilizziamo il Dataset MNIST formato da 70'000 immagini di numeri scritti a mano (60k train / 10k test, 28×28 scala di grigi).  
Il dataset è distribuito e mantenuto da Yann LeCun e collaboratori (NYU): https://yann.lecun.com/exdb/mnist/

## Avvio rapido
1. Clona il repo e crea un ambiente virtuale.
2. Installa le dipendenze ed esegui il notebook.

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt  # oppure: pip install tensorflow numpy matplotlib jupyter
jupyter lab  # oppure: jupyter notebook
