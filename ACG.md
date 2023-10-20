
# L'AGC : retour sur l'ordinateur qui a amené l'humanité sur la Lune 
> 20/10 à 15:10 - Olivier PONCET et Romain BERTHON

![Discovery](https://img.shields.io/badge/Discovery-blue)

Lundi 21 juillet 1969, l’humanité posait pour la première fois le pied sur la Lune. Cet exploit est le fruit de nombreuses avancées techniques et technologiques, notamment en électronique et dans le domaine de l’informatique alors naissant. Pour mener à bien leurs missions, les astronautes s’appuyaient sur l’**Apollo Guidance Program (ACG)**, l’ordinateur de bord du programme Apollo qui permettra de réaliser ces exploits.

## 1. Contexte
- 4 octobre 1957 : Spoutnik en orbite
- 29 juillet 1958 : création de la NASA
- 12 Avril 1961 : premier russe en espace - vol autour de la Terre
- 25 mai 1961, discours de Kennedy devant le congrès américain pour amener le premier humain sur la lune.

&rarr; Le constat est dure, dans la course à la Lune, les Américains sont à la traîne.

&rarr; Le défi technologique est immense.

## 2. Les responsabilités de l'ACG 

1. La navigation inertielle - *Charles Stark Draper - père de ma navigation inertielle* &rarr; L'AGC embarque une BDD avec un ensemble d'étoiles de références pour pouvoir naviguer de référentiel en référentiel. Toujours 5 référentiels suivis en permanence.
2. Le Digital Autopilot (DAP)
3. Afficher des données à l'équipage
4. La liaison avec le sol et la télémétrie.

## 3. le Hardware
Voici ses caractéristiques techniques: 
- Fréquence principale de 2 MHz. - Processeur en complément à 1 (pour représenter des nb négatifs, on rajoute un 1 devant). Ajd, tous les processeurs sont en complément à 2
- Largeur des registres de 16-bits (dont 1 de contrôle)
- Poids de 32kg
- Puissance inférieure à un Nokia ou une calculatrice scientifique

L'ACG s'appuie sur une archi simple et efficace.

### Processeur
L'ordinateur est construit avec des portes NOR. Pour stocker l'état d'un bit: le match: 2 portes NOR suffisent. Pour stocker un bit en dehors de la RAM on utilise des registres.
- L'ALU : environ 240 portes NOR.

### La mémoire vive
2048 mots de 15 bits + 1 bit de contrôle
- soit 4kB de mémoire vive.

### La mémoire morte (core rope memory)
36864 mots de 15 bits + 1 bit de parité
- soit 72Kb de mémoire de travail

### Interpréteur : la VM de l'AGC
Avec son propre langage (interpretive) qui compile en assembleur


## 4. Le software
Le **Display and Keyboard (DSKY)** compose l'interface utilisateur.
Pour interagir avec la machine : Programmes, verbes et noms

Ex : allumer les lampes du DSKY

`VERB` `3` `5` `ENTR`

Le **DSKY** doit pouvoir afficher une surcharge de travail.

Il supporte le multi processing.

Voici Margaret Hamilton du MIT à côté de la base de code de l'ACG:

![margaret-hamilton-mit.jpg](https://github.com/ngriere/devfestnantes2023/assets/9659029/a7b93ff8-d430-4140-89fa-8b691f9caf03)

## 5. Héritage du programme Apollo
- Grosses avancées dans la micro-electronie
- les télécommunications
- informatique
- aéronautique
- aérospatiale
- automobile

Découverte et évolutions technologiques :
- les circuits intégrés
- l'informatique embarquée
- la programmation temps réel
- la nourriture lyophilisée
- les couches bébé (pour les astronautes)


