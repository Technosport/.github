# Technosport amU 🏃‍♂️🔬

> **Plateforme technologique de recherche, d'innovation et d'évaluation au service de la performance sportive, de la santé et du mouvement humain.**  
> *Institut des Sciences du Mouvement (ISM UMR 7287 CNRS) — Aix-Marseille Université / *

---

### 🌐 À propos du Technosport

Le **Technosport amU** est une plateforme technologique universitaire de pointe dédiée à l'analyse pluridisciplinaire du mouvement humain. Nous concevons et développons des solutions logicielles, des chaînes de traitement et des applications sur-mesure pour la recherche scientifique et la valorisation.

---

### 📦 Projets & Écosystème Logiciel

#### 🔹 [`tks-package`](https://github.com/Technosport/TKS-package)
[![PyPI version](https://img.shields.io/pypi/v/tks-package.svg)](https://pypi.org/project/tks-package/)
[![Python versions](https://img.shields.io/pypi/pyversions/tks-package.svg)](https://pypi.org/project/tks-package/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

La boîte à outils Python de référence du laboratoire pour l'importation, le traitement du signal et l'analyse des données biomécaniques.

```bash
pip install tks-package
```

* **Lecture multi-formats :** Fichiers C3D (`ezc3d`), exportations Visual3D (`.txt`), acquisitions EMG Delsys Trigno (`.xml`, `.h5`), semelles pressurisées Moticon, signaux FIT Garmin...
* **Traitement & Analyse :** Filtrage de signaux, détection d'événements cinématiques (impacts, décollages), calculs articulaires et cinétiques.
* **Visualisation :** Thèmes graphiques prêts pour la publication et l'exploration interactive (`matplotlib`, `plotly`).

---

#### 🔹 [`App-Pseudonymisation`](https://github.com/Technosport/App-Pseudonymisation)
Application portable et chiffrée (Windows & macOS) utilisable sur clé USB pour enregistrer et pseudonymiser les données des participants lors des campagnes expérimentales, dans le strict respect de la conformité RGPD et des comités d'éthique.

---

#### 🔹 Outils d'expérimentation & Biofeedback
* **`Speed-Feedback-MicrogateCells`** : Contrôle d'acquisition et retour visuel/sonore en temps réel couplé aux cellules photoélectriques Microgate.
* **`Visual3D-Pipelines`** : Référentiel de scripts de calcul cinématique et cinétique automatisés pour Visual3D.
* **`golf-studio`** : Dashboard Streamlit d'analyse cinématique et dynamique 3D du geste sportif.

---

### ⚙️ Technologies & Équipements

Nos pipelines s'interfacent avec les technologies de pointe de la plateforme :
* **Capture du mouvement 3D :** Systèmes optoélectroniques Qualisys & Vicon, Visual3D
* **Électromyographie (EMG) & Capteurs inertiels (IMU) :** Delsys Trigno Wireless
* **Dynamométrie :** Plateformes de force Kistler et AMTI
* **Pression plantaire :** Semelles de pression Moticon OpenGo
* **Chronométrie :** Cellules et systèmes de timing Microgate

---

### 📍 Localisation & Contact

* **Lieu :** Technosport amU — Faculté des Sciences du Sport  
  163 Avenue de Luminy, 13009 Marseille, France
* **Affiliation :** Aix-Marseille Université & Institut des Sciences du Mouvement (ISM UMR 7287 CNRS)
* **GitHub :** [github.com/Technosport](https://github.com/Technosport)
* **Package PyPI :** [pypi.org/project/tks-package](https://pypi.org/project/tks-package/)
