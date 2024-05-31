Projet Docker

Ce projet contient les fichiers suivants :
- Dockerfile : Décrit la création d'une image Docker basée sur une distribution Linux avec Python installé, et ajoute le fichier Python `prediction_cup_winner.py` dans le répertoire `/app`.
- prediction_cup_winner.py : Un fichier Python qui exécute le script de prédiction.
- docker-compose.yml : Définit deux services :
  - app : Utilise le Dockerfile pour créer une image Docker et exécuter le script Python.
  - db : Utilise l'image officielle de PostgreSQL pour créer un service de base de données.

Instructions :
1. Décompressez le fichier dans un répertoire de votre choix.
2. Naviguez vers ce répertoire dans votre terminal.
3. Exécutez la commande `docker-compose up` pour lancer les services.

Captures d'écran :
(inclure ici des captures d'écran montrant les conteneurs en cours d'exécution, si possible)
