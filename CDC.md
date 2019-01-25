# Site web pédagogique permettant l'attaque d'un chiffrement mono-alphabétique
## Projet S6
## Année scolaire 2018-2019

-------------

* DUVAL Paul
* MALHERE Bastien
* PRUVOST--COUVREUR Gabin
* WARET Amélie


## Cahier des charges fonctionnel
### Présentation
L'objectif du projet est de développer un site Web permettant le déchiffrement de messages cryptés à l'aide d'un chiffrement par substitution aussi appelé chiffrement par substitution.
Le site Web proposera différentes façons de déchiffrer ou de chiffrer des messages. 

### Énoncé du besoin
<img src="https://github.com/fruitsec/appliInfo/blob/master/IMG_20190125_001009.jpg" >

### Validation du besoin

#### Pourquoi ce besoin existe-t-il ?
Lors des forums et des fêtes de la science, un site Web tel que celui que nous prévoyons de créer permettrait à des lycéens ou des collégiens de découvrir le chiffrement et l'attaque de messages cryptés à travers une interface simple et des exercices de réflexion ludiques. Un élève peut par exemple crypter un message que son camarade devra déchiffrer. Le site permettra dans un premier temps de divertir les visiteurs des fêtes de la science, mais aussi de servir à intéresser certains d'entre eux aux problématiques liées au chiffrement, déchiffrement et aux attaques de ces différents processus.

#### Ce besoin peut-il évoluer ?
Tant qu'il faudra faire découvrir la sécurité et le cryptage à des élèves, le besoin existera. Ce besoin disparaîtra lorsque les fêtes de la science disparaîtront. 

#### Ce besoin peut-il évoluer ? 
Le besoin évoluera en même temps que la technologie. Un site simple comme celui que nous allons produire devrait rester à jour quelques années avant de devoir être adapté aux nouvelles méthodes de cryptage et aux nouvelles normes de sécurité OWASP. Il semblerait donc que ce besoin perdurera puisque l'informatique ne fait qu'évoluer et ces problématiques sont au cœur de l'évolution du domaine.

### Analyse fonctionnelle du besoin

#### Environnement du produit

* Acteurs
   * Élèves: utilisateurs du site
   * Animateurs: fournissent des explications sur le fonctionnement du site
* Contraintes
   * C1: être accessible depuis un réseau local
   * C2: permettre de chiffrer/déchiffrer des messages
   * C3: proposer des outils d'aide au déchiffrement
   * C3.1: analyse fréquentielle des lettres et groupes de lettres
   * C3.2: suggestion automatique de mots en fonction des lettres trouvées
   * C4: être simple à utiliser et à comprendre
   * C5: proposer une automatisation du déchiffrement 
   * C6: proposer une série d'exercices et/ou un tutoriel pour apprendre à utiliser le site
   * C7: respecter les normes de sécurité (OWASP) 

#### Énoncé des fonctions de services

##### Fonction principale
Permettre de chiffrer et déchiffrer des messages de façon simple, avec plusieurs outils permettant d'aider l'utilisateur, tels que les fréquences d’apparitions de chaque lettre pour une l'ange donnée.

##### Fonctionnalités attendues
(à compléter) 



-----------
Notes:

Suggestions auto algo simple à proposer d'ici une semaine ou tout du moins une ébauche.

Idées: regex sur le début des mots + contrainte: ne pas proposer des mots peu utilisés à moins qu'on le précise de plus en plus (trouver comment exprimer ça en algo) -> étudier la fréquence des mots dans des livres

Première version chiffrement déchiffrement simplifiés avec clé
Deuxième version idem + trouver clé à partir d'étude de fréquence
Troisième version ajout boîte à outils et terminal

En parallèle dvp site
À la fin install serveur

