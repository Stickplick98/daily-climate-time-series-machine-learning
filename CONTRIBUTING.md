# Ajouter les nouvelles dépendances aux projets

## Créer un environnement virtuel (si pas déja fait)

Dans le dossier du projet à la racine :

```bash
python -m venv venv
```

Activation de l'environnement : 

```bash
env\Scripts\activate
```

## Ajouter les nouvelles dépendances

Si vous ajoutez des dépendances ajoutez les au `requirements.txt` pour faciliter le travail du prochain :


```bash
pip freeze > requirements.txt
```

# Branches

Faites des branches quand vous travaillez pour que ça soit plus propre et pour faciliter la collaboration 

# Pull Requests

Une fois le travail fini sur une branche (pas trop faire par branche) faire une pull request sur Github vers la main et ajouter des reviewers 

