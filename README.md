# Mise en place d'une Todo List (Express, Babel, Sequelize, PostgreSQL)

## Étapes à suivre :

1. Génération du projet avec Express generator : `express --view=pug newtodo`
2. Installation + Configuration `Babel`
  a. Installation Babel `npm install @babel/core @babel/node --save-dev`
  b. Édition de la commande `npm start` pour : `"start": "nodemon --exec babel-node src/index.js",`
  c. Installation des presets de base pour Babel : `npm install @babel/preset-env --save-dev`
  d. Création du fichier de configuration pour Babel : `touch .babelrc`
  e. Ajout des presets dans le `.babelrc` 
3. Refactoriser tous les `require` en `import`
4. Installation du système de variables d'environnement : `npm install dotenv-extended --save`
  a. Création du fichier `.env` : `touch .env`
  b. Création de la première variable d'environnement : `PORT=4000`
  c. Test d'import + test du fonctionnement de `dotenv`

