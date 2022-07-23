# Cartes du club robot

Toutes les cartes ici sont les cartes en développement au club. Vous pouvez retrouver
dans les release les cartes correspondant à chaque robot.

Dans le dossier `manufactured` vous pouvez retrouver toutes les cartes qui ont été fabriquées. Elles sont
identifiées par un code unique que vous pouvez retrouver sur le PCB.

## Procédure de fabrication

Lorsque vous envoyez une carte à fabriquer, il faut:
- Ajouter un identifiant à la carte (de la forme `[A-Z]{3}`)
- Copier le projet dans le dossier `manufactured`
- Renommer le projet en `[identifiant] {nom}`

Cela permet d'avoir une trace exacte de toutes les cartes fabriquées. Une carte dans le dossier `manufactured` n'est pas
forcément définitive, mais cela permet d'identifier les cartes dans le local.

## Procédure post-coupe

Lorsque la coupe est finie il faut produire une release contenant toutes les cartes utilisées, c'est pratique pour comprendre
comment fonctionnait le robot.

## Cartes

### Alimentation

Carte principale d'alimentation du robot, adapte la tension batterie pour alimenter les différets composants.

### Base roulante

Carte pour la gestion de la base roulante du robot
