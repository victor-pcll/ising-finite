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

```
ising-finite/
├── Ising_Model.ipynb           # Contient le notebook Jupyter
├── assets/                     # Illustrations générées
│   ├── illu_1.png
│   ├── ...
│   └── illu_13.png
├── requirements.txt            # packages
└── README.md
```

---

## Installation
1. Cloner le dépôt :  
```bash
git clone https://github.com/victor-pcll/ising-finite.git
cd ising-finite
python -m venv venv
source venv/bin/activate  # macOS / Linux
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

---

## Références

**Physique statistique ** : Physique statistique (PHYS-338), École Polytechnique Fédérale de Lausanne, Prof. Florent Krzakala
