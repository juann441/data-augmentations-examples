# Visualisation des Data Augmentations

Ce notebook permet de **visualiser en temps réel les effets de différentes data augmentations** sur des images médicales, avant l'entraînement d'un modèle de détection (ex : YOLOv8).

---

## 🎯 Objectif

- Comprendre l'impact de chaque transformation : rotation, flip, luminosité, contraste, teinte, saturation, blur, CLAHE, crop…
- Aider à choisir les paramètres adaptés pour l'imagerie médicale.

---

## 🖼 Exemple visuel

Voici un exemple généré par le notebook sur la même image originale :

![](exemple_augmentations.png)

> Chaque subplot indique la transformation appliquée et ses paramètres.

---

## 🛠 Instructions

1. Installer les dépendances :
```bash
pip install albumentations matplotlib opencv-python ipywidgets
