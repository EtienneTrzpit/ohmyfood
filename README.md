
## Installer les dépendances

lancez la commande npm install 

## Explication de l'installation

Initialiser le projet

npm init

Installer sass

npm install sass --save-dev

un dossier node_modules a été ajouté automatiquement

Il serait possible de tranpiler du Sass avec le CSS en utilisant la commande (on ne parle pas de compilation)
sass src/style.scss dist/style.css
ce qui veut dire sass fichier source fichier de destination

## Créer un dossier src/scss

A l'intérieur du dossier scss placer le fichier style.scss


## Installer le script de lancement de Sass watch (avec surveillance des modifications) dans l'application depuis le fichier package.json

  "scripts": {
    "sass": "sass --watch src/scss:dist/assets/css"
  },

## Lancer la transpilation

npm run sass

Un dossier dist est créé avec style.css

## Placer le css dans le fichier index.html

```
<link rel="stylesheet" href="dist/assets/css/style.css">
```











