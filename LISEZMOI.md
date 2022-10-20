[ES](./LEERME.md)

# La Isla Disruptiva

Le monde d'aujourd'hui change sous l'impulsion du numérique.
Ainsi, ceux qui contrôlent le code et le dévelopement logiciel contrôlent l'avenir.

C'est sur ce constat et sur notre volonté de prendre nos responsabilités envers le futur que repose La Isla Disruptiva.

Sur La Isla Disruptiva, entre 2 piña colada, on apprend à coder son futur. 

## Qu'est-ce qu'un développeur disruptif?

Pour nous, le dévelopeur est un super-héro des temps modernes. Quelqu'un capable de résoudre nos problèmes, quelqu'un capable de créer des outils
qui transforment notre vie. Espérons que ces transformations seront bénéfiques pour la société. Le dévelopeur disruptif est du bon côté. 

Le développeur disruptif n'est pas qu'un codeur. Ce n'est pas qu'un exécutant. Il comprend nos problèmes et c'est à partir de ce matériau qu'il crée.

Le code et la technologie sont à la fois essentiels et accessoires. 

## Apprentissage actif et montée en compétence 

Comme tout développeur disruptif, je ne suis pas un informaticien accompli. Peut-être que je ne sais pas coder et que j'évite le plus souvent possible d'utiliser un ordinateur.

Cependant, je souhaite prendre part à la création de la technologie. Car c'est ma responsabilité, comme la vôtre et comme toute personne libre.

La Isla Disruptiva est un espace sécuritaire pour apprendre, partager et se perfectionner.

# Katas sur la plage

Inspiré des [katas de programmation](https://es.wikipedia.org/wiki/Kata_(programaci%C3%B3n)), La Isla disruptiva propose ce type d'exercice. Voici notre méthode.

Les repos de La Isla Disruptiva commençant par **kata-\*** sont des katas à faire sur la plage, idéalement entre amis, autour d'un feux, avec une guitare et, accessoirement, en prenant un verre de piña colada.

### Des requis à la solution optimale

Toute bonne solution part d'un problème, même si celui-ci est souvent inconnu, imperceptible ou inavoué. Ces pourquoi, les katas sur la plage ont comme point de départ la définition d'un problème.

La pertinence de ce problème, son importance ou sa radicalité n'ont aucune importance. Nous disruptrons le monde peut-être, mais pour l'instant nous sommes sur la plage et nous commencerons pas de petits problèmes. N'empêche que la description de notre problème permet de nous mettre dans la peau de l'utilisateur et de ressentir son besoin, sa douleur, son problème... qui est à la source de toute solution disruptive.

### Le déroulement

#### Définissez un problème et écrire les requis utilisateurs

  - N'importe qui peut soumettre un problème à la communauté de La Isla Disruptiva. Pour ce faire, vous devez:
    - Créez un repo git contenant la desciption du problème et les requis utilisateur dans la branche **main**.
    - Le premier commit doit être vide.
    - Proposez à La Isla Disruptiva d'en faire un fork.

#### Proposez une solution en écrire la spécification

  - Créer un fork et une branche **kata/AUTEUR/DESCRIPTION**
  - Décrire la solution proposer sous forme de spécification

#### Implémentez la solution

  - Réaliser le kata en utilisant la méthodologie red-green-refactor

#### Présentez votre oeuvre

  - Nettoyer votre code
  - Ajouter une présentation (écrit ou oral)

#### Échangez, partagez et co-construisez notre compétence

  - Soumettre un pull request de votre branche


### Convention de commits

L'objectif des katas est d'apprendre ensemble. Pour ce faire, nous portons une attention particulière à la méthode et à la communication.
Grâce à nos conventions de commit simples, chaque kata devient un matériel pédagogique précieux.

Chaque message de commit a une des 2 formes suivante:

```
[TYPE] DESCRIPTION
```
ou 
```
DESCRIPTION
```

  - Il y a 5 types de commits:
    - [spec]: Décrit le problème ou de la solution (requis, spécification, design, architecture, etc.).
    - [red]: Déclare la prochaine fonctionalité qui sera développée (comprend un test qui échoue).
    - [green]: Atteint un état stable d'implémentation d'une fonctionalité (permet à un test de réussir).
    - [refactor]: Modifie une qualité du code sans effet sur les fonctionalitées.
    - [doc]: Ajoute de la documentation (explication, démonstration, réflexion, commentaire, etc. )

  - Entre un commit [red] et [green], il peut y avoir des messages de commits sans [TYPE]. 
  - La description permet de comprendre la "fonctionalité" et non pas seulement le détail d'implémentation.
  - Un développeur peut lire uniquement l'historique et reproduire une implémentation semblable.

### Autres technicalités

  - Les PR seront effectués dans une branche du même nom que la vôtre.
  - Seuls les branche modifiant uniquement la définition du problème et nommées **spec/DESCRIPTION** pourront être merger dans main.
  - Si vous le souhaitez, vous pouvez changer la licence que votre oeuvre. Sinon, celle-ci sera mise dans le domaine public (CC0-1.0).
  - Les Pull Request qui ne respectent pas notre convention de commits seront refusés.
  - Votre branche ne doit pas contenir de trace de votre environnement de travail ou de fichiers binaires ou dérivées.