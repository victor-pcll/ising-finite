# Modèle d’Ising en dimension finie

## Description
Ce projet présente une étude du **modèle d’Ising** sur des réseaux de taille finie à travers un **notebook Jupyter**. Il permet de visualiser le comportement collectif des spins et d’explorer les propriétés thermodynamiques d’un système magnétique en fonction de la température.

Le projet inclut :  
- La simulation d’un réseau de spins en **2D**.  
- L’implémentation de l’**algorithme de Monte Carlo (Metropolis-Hastings)** pour faire évoluer le système.  
- Des visualisations illustrant la **magnétisation**, l’**énergie** et la **transition de phase**.  
- Une approche pédagogique pour comprendre l’effet de la **taille finie** sur les transitions de phase.

---

## Structure du projet

ising-finite/
│
├─ notebook/                   # Contient le notebook Jupyter
│   └─ Ising_Model.ipynb
│
├─ images/                     # Illustrations générées
│   └─ spin_configurations.png
│
└─ README.md

---

## Installation
1. Cloner le dépôt :  
```bash
git clone https://github.com/ton-utilisateur/ising-finite.git
cd ising-finite
python -m venv venv
source venv/bin/activate  # macOS / Linux
venv\Scripts\activate     # Windows
pip install numpy matplotlib scipy
```

---

## Objectif pédagogique

Ce projet vise à :
	•	Comprendre le modèle d’Ising et ses concepts clés en physique statistique.
	•	Visualiser l’effet des fluctuations thermiques sur un réseau fini.
	•	Étudier la transition de phase dans un système fini.

---

## Références

**Physique statistique 2** : Transitions de phase, École Polytechnique Fédérale de Lausanne, Prof. Matthieu Wyart, Rédigé par Jonas Paccolat
