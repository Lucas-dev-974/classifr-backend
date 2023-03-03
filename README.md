# Brief-2C - backend

Ce projet à pour object d'offrir un backend à l'application web ClassiFr, une app qui intègre de l'intelligence artificielle pour faire des prédiction sur les catégorie d'image. 
Le backend va permettre d'admistrer des droit d'entrainement, d'ajout de catégories (classes).. à certein utilisateur mais vas aussi permettre d'utiliser le modèle entrainer via une requête web.

Dépendances Requise:
  - hug
  - psycopg2
  - SQLAlchemy
  - Keras
  - joblib
  - pillow
  - numpy
    - ... (sous dépendance)
  - Voir requirements.txt  

Lancer le server dans l'environement venv:
  - .venv/Script/Activate.ps1
    - hug -f server.py (lance le serveur hug)
    - py database/database.py (lance les migration)
