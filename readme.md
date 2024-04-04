# Application Web de Gestion de smartphones

Ce projet est une application web simple pour la gestion de smartphones. L'objectif est de permettre aux utilisateurs d'ajouter des informations sur leurs smartphones à une base de données CSV à l'aide d'un formulaire web.

## Technologies utilisées

- Python
- Flask (un framework web Python)
- HTML
- CSV (pour le stockage des données)

## Fonctionnement de l'application

L'application comporte deux pages principales :

1. **Page d'accueil (`index.html`)** :
    - Cette page contient un formulaire où l'utilisateur peut saisir les informations sur son véhicule (numéro, marque, modèle, année).
  
2. **Page de résultat (`result.html`)** :
    - Après avoir soumis le formulaire, cette page affiche un message de confirmation.

## Structure du Code

- **`app.py`** : Ce fichier contient le code principal de l'application.
    - Il définit deux routes :
        - `/` : pour la page d'accueil.
        - `/submit` : pour la soumission du formulaire.
    - Lorsqu'un utilisateur soumet le formulaire, les données sont récupérées et enregistrées dans un fichier CSV.
  
- **`index.html`** : Le modèle HTML de la page d'accueil contenant le formulaire.

- **`result.html`** : Le modèle HTML de la page de résultat affichant un message de confirmation.

## Comment exécuter l'application

1. Assurez-vous d'avoir Python installé sur votre système.
2. Installez Flask en exécutant `pip install flask` dans votre terminal.
3. Exécutez le fichier `app.py` en utilisant la commande `python app.py`.
4. Accédez à l'application dans votre navigateur en entrant l'URL `http://localhost:5000`.

---
