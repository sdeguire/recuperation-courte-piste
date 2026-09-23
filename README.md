# Récupération Courte Piste

Outil de décision sur la récupération, destiné aux athlètes et au personnel
d'encadrement en patinage de vitesse courte piste.

**Site : https://sdeguire.github.io/recuperation-courte-piste/**

## Ce que fait l'outil

L'athlète indique trois choses : sa phase de saison, la séance qui vient de
finir, et le délai avant le prochain effort. Il coche aussi l'équipement dont il
dispose. L'outil retourne l'éventail des stratégies pertinentes, classées soit
par priorité, soit chronologiquement dans la journée.

Chaque stratégie porte quatre indicateurs :

- **Type de gain** : fondation, optimisation ou confort
- **Bénéfice attendu** : de 0 à 5
- **Risque de freiner l'adaptation** : calculé selon la séance et la phase
- **Niveau de preuve** : solide, correcte ou limitée

Un second onglet présente le volet éducatif en langage clair, les erreurs
fréquentes, les limites de la littérature et les références.

## Base scientifique

58 revues systématiques, méta-analyses et essais contrôlés publiés
principalement entre 2015 et 2026. Les références complètes sont dans l'onglet
Comprendre.

Deux points méthodologiques appliqués partout :

1. Une stratégie n'atteint la priorité que si son bénéfice est d'au moins 3 sur
   5, que son niveau de preuve est solide ou correct, et qu'aucun résultat
   contradictoire n'existe entre les méta-analyses.
2. Le risque de freiner les adaptations n'est pas une propriété fixe. Il est
   recalculé selon le type de séance et la phase de saison.

## Limites

Aucune étude ne porte sur la courte piste. Tout est transposé du sport
collectif, de la course et du cyclisme. Les participants sont majoritairement
des hommes. Le parasport n'est pas couvert et les repères de température ne s'y
transposent pas. La nutrition est traitée séparément.

## Installation sur téléphone

Ouvrir le site, puis Partager et Ajouter à l'écran d'accueil. L'outil s'ouvre
alors en plein écran avec son icône.

## Technique

Page HTML autonome, sans dépendance ni outil de compilation. La logique de
décision et les données sont dans le script en fin de fichier. Les choix sont
mémorisés localement dans le navigateur.
