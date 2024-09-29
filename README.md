# HelloToast

## Description

L'application **HelloToast** vise à illustrer des concepts de base du développement Android en Java. Elle utilise à la fois un **LinearLayout** et un **ConstraintLayout** pour organiser l'interface utilisateur et gérer les interactions de manière flexible et responsive. 

## Fonctionnalités Principales

- **Affichage d’un Toast** : 
  - L’interface comprend un bouton qui, lorsqu'il est pressé, affiche un message Toast à l’écran. Ce Toast est une notification courte qui informe temporairement l’utilisateur d’une action effectuée.

- **Affichage d’une boîte de dialogue d’alerte (AlertDialog)** : 
  - L’application inclut un AlertDialog qui s’affiche lorsqu’un deuxième bouton est pressé, demandant à l’utilisateur de confirmer une action avec les options "Cancel" ou "Continue".

- **Incrémentation du Compteur** : 
  - Un troisième bouton est dédié à l’incrémentation d’un compteur. Chaque fois que l’utilisateur appuie sur ce bouton, la valeur du compteur augmente et est mise à jour dans un champ de texte (TextView).

## Utilisation de ConstraintLayout

Le **ConstraintLayout** est utilisé dans cette application pour :

- **Créer des interfaces utilisateurs complexes** : Contrairement aux layouts traditionnels, le ConstraintLayout permet de créer des interfaces plus flexibles et dynamiques sans avoir besoin d'imbrication de plusieurs vues.
- **Définir des contraintes** : Les éléments de l'interface peuvent être positionnés en fonction des autres éléments, ce qui permet de concevoir des mises en page qui s'ajustent automatiquement à différentes tailles d'écran et orientations.
- **Optimiser la performance** : L'utilisation de ConstraintLayout réduit le nombre de niveaux d'imbrication, ce qui améliore les performances de rendu de l'interface.

## Objectif

L'objectif de ce projet est de savoir comment utiliser à la fois **ConstraintLayout** et **LinearLayout**, et de se familiariser avec **Android Studio**.

## Prérequis

- Android Studio
- Java Development Kit (JDK)

## Installation

1. Cloner ce dépôt :
   ```bash
   git clone <URL_DU_REPO>
