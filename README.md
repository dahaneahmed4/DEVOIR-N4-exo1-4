# 🎓 Correction Interactive : Optimisation avec Contraintes d'Égalité (Série N°3)

Ce dépôt contient une solution interactive et détaillée des exercices 1 et 4 de la **Série N°3** du module d'**Optimisation** (M1 AII - USTHB).

L'outil est conçu comme un cahier de notes (notebook) académique, combinant la théorie mathématique, les calculs détaillés en français, et les instructions pour la résolution symbolique sous **MATLAB**.

## 🚀 Utilisation du Fichier HTML

Le cœur de cette solution est le fichier unique `Correction_Optimisation.html`.

1.  **Téléchargement :** Téléchargez ou copiez le contenu du fichier `Correction_Optimisation.html`.
2.  **Exécution :** Ouvrez simplement le fichier `Correction_Optimisation.html` avec n'importe quel navigateur web moderne (Chrome, Firefox, Edge, etc.).
3.  **Navigation :** Utilisez les onglets en haut de la page pour basculer entre la correction de l'Exercice 1 et celle de l'Exercice 4.

**Note :** Le fichier utilise la bibliothèque **MathJax** (via CDN) pour afficher correctement les formules mathématiques en LaTeX. Une connexion internet est nécessaire pour charger ces formules et la coloration syntaxique MATLAB.

## 📝 Méthodologie et Contenu

Tous les calculs sont basés sur la **Méthode des Multiplicateurs de Lagrange** (Lagrangien) vue dans le **Chapitre III** du cours.

| Exercice | Objectif | Méthode Clé | MATLAB utilisé |
| :--- | :--- | :--- | :--- |
| **Exercice 1** | Min \(f(x) = (x_1-2)^2 + x_2^2 + x_3^2\) S.T. \(x_1^2 + 2x_2^2 + 3x_3^2 = 2\). | Lagrangien et Matrice Hessienne (SONC) pour déterminer la nature (Min/Max). | `syms`, `jacobian`, `solve`, `hessian`, `eig`. |
| **Exercice 4** | Max Volume \(V = XYZ\) S.T. Contraintes de surface et \(X=2Y\). | Lagrangien appliqué à la minimisation de \(-V\) après substitution pour réduire les variables. | `syms`, `jacobian`, `solve` avec hypothèses de positivité (`assume`). |

## ✨ Fonctionnalités Incluses

* **Formules Mathématiques :** Utilisation de LaTeX (via MathJax) pour une présentation claire des Lagrangiens, des gradients et des matrices.
* **Calculs Détaillés :** Étapes de résolution des systèmes d'équations (FONC) expliquées en français.
* **Instructions MATLAB :** Scripts prêts à l'emploi (Symbolic Math Toolbox) pour vérifier les résultats, notamment l'analyse des valeurs propres de la Hessienne.
* **Résultats Finaux :** Mise en évidence des points critiques, des multiplicateurs de Lagrange et des dimensions optimales.
* **Visualisation (Placeholders) :** Sections dédiées pour l'insertion future de graphiques (ex: l'ellipsoïde de l'Ex 1 ou le schéma de la boîte de l'Ex 4) pour une meilleure compréhension géométrique.

---

*Bonne optimisation !*
