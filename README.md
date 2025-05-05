# VPO-Project
# 🚇 Projet IG.2405 — Reconnaissance des lignes de métro parisien (ISEP 2025)

Ce projet consiste à détecter et reconnaître automatiquement les pictogrammes des lignes de métro parisien dans des images extraites de flux vidéo. Il est réalisé pour le client fictif **IMAGIK** dans le cadre d'un assistant à la mobilité pour malvoyants.

---

## 🧠 Objectifs
- Détecter les zones contenant des pictogrammes de lignes de métro
- Classifier les pictogrammes selon leur numéro de ligne (1, 2, ..., 14)
- Fournir un programme exécutable sur un répertoire complet d'images

---

## 📁 Structure du projet

```
metro-vision-project/
├── data/                  # Dossiers d’images et fichiers .xlsx (non versionnés)
├── results/               # Fichiers de sortie (.xlsx, images prédites, modèles)
├── scripts/               # Scripts utilitaires (téléchargement des données, etc.)
├── src/                   # Code source principal
│   ├── metro.py           # Fonction principale demandée
│   ├── metro_test.py      # Lancement sur dossier complet
│   ├── detection.py       # Détection des zones candidates
│   ├── recognition.py     # Reconnaissance/classification des pictogrammes
│   └── utils.py           # Fonctions utilitaires (chargement images, affichage)
├── .devcontainer/         # Config automatique pour GitHub Codespaces
├── .github/workflows/     # Intégration continue (GitHub Actions)
├── requirements.txt       # Bibliothèques Python
├── .gitignore             # Fichiers à ignorer (données, caches...)
├── package.json           # Scripts exécutables
└── README.md              # Ce fichier !
```

---

## 🧠 Rappel des livrables (exigences IMAGIK)
- `metro.py` : fonction de reconnaissance
- `metro_test.py` : test batch + export Excel
- Rapport technique (formalisé, sans code)
- PowerPoint de soutenance + démo

---

**Contact** : <email de référence> | Projet encadré par ISEP, module IG.2405