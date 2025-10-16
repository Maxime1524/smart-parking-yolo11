# 🚗 Smart Parking Lot Vehicle Detection with YOLO11

## 📝 Description
Système de détection intelligente de véhicules dans les parkings utilisant YOLO11 et le dataset PKLot.

## 🎯 Objectifs
- Détecter les véhicules (voitures, motos, bus, camions)
- Compter les places occupées vs libres
- Comparer YOLO11, YOLOv8 et Faster-RCNN

## 📊 Dataset
- **Principal** : PKLot (images de parkings)
- **Pré-entraînement** : COCO (weights initiaux)

## 🏷️ Classes COCO utilisées
- 2: car
- 3: motorcycle
- 5: bus
- 7: truck
- 12: parking meter (optionnel)

## 📂 Structure du projet
```
smart-parking-yolo11/
├── notebooks/          # Notebooks Colab
├── data/              # Datasets et configs
├── src/               # Scripts Python
├── experiments/       # Modèles entraînés
└── results/           # Résultats et visualisations
```

## 🚀 Quick Start
Voir le notebook `notebooks/01_setup_and_training.ipynb`

## 📈 Résultats
*(À remplir après les expériences)*

## 👤 Auteur
Projet PFE - Ing3 2025-26 Maxime Massonnat Axel Derouet
