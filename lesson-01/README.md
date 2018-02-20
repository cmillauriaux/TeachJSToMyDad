# Cours 1 : Mise en place

## Création d'un projet

Pour créer un projet, c'est très simple : il suffit de créer un répertoire avec un fichier texte `main.js` à l'intérieur. Le nom du fichier importe peu, c'est une convention pour que l'on puisse connaitre le fichier principal une fois que le projet glonfle un peu et qu'il y a plusieurs dizaines de fichiers dans le répertoire.

> **Astuce** : Dans Visual Studio Code, clic droit dans l'explorateur (ou dans le menu `Fichier`) et sélectionne `Nouveau fichier` 

## Ecrire dans la console

Le problème quand on commence à programmer c'est qu'on a du mal à voir ce qu'il se passe dans un programme. Il existe bien sur des moyens pour afficher des informations dans une page web, une application mobile ou via un arduino mais tout cela nécessite de mettre en place des librairies et de bien connaitre le développement. Pour simplifier, on peut écrire directement dans la console Windows (ou Linux, ou OSX), ce qui est accessible simplement.

```javascript
console.log("Bonjour tout le monde");
```

> Une chaine de caractères est toujours déclarée à l'aide du caractères `"` ou `'`. Il est important d'ouvrir et de fermer les chaines de caractères avec ces caractères.

## Lancement d'un projet

Pour lancer le projet, il faut ouvrir une console et tapper la commande `node main.js`

> **Astuce** Dans Visual Studio Code, tu peux ouvrir une commande en ouvrant le menu `Afficher`, puis `Terminal intégré`. Il faut ensuite se déplacer dans le bon dossier en tappant la commande `cd mon_repertoire`. Ici ce sera donc `cd lesson-01`.