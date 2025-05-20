# ⚙️ Installation

### 📁 Cloner le projet (si nécessaire)

```bash
git clone https://github.com/Stickplick98/daily-climate-time-series-machine-learning
```

### 🐍 Python

Le projet devrait fonctionner avec la majorité des versions de Python. Cependant, si ce n'est pas le cas, la version 3.11.9 a été testée et est fonctionnelle.

🔗 https://www.python.org/downloads/release/python-3119/

### 📦 Dépendances

Les dépendances peuvent être installées avec la commande suivante :

```bash
pip install -r requirements.txt
```

### 🧪 Kaggle

Le projet utilise un dataset via l'API de Kaggle. Celle-ci nécessite un `username` et une `key` afin de pouvoir s'authentifier

#### 1. Créer un compte sur Kaggle

🔗 https://www.kaggle.com

#### 2. Créer une clé d'API

- Cliquer sur l'icône en haut à droite et sélectionner "Settings"
- Scroller jusqu'à voir "API" et cliquer sur "Create New Token"

Un fichier `kaggle.json` vous sera téléchargé

#### 3. Ajouter les credentials au `.env`

- Créer un `.env` à la racine du projet

- Copier le contenu du `.env.example` dans le `.env` précédemment créé

- Compléter le `.env` avec les valeurs correspondantes trouvées dans le `kaggle.json` précédemment téléchargé lors de l'étape `2`

# 🤝 Contributions

[Guide de contribution](CONTRIBUTING.md)

# 🚀 Commencer la lecture

👉 [Introduction](./notebooks/00_introduction.ipynb)
