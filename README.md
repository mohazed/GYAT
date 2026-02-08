# 🧠 Graph Attention Networks: The Duel (GATv1 vs GATv2)

> **Projet Final - Graph Machine Learning (2026)** > **Comparaison d'implémentation "From Scratch"**

Ce dépôt contient l'implémentation et l'analyse comparative de deux architectures majeures de GNN :
1.  **GATv1** (Veličković et al., 2017) : Attention Statique.
2.  **GATv2** (Brody et al., 2021) : Attention Dynamique.

L'objectif est de démontrer les limitations théoriques de la v1 et la supériorité expressive de la v2 via des datasets standards (Cora) et synthétiques.

---

## 👥 L'Équipe (Groupe X)

| Membre | Rôle Principal | GitHub |
| :--- | :--- | :--- |
| **Zouzou** | 🏗️ Architecte Modèle (Layers & Attention) | @Zouzou |
| **Mazou** | ⚙️ Ingénieur Data & Training Loop | @Mazou |
| **Amine** | 📊 Analyste, Visualisation & Benchmarking | @Amine |

---

## 📅 Tableau de Bord & Avancement

**Comment utiliser ce tableau ?** Modifiez le fichier `README.md` et remplacez `[ ]` par `[x]` pour valider une étape.  
*Exemple : `[x]` Tâche terminée.*

### 🟢 Semaine 1 : Setup & Théorie (Initialisation)
*Objectif : Environnement prêt et données chargées.*

| Tâche | Zouzou | Mazou | Amine |
| :--- | :---: | :---: | :---: |
| Lecture approfondie du papier GATv1 (2017) | [ ] | [ ] | [ ] |
| Lecture approfondie du papier GATv2 (2021) | [ ] | [ ] | [ ] |
| Initialisation Git & Structure du projet | [ ] | [ ] | [ ] |
| Script de chargement du dataset **Cora** (sans PyG si possible) | [ ] | [ ] | [ ] |
| Prétraitement des features (Normalisation, Adjacence) | [ ] | [ ] | [ ] |

### 🟡 Semaine 2 : Le Cœur du Moteur (GATv1)
*Objectif : Avoir une boucle d'entraînement qui fonctionne sur la version basique.*

| Tâche | Zouzou | Mazou | Amine |
| :--- | :--- | :---: | :---: |
| Implémentation classe `GATLayer` (Squelette) | [ ] | [ ] | [ ] |
| Codage du mécanisme **Attention Statique** (v1) | [ ] | [ ] | [ ] |
| Codage de la boucle `train()` (Loss, Optimizer) | [ ] | [ ] | [ ] |
| Test unitaire : Le modèle apprend-il sur Cora ? | [ ] | [ ] | [ ] |

### 🟠 Semaine 3 : Le "Game Changer" (GATv2 & Synthétique)
*Objectif : Implémenter la correction et le piège.*

| Tâche | Zouzou | Mazou | Amine |
| :--- | :--- | :---: | :---: |
| Implémentation du switch **Attention Dynamique** (v2) | [ ] | [ ] | [ ] |
| Génération du **Dataset Synthétique** (Dictionary Problem) | [ ] | [ ] | [ ] |
| Vérification : v1 échoue-t-elle sur le synthétique ? | [ ] | [ ] | [ ] |
| Gestion du Multi-Head Attention (Concaténation) | [ ] | [ ] | [ ] |

### 🔴 Semaine 4 : Benchmarking & Visualisation
*Objectif : Produire les preuves pour le rapport.*

| Tâche | Zouzou | Mazou | Amine |
| :--- | :--- | :---: | :---: |
| Lancement des entraînements finaux (Cora/Citeseer) | [ ] | [ ] | [ ] |
| Création des courbes de Loss/Accuracy | [ ] | [ ] | [ ] |
| Extraction des poids d'attention ($\alpha_{ij}$) | [ ] | [ ] | [ ] |
| Génération des Heatmaps (Comparaison v1 vs v2) | [ ] | [ ] | [ ] |

### 🔵 Semaine 5 : Nettoyage & Rendu
*Objectif : Rendre le projet "sexy" et lisible.*

| Tâche | Zouzou | Mazou | Amine |
| :--- | :--- | :---: | :---: |
| Refactoring du code (Noms de variables, Docstrings) | [ ] | [ ] | [ ] |
| Rédaction du Jupyter Notebook Pédagogique | [ ] | [ ] | [ ] |
| Vérification finale des critères d'évaluation | [ ] | [ ] | [ ] |
| Création du ZIP final pour envoi | [ ] | [ ] | [ ] |

---

## 🛠️ Installation & Utilisation

```bash
# Cloner le repo
git clone [https://github.com/votre-repo/gat-project.git](https://github.com/votre-repo/gat-project.git)
cd gat-project

# Installer les dépendances
pip install -r requirements.txt
