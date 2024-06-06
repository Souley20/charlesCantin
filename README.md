# Projet Studi / Eval d’entrainement

Charles Cantin, une personne de votre entourage, est passionné par la photographie.
Même s’il pratique en amateur, son talent est reconnu et beaucoup font appel à lui pour immortaliser 
leurs événements.

## Déploiement en local

### 1\. Clone le dépot Git

```
https://github.com/Souley20/CharlesCantin.git

```

### 2\. Naviguer et sélectionner le répertoire

`cd CharlesCantin`

### 3\. Installer les dépendances

`npm install`

### 4\. Construire le projet pour générer la 1ère feuille de style CSS

Cette étape n’est à réaliser que lors du tout 1er lancement du projet.

`npm run build`

Pour utiliser le processeur d'image Sharp avec <picture> ou <img> ou CSS background-image, ou autres, vous devez installer la documentation Eleventy-img sur 11ty.dev.

`npm install --save-dev @11ty/eleventy-img`

### 5\. Configurer le back-end en local

Dans le répertoire src/admin du projet, dans le fichier config.yaml :

Passer la valeur à : `true`

// Please run "npx netlify-cms-proxy-server" for local backend

`local_backend: true`

### 6\. Lancer le back-end en local
