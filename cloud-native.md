
#  📝 ✅ La checklist ultime pour rendre vos applications cloud native !
> 20/10 à 14:00 - Katia HIMEUR / Cockpit Io

![Cloud & DevOps](https://img.shields.io/badge/Cloud%20&%20DevOps-green)

Aujourd’hui, le cloud permet d’améliorer la disponibilité et l’évolutivité de nos applications. Grâce au cloud, nous pouvons provisionner de nouvelles infrastructures rapidement et faire évoluer avec la même vitesse les infrastructures existantes. Nous ne présentons plus les avantages du Cloud ni la multitude de services cloud existants. De prime abord, migrer une application sur le Cloud peut sembler un sujet trivial. Mais, toutes les applications sont-elles faites pour être déployées sur le Cloud ? D'où viennent tous ces projets de migration ratés alors ?

Durant ce talk, je vous présenterai la checklist qui vous permettra de rendre vos applications véritablement "cloud native" pour tirer le meilleur de ce modèle.

## 1. Pourquoi ce talk ?
Le marché du cloud est en constante augmentation.

La tendance semble être à l'optimisation des coûts pour les applis déjà présentes dans le cloud.

Objectifs:
- partager un retour d'XP
- partager la méthode de migration vers le cloud
- donner les clefs pour réussir

## 2. Le cloud computing
> Ensemble de ressources et services fournis à la demande par le fournisseur cloud
 :bulb: le fournisseur de services cloud maintient le matériel physique
 
Ex de services : réseaux, serveurs, bdd etc.
 
3 types de Cloud:
- public
- privé
- hybride
 
 Avantages du cloud:
 - réduction des coûts
 - réduction du Time to market
 - agilité
 - Scalabilité
 
 ## 3. Le cloud native
 Approche logicielle permettant de:
 - créer déployer et gérer des applis dans des envs cloud
 - mettez en oeuvre des **systèmes faiblement couplés, résilients, manageables et observables**.
 
Comment mettre en place cette approche ?

D'après la [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/), grâce aux:
- conteneurs
- microservices
- services mesh 
- APIs déclaratives
- infrastructures immuables

### CNCF landscape

Est-ce vraiment cela le secret pour réussir sa migration ?
&rarr; Non

Que faire alors ? 
&rarr; suivre quelques règles de bases.

## Règles pour réussir sa migration cloud native
1. Ne pas se concentrer uniquement sur la technique. 
2. Définir ses objectifs. Pourquoi choisir le cloud ? Quels avantages recherchés ? Quels objectifs business ? Aller sur le cloud n'est pas un objectif mais un moyen d'atteindre les objectifs business !
3. Communiquer avant, pendant et après le projet. Même niveau d'information, rappelez les objectifs.
4. Analyser votre culture et vos pratiques. DevOps, CI/CD, degré d'automatisation ?
5. Identifier les personnes clefs. Qui maîtrise l'appli, l'infra, le déploiement ? Qui lead le projet de migration ?
6. Collaborer &rarr; task force multidisciplinaire, pas de silos
7. Analyser l'existant : archi, dépendances, version, s'assurer qu'on est stateless, données à transférer, ressources actuelles utilisées, trafic, l'observabilité
8. Faire un point sécurité : contraintes réglementaires, procédures, détection de vulnérabilités.
9. Cadrer votre projet : Scopes applicatif et infrastructure concernés. Choix de l'archi cible, choix du ou des fournisseurs cloud. Anticiper les besoins de formation des équipes. Anticiper le cost management et l'impact écologique.
10. Établir ses KPIs : quoi suivre pour évaluer la réussite ?
11. Préparer son appli : microservices, serverless, conteneurisation, observabilité ?
12. Préparer le jour J: check-list et étapes de migration, rollback en cas de problèmes, DNS, transfert de données ? Tester ce scénario. Est-ce qu'on fait du blue/green ou du canary ?
13. Se préparer aux surprises: Loi de shatterton et de Murphy
14. Documenter: faire au fur et à mesure
15. Itérer: ajuster l'infrastructure et le dimensionnement, ajuster le monitoring

## Stratégies de migration

| Stratégie | Description  |
|----|----|
|  **Refactor / Re-architect**  | Migrer en refactorant l'archi de son application   |
| **Re-platform (Lift & Reshape)**  | Migrer en apportant quelques optimisations uniquement |
| **Repurchase (Drop & Shop)**   | Passage du **on premise** à un modèle SaaS |
|  **Rehost (Lift & Shift)**  | Migrer l'application telle qu'elle. Peut-être une étape intermédiaire. |
   |  **Retain (Revisit)**  | Pas de migration |
| **Retire**   | Décomissionnement   |
 
