# Slides Agile Laval 2016

## Prérequis

Une stack JS:

- node
- npm
- yeoman

## Technos

Reveal.js pour les slides en mode serveur.

On utilise un générateur YeoMan pour générer la structure du projet: 
https://github.com/slara/generator-reveal

Markdown pour les slides

## Installation

```./install.sh```

## Utilisation

Pour générer un nouveau slide en Markdown:

```bash
yo reveal:slide "Nom de mon super slide" --markdown
```

## Lancement

```grunt serve```

=> http://localhost:9000

Note: alias grunt="./node_modules/grunt-cli/bin/grunt"


## Notes

Pendant la présentation, taper 's'
