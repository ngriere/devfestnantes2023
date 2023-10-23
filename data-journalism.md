#  :bulb: The laundromat : quand les journalistes deviennent data analystes
> 19/10 à 13:58 - Antoine BONNEAU et Guillaume RENAUDIN / Zenika

![Discovery](https://img.shields.io/badge/Discovery-blue)

> Data with visualisation is the **new camera**

De 1972 avec l’affaire du Watergate à 2016, date à laquelle sont publiés les premiers articles relatifs aux Panama papers, le journalisme d’investigation évolue et s’enrichit de nouvelles sources de données et de nouveaux outils. 
Une ère nouvelle émerge, celle du data journalism. Armés d’exemples concrets, venez prendre conscience de l’importance de l’usage dans la data dans l’observation de faits et d’analyse de l’actualité. 
Quel est le profil de ces nouveaux journalistes? Ont-ils des formations particulières, des méthodes et outils de prédilection ? Et si vous même deveniez, à votre échelle, un citoyen informé et engagé ? 
De la découverte de sources de données avec lesquelles débuter, l’élaboration d’une démarche d’analyse à la maîtrise de quelques outils de base, récupérez un kit de démarrage pour débunker quelques news ou des phénomènes de société.

 &rarr; Sujet Hybride: Data 📊 / Journalisme 📰
 
## 1. Contexte
En 2015, prise de conscience mondiale suite aux révélations de l'affaire Panama Papers:
![Graph pour investiguer les Panama Papers](https://www.datanami.com/wp-content/uploads/2016/04/Panama_4.png)

![histoire_panama_papers](https://github.com/ngriere/devfestnantes2023/assets/9659029/44867de5-c3c9-49fb-98e4-01913daf31df)

Quelques chiffres clés:
- 214 000 sociétés offshore
- 11,5 Millions de docs fuités
- 2,6 TO de données (environ 3 pour Lux Leaks)
- 12 chefs d'états
- 128 dirigeants politiques
- 29 des 500 plus grandes fortunes
   1000 ressortissants français concernés

📽️ The Laudromat &rarr; film Netflix qui retrace l'ensemble de l'affaire gros casting

## 2. Le data journalisme

&rarr; Changement de paradigme dans le journalisme d'investigation

![changement_paradigme](https://github.com/ngriere/devfestnantes2023/assets/9659029/288d41e2-f8a0-4500-9001-f0a7aafa043c)

### Visualisation des données
> Une image vaut mille mots

Apparition d'outils dynamiques qui permettent de faire des représentations qui parlent d'elles-mêmes, comme sur le site [Information is beautiful](https://informationisbeautiful.net/) de David McCandless.

- [Most talked about fears](https://informationisbeautiful.net/visualizations/mountains-out-of-molehills/)
- [Most common passwords](https://informationisbeautiful.net/visualizations/top-500-passwords-visualized/)
- [Based on a true story](https://informationisbeautiful.net/visualizations/based-on-a-true-true-story/)

### Les objectifs du daja journalisme
- **Mieux** informer
- **Personnaliser** l'information
- **Analyser** la masse des données "ouvertes"
- Permettre une **visualisation** de l'information
- Surveillance des gouvernements, autorités, **contre-pouvoir**
- **Sensibiliser** sur des sujets moins couverts par les médias
- **Ouvrir les données** et les analyses

:warning: La donnée en tant que telle n'est pas une info.
🕵️: La data visualisation aide et l'éditorial également.


La première *"dataviz*" serait attribuée à *The Guardian* en 1821.

Autre exemple : Los Angeles Times recense tous les crimes qui ont eu lieu "Thé homicide Report". Derrière la visualisation en points, l'intérêt est de donner accès à l'histoire de chaque victime etc.

Des consortiums de journalistes : [EJC](https://ejc.net/), [ICIJ](https://www.icij.org/), [ProPublica](https://www.propublica.org/), [TBIJ](https://www.thebureauinvestigates.com/) ont créés des outils qui peuvent fournir une base de connaissance pour se former au data journalisme.

Le **but** du data journalisme est notamment de réussir à réconcilier 2 mondes en apparence opposés:
1. Le journalisme &rarr; très littéraire
2. La data &rarr; très scientifique

## 3. L'accès aux données

![camera_80efe758-5856-49e4-9d97-25c556f4b770](/camera_80efe758-5856-49e4-9d97-25c556f4b770.jpg)

Les 2 seuls procès ayant eu lieu concernent des lanceurs d'alertes. Grosse masse de données provenant des lanceurs d'alertes et alimentant le travail des journalistes d'investigation

OpenData (ex SNCF, data.gouv): bcp d'entreprises comprennent l'intérêt de mettre leurs données en accès.

Sites de références : permettent de naviguer dans l'historique des révélations etc.

Curation et extraction : data mineurs qui lisent tweeters pour lire les activités anormales. Passer du texte à l'image etc.
Webscrapping pour récupérer des données de sites (attention pas légal souvent)

Archives : rapports scientifiques etc. Arxiv, WaybackMachine

### où trouver de la data
data.gouv
Possibilité de déposer des jeux de données soit même et se nombreux consultables.
Fabriquedunumerique
Documentcloud.org

### les outils
Passer d'une donne brute à "l'histoire"

1. Traditionnel -> excel
2. Nettoyage -> Open Refine
3. Développeur -> Python, Pandas, Notebook (Jupyter, Google Collab)
4. Requêter, extraire -> SQL, Spark, Outwithub, Tabula
5. Partager -> Datashare
6. Exposer, dataviz -> Datawrapper

Et pleins d'autres:
Https://github.com/ICIJ
Osintframework.com

### et vous ? Données citoyennes
Observatoires citoyens
Ex:
- allô place Beauvau -> les violences policières 
- COVID tracker -> suivre l'évolution de la pandémie covid
- nosdéputés.fr -> presenteisme des députés, sujets courants discutés à l'assemblée.

### et vous ? Debunker ou fact-checker
![camera_390fc538-0ace-446f-9fdd-e3e1be528882](/camera_390fc538-0ace-446f-9fdd-e3e1be528882.jpg)

### démo
Datashare -> Open Refine -> Datawrapper

1. Webscrapping d'un site pour récupérer les dialogues des 5 premières minutes du film thé Laudromat
2. Passage des données dans OpenRefine -> extraire les pays mentionnés dans les films et les mentionner par rapport aux leaks Panama Papers pour voir si la couverture est exhaustive ou non.

Datawrapper -> facile à prendre en main / partage de Map collaborative

Partage de Map en temps réel -> nécessite une connexion avec Google sheets

## Ouverture
### à venir
Lancement le 24 octobre du TEMS -> plateforme collaborative pour du contenu vérifié

### médias et IA
Crainte / Opportunités
AssociatedPress et OpenAi vont collaborer
Google collabore avec le New York Times et le Washington Post.

2 approches:
US est précurseur de la dataviz, de l'ouverture des données et veut travailler avec les Big players

UE crée des collectifs pour se protéger et vérifier les données 

Radio-France : 700 journalistes
10% formes au numérique
5% des 10% travaillent dans la donnée

Grosse opportunité 
