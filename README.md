# Projet-6

Ce projet consistait à effectuer la partie Back-End d'une application de sauce en utilisant Node.js avec le frameworks express.js et une base de donnée MongoDB.

Installation

- Cloner ce projet depuis GitHub.


Faire tourner le Frontend

- Ouvrir le terminal sur ce dossier et exécuter npm install pour installer les dépendances.
- Exécuter npm install node-sass pour installer sass.
- Le projet a été généré avec Angular CLI version 7.0.2.
- Démarrer ng serve (ou npm start) pour avoir accès au serveur de développement.
- Rendez-vous sur http://localhost:4200.
- L'application va se recharger automatiquement si vous modifiez un fichier source.


Faire tourner le Backend

- Renommer le fichier ".env.test" en ".env"
- Mettre vos identifiants de connexion à la base de données dans les guillemets. Par exemple : "mongodb+srv://{Identifiant}:{Mot de passe}@cluster0.ntj6t.mongodb.net/myFirstDatabase?retryWrites=true&w=majority"
- Ouvrir le terminal sur ce dossier.
- Pour utiliser le serveur, chargez le package nodemon : npm install -g nodemon.
- Puis lancez le serveur: nodemon server.
- Pour faire court
- Si les packages sont déja installés, ces commandes suffisent à démarrer les serveurs.


- npm start via le terminal sur le frontend
* nodemon server via le terminal sur le backend
- Se connecter à l'url : http://localhost:4200


Connexion

- Ouvrir localhost:4200 dans votre navigateur.
- Pour s'inscrire sur l'application, l'utilisateur doit fournir un email et un mot de passe contenant 08 caractères minimum (dont 1 majuscule, 1 minuscule, 1 chiffre, pas de symbole, espaces autorisés).
