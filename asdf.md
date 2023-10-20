# 📝asdf, un outil pour toutes vos versions 
> 19/10 à 17:50 - Sylvain METAYER / Onepoint

![Outils](https://img.shields.io/badge/Outils-orange)

Fatigué de devoir installer 50 outils différents pour changer de version de node/java/terraform/... ?

Vous aimeriez trouver un outil pour gérer de la même façon toutes les versions de vos outils, voir créer vos propres plugin pour gérer les versions de votre nouvel outil ?

Venez à la rencontre d'asdf et voyons comment il pourra vous aider au quotidien

[asdf](https://asdf-vm.com/guide/getting-started.html) est un outil permettant de gérer les versions de nos différents outils.

## 1. Installation asdf
Aller sur le site officiel et suivre la procdédure officielle

## 2. Concepts
### Plugins
Trouver un plugin sur le [repo officiel](https://github.com/asdf-vm/asdf-plugins)

Pour ajouter un repo:
```bash
asdf plugin-add <plugin-name> <optional-repo-url>
```

### .tool-versions
Ce fichier repertorie les versions utilisées des outils. AU sein d'un projet, il est intéressant de déclarer ce fichier afin de figer les dépendances locales des outils au sein du projet.

### shims
Petits wrappers qui indique quelles versions utiliser

## 3. Local vs. global
![image](https://github.com/ngriere/devfestnantes2023/assets/9659029/bf4ba2d6-38f9-4689-9fac-870face5fe43)

Installation d'une version: `asdf install <plugin> <version>`

Pour fixer une version globale:
```bash
asdf global <plugin> <version>
asdf global nodejs latest
```

Pour fixer une version locale:
```bash
asdf local <plugin> <version>
asdf local nodejs 18.18
```

Pour fixer la version du shell courant:
```bash
asdf <plugin> <version>
asdf shell nodejs 18.18
```

Lister les versions installées:
```bash
asdf list nodejs
```

## 4. Création d'un plugin custom
Suivre les instructions en prenant le template de création d'un plugin de base: https://github.com/asdf-vm/asdf-plugin-template

Structure d'un plugin:

![image](https://github.com/ngriere/devfestnantes2023/assets/9659029/51d5eb0e-2456-4d45-9caf-4f94461e024b)


## 5. Ressources
- [asdf Plugin Manager](https://github.com/asdf-community/asdf-plugin-manager)
- [Site de la prez](https://r.sylvain.dev/devfest-nantes2023)

