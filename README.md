# 🌳 Arbre de Décision — Projet Data Mining (S4)

Support de cours et présentation sur les **arbres de décision**, réalisés dans le cadre du module *Data Mining* (Semestre 4).

**Auteur :** Mohamed Vadel Cheikhna Sid'mhamed

---

## 📖 Description du projet

Ce dépôt contient une présentation détaillée sur le fonctionnement des **arbres de décision**, un des algorithmes de classification les plus utilisés en fouille de données (*data mining*). Le document explique la construction d'un arbre avec l'algorithme **ID3**, la mesure d'incertitude par l'**entropie**, ainsi que les techniques d'**élagage** (*pruning*) permettant d'éviter le sur-apprentissage.

Le contenu s'appuie sur des exemples concrets, dont le jeu de données classique *« Jouer au tennis »* (Ciel, Température, Humidité, Vent).

---

## 📂 Contenu du dépôt

| Fichier | Description |
|---|---|
| [`Decision Tree.pptx`](./Decision%20Tree.pptx) | Présentation PowerPoint complète (25 slides) |
| [`Decision Tree 1.pdf`](./Decision%20Tree%201.pdf) | Version PDF exportée de la présentation |

---

## 🗂️ Plan de la présentation

### 1. Généralisation de l'arbre de décision
- **A.** Point de départ : toutes les instances à la racine
- **B.** Choix d'un attribut et d'un split (algorithme ID3, gain d'information, indice de Gini)
- **C.** Partitionnement des données selon le split choisi
- **D.** Traitement récursif de chaque nœud fils
- **E.** Condition d'arrêt (nœud terminal / feuille)
- **F.** Étiquetage du nœud terminal (classe majoritaire)
- **G.** Exemple complet : jeu de données *« Jouer au tennis »* et arbre obtenu

### 2. Élagage de l'arbre (*pruning*)
- **A.** Pourquoi élaguer : éviter le sur-apprentissage (*overfitting*)
- **B.** Qu'est-ce que le sur-apprentissage ? (exemples pédagogiques : l'élève qui apprend par cœur, la reconnaissance de formes, la régression bruitée)
- **C.** Comment réduire le sur-apprentissage : suppression des branches peu utiles
- **D.** Effets de l'élagage sur la précision et la généralisation

### 3. Méthodes d'élagage
- **A. Pré-élagage** (*pre-pruning*) : hauteur maximale, nombre minimum d'exemples par nœud, gain d'information minimum
- **B. Post-élagage** (*post-pruning*) : construction complète de l'arbre puis simplification via un jeu de validation

### 4. Mesure d'incertitude — Entropie
- **A.** Incertitude de l'ensemble (entropie globale entre classes P et N)
- **B.** Incertitude des sous-ensembles et calcul du gain d'information par attribut

---

## 🧠 Notions clés abordées

| Notion | Description |
|---|---|
| **ID3** | Algorithme de construction d'arbre basé sur le gain d'information |
| **Entropie** | Mesure de l'incertitude/désordre d'un ensemble de données |
| **Gain d'information** | Critère de choix de l'attribut de split à chaque nœud |
| **Nœud terminal / feuille** | Nœud auquel une classe est assignée (classe majoritaire ou pure) |
| **Sur-apprentissage (overfitting)** | Modèle trop collé aux données d'entraînement, mauvaise généralisation |
| **Élagage (pruning)** | Simplification de l'arbre pour améliorer la généralisation |
| **Pré-élagage / Post-élagage** | Deux stratégies pour limiter la complexité de l'arbre |

---

## 👀 Consulter le projet

- Ouvrir directement [`Decision Tree.pptx`](./Decision%20Tree.pptx) avec PowerPoint, LibreOffice Impress ou Google Slides.
- Ou consulter la version [`Decision Tree 1.pdf`](./Decision%20Tree%201.pdf) avec n'importe quel lecteur PDF.

---

## 🎓 Contexte académique

Projet réalisé dans le cadre du module **Data Mining — Semestre 4 (S4)**.
