# Modèle de configuration de Webpack pour WordPress

## Installation

1. Exécuter dans le répertoire la commande `npm install` qui va installer toute les dépendances Node.js nécessaire au bon fonctionnement de l'application.
2. Exécuter une des commandes ci-dessous.

## Commandes disponibles

- `npm run start` : Démarre le serveur de développement en utilisant [Browsersync](https://www.browsersync.io/)
- `npm run build:dev` : Génère les ressources front sans compression en vue d'une utilisation dans un environnement de développemnt
- `npm run build:prod` : Génère les ressources front avec compression (minify, uglify) en vue d'une utilisation dans un environnement de production
- `npm run clean` : Supprime les fichiers générés par Webpack
- `npm run clean:all` : Supprime les fichiers générés par Webpack ainsi que le répertoire des dépendances installées avec NPM (`node_modules`)

## Prérequis (à ne faire qu'une fois à la première utilisation de Webpack)

1. Installer la dernière version de Node.js avec le package `n` :
    - `sudo npm install -g n`
    - `sudo n lts`
2. Installer les packages `webpack`, `webpack-cli` et `webpack-dev-server` en global
    - `sudo npm install -g webpack webpack-cli webpack-dev-server`
