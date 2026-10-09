# Traitement-d-images-Couleurs

# Démosaïquage d’images couleur par optimisation et variation totale

## Présentation du projet

Les capteurs d’images numériques utilisent généralement un filtre de Bayer, qui associe à chaque pixel une seule composante de couleur parmi le rouge, le vert et le bleu (RGB). Le démosaïquage consiste à reconstruire une image couleur complète à partir de ces observations partielles.

Ce problème de reconstruction est un problème inverse mal posé, rendu plus difficile par la présence éventuelle de bruit dans les données acquises.

## Objectifs

L’objectif de ce projet est de reconstruire une image couleur à partir de mesures issues d’un filtre de Bayer, en formulant le problème comme une tâche d’optimisation régularisée.

La méthode repose sur :

* La modélisation du filtre de Bayer comme un opérateur linéaire.
* La formulation d’une fonctionnelle combinant un terme d’attache aux données et un terme de régularisation.
* L’utilisation de la variation totale (*Total Variation*) pour limiter les variations indésirables tout en préservant les contours.
* Le calcul du gradient de la fonctionnelle et l’implémentation d’un algorithme de descente de gradient.
* L’étude de la convergence de la méthode et de l’influence des paramètres sur la qualité de reconstruction.

## Images test

Deux images sont utilisées pour évaluer la méthode :

* **Image de fruits :** permet d’étudier la reconstruction des couleurs et l’équilibre entre les différentes composantes RGB.
* **Image d’un verre d’eau :** permet d’analyser la préservation des détails fins et des variations locales de couleur.

## Compétences mobilisées

* Mathématiques appliquées et problèmes inverses.
* Optimisation numérique et descente de gradient.
* Régularisation par variation totale.
* Traitement d’images numériques et reconstruction couleur.
* Analyse de la convergence et évaluation des résultats.

## Résultats

Cette section présentera les images reconstruites, les comparaisons avec les images originales et l’analyse de l’influence des paramètres de régularisation.

## Technologies

À compléter selon l’implémentation réelle du projet : Python, MATLAB, NumPy, Matplotlib, etc.
