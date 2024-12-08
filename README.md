# Recréation d'un SweetAlert

## Description
Ce projet consiste à recréer une version simplifiée de la bibliothèque d'alertes personnalisées SweetAlert, en utilisant uniquement les API du DOM et du CSS, sans Node.js ni framework externe. L'objectif est de développer un mini-package JavaScript autonome capable de gérer différents types d'alertes avec une approche modulaire et réutilisable.

## Objectifs du projet
Le projet a pour but de créer un package JavaScript qui implémente les fonctionnalités suivantes :

1. **Sweet Info** : Affichage de messages d'information.
2. **Sweet Success** : Affichage de confirmations réussies.
3. **Sweet Warning** : Affichage de messages d'avertissement.
4. **Sweet Danger** : Affichage d'erreurs critiques.

Le package doit être autonome et réutilisable, ce qui implique une structure modulaire permettant d'ajouter facilement de nouveaux types d'alertes si nécessaire.

## Fonctionnalités
- Affichage dynamique des alertes avec des styles spécifiques pour chaque type d'alerte.
- Fermeture des alertes après un certain délai ou par interaction de l'utilisateur.
- Possibilité de personnaliser les alertes via les paramètres d'entrée.

## Technologies utilisées
- JavaScript (API DOM)
- CSS (pour la mise en forme des alertes)
- Git et GitHub (pour la gestion de version)

## Structure du projet
- **`sweetalert.js`** : Fichier JavaScript contenant les fonctionnalités des alertes.
- **`style.css`** : Fichier CSS pour le style des alertes.

## Installation
1. Clonez ce repository sur votre machine locale.
    ```bash
    git clone https://github.com/achraf622-cpu/sweetalert-recreation.git
    ```
2. Ouvrez les fichiers dans votre éditeur de texte préféré.

## Branches et Gestion de Version
Le projet suit une gestion de version avec Git et GitHub, respectant les bonnes pratiques de développement :
- Chaque type d'alerte a été développé dans une branche distincte.
- Les commits sont clairs et descriptifs.
- La branche `master` contient la version finale après la fusion des branches.

## Exemple d'utilisation
Pour utiliser les alertes, incluez simplement le fichier JavaScript dans votre projet et appelez les fonctions correspondantes :

```html
<script src="sweetalert.js"></script>
<script>
  SweetInfo('Voici un message d\'information');
  SweetSuccess('Opération réussie !');
  SweetWarning('Attention, ceci est un avertissement');
  SweetDanger('Une erreur critique est survenue');
</script>
