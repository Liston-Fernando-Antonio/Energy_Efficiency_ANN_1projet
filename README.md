# Energy_Efficiency_ANN_1projet

# Energy_Efficiency_ANN

Mini projet d’Artificial Neural Network (ANN) pour prédire la consommation énergétique des bâtiments (Heating Load et Cooling Load) à partir de caractéristiques géométriques et d’orientation.

📂 Structure du projet
Energy_Efficiency_ANN/
├── notebooks/
│ ├── training_model.ipynb # Entraînement du modèle
│ └── predict_model.ipynb # Prédictions sur de nouvelles données
├── models/
│ ├── Energy_Efficiency_Model.h5 # Modèle entraîné
│ ├── scaler_X.pkl # Scaler des features
│ └── scaler_y.pkl # Scaler des labels
├── data/
│ └── energy_efficiency_data.csv # Dataset
├── .gitignore
├── requirements.txt
└── README.md

⚙️ Installation

Cloner le projet :

git clone
cd Energy_Efficiency_ANN1Projet

Créer un environnement:

python -m venv venv

# Sur Windows

venv\Scripts\activate

# Sur macOS/Linux

source venv/bin/activate

Installer les dépendances :

pip install -r requirements.txt

📖 Utilisation

Entraîner le modèle (créer le dossier notebooks) :

Ouvrir et exécuter notebooks/training_model.ipynb

Le modèle sera sauvegardé dans models/Energy_Efficiency_Model.h5

Les scalers seront sauvegardés dans models/scaler_X.pkl et models/scaler_y.pkl

Faire des prédictions :

Ouvrir notebooks/predict_model.ipynb

Modifier les exemples de données si nécessaire

Exécuter pour obtenir les prédictions de Heating Load et Cooling Load

📊 Fonctionnalités

ANN avec 2 couches cachées (64 et 32 neurones)

Prédiction simultanée du Heating Load et Cooling Load

Normalisation des données avec MinMaxScaler

Suivi de l’entraînement avec MLflow

Visualisation des performances et des prédictions

🔖 Technologies utilisées

Python 3.x

TensorFlow / Keras

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn

MLflow
