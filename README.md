# Jeu de Memory

Jeu de memory interactif développé en **Vanilla JavaScript**, sans framework ni librairie externe.

🔗 **Voir le projet en ligne :** https://simclement.github.io/js-memory-game/

## 📖 Contexte

Projet réalisé dans le cadre du TD "Conception, Déploiement et Documentation d'un Jeu de Memory" (BUT Informatique 2A — R3.01), IUT Grand Ouest Normandie (Caen).

Ce projet consiste à retrouver les paires d'images identiques parmi 16 cartes disposées aléatoirement sur un plateau de jeu. Les images sont générées dynamiquement via l'API [Picsum Photos](https://picsum.photos/).

## ✨ Fonctionnalités

- **Génération dynamique** des cartes via l'API Picsum Photos
- **Algorithme de Fisher-Yates** pour un mélange aléatoire et équitable des cartes
- **Accessibilité (A11y / ARIA)** : attributs `role="button"` et `tabindex="0"` sur chaque carte
- **Gestion asynchrone** des tours de jeu via `setTimeout` (masquage des cartes non appariées après 800ms)
- **Chronomètre** en temps réel, formaté en `mm:ss`
- **Compteur de coups** (moves)
- **Détection de victoire** avec affichage du score final
- **Réinitialisation** de la partie (nouveau mélange, nouveau chronomètre)

## 🛠️ Langages et technologies utilisés

- **HTML5** — structure sémantique de la page
- **CSS Grid** — mise en page du plateau de jeu (`#game-board`)
- **JavaScript ES6** — logique du jeu, sans dépendance externe

## ✍️ Auteur(s)

- Simon CLEMENT
