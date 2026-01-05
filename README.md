# 💣 JavaFX Bomberman

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-21.0.1-4285F4?style=for-the-badge&logo=java&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-Build-02303A?style=for-the-badge&logo=gradle&logoColor=white)

Une réimplémentation du célèbre jeu d'arcade **Bomberman** développée en **Java** avec le framework **JavaFX**. Ce projet a été réalisé dans le cadre du BUT Informatique (IUT de Lens / Université d'Artois).

## 🎮 Fonctionnalités

Ce jeu reprend les mécaniques classiques de Bomberman avec une architecture logicielle robuste :

* **Déplacement fluide** du personnage sur une grille.
* **Système de Bombes** : Posez des bombes pour détruire les obstacles et les ennemis.
* **Inventaire de Bombes** : Possibilité de sélectionner différents types de bombes via un menu dédié.
* **Gestion des Vies (Pv)** : Système de points de vie avec affichage visuel (cœurs).
* **Ennemis** : IA basique gérant les déplacements des ennemis.
* **Conditions de Victoire/Défaite** : Gestion des états "Game Over" et "Victoire" avec possibilité de relancer la partie.
* **Interface Graphique (GUI)** : Utilisation de FXML pour la structure et CSS pour le style.

## 🕹️ Contrôles

Le jeu se joue au clavier :

| Touche | Action |
| :---: | :--- |
| **↑** | Déplacement Haut |
| **↓** | Déplacement Bas |
| **←** | Déplacement Gauche |
| **→** | Déplacement Droite |
| **ESPACE** | Poser une bombe |
| **I** | Ouvrir l'inventaire (Sélectionner une bombe) |

## 🛠️ Stack Technique & Architecture

Le projet suit une architecture **MVC (Modèle-Vue-Contrôleur)** stricte, renforcée par l'utilisation d'une **Façade** pour simplifier les interactions entre le contrôleur et le modèle métier.

* **Langage** : Java 21
* **Framework UI** : JavaFX 21 (Modules: Controls, FXML)
* **Build Tool** : Gradle
* **Patrons de conception** : MVC, Façade, Factory (pour les cellules de liste), Observer (Bindings JavaFX).

## 🚀 Installation et Lancement

### Prérequis
* JDK 21 installé.
* Gradle (optionnel, le wrapper `gradlew` est inclus).

### Instructions

1.  **Cloner le dépôt** :
    ```bash
    git clone [https://github.com/TonPseudo/JavaFX-Jeux-Bomberman.git](https://github.com/TonPseudo/JavaFX-Jeux-Bomberman.git)
    cd JavaFX-Jeux-Bomberman
    ```

2.  **Lancer le jeu via Gradle** :
    Sous Windows :
    ```bash
    .\gradlew run
    ```
    Sous Mac/Linux :
    ```bash
    ./gradlew run
    ```

L'application se lancera via la classe principale `fr.univartois.butinfo.ihm.BombermanApplication`.

## 👤 Auteur

**Loïck DAVI** - *Développeur*

---
*Projet réalisé dans un cadre pédagogique à l'Université d'Artois.*
