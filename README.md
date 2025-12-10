# andromeda-ai

<img src="https://img.shields.io/badge/Project-Andromeda%20IA-6A5ACD?style=for-the-badge&logo=starship&logoColor=white" /><img src="https://img.shields.io/badge/Astronomy-AI%20%2F%20Deep%20Learning-blue?style=for-the-badge&logo=nasa" />
<img src="https://img.shields.io/badge/Status-Active%20Development-orange?style=for-the-badge" /><img src="https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python" /> <img src="https://img.shields.io/badge/TensorFlow-Keras-FF6F00?style=flat-square&logo=tensorflow" /><img src="https://img.shields.io/badge/PyTorch-Ready-EE4C2C?style=flat-square&logo=pytorch" /><img src="https://img.shieds.io/badge/Kaggle-Datasets-20B2AA?style=flat-square&logo=kaggle" />
<img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter" /> <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />

# 📡 Astronomy Datasets Used in *Projeto Andromeda IA*
AI &amp; Deep Learning experiments applied to astronomy data (images and time series).   The goal of this project is to build and evaluate models that can help classify celestial objects, detect anomalies.
This project aggregates multiple public astronomy datasets from Kaggle to support experiments in image classification, star-type prediction, exoplanet exploration, pulsar detection, and large-scale sky surveys.
Below is the full list of datasets used, grouped by scientific domain.

## 🌌 1. Galaxy & Space Imagery Datasets

### **Dummy Astronomy Data (Cutouts + Tables)**

**Link:** [https://www.kaggle.com/datasets/divyansh22/dummy-astronomy-data](https://www.kaggle.com/datasets/divyansh22/dummy-astronomy-data)
A synthetic but astrophysically realistic dataset containing image cutouts and tabular metadata for experiments in galaxy detection, morphology studies, and introductory ML tasks in astronomy.

## ⭐ 2. Star Classification Datasets

### **Star Type Classification**

**Link:** [https://www.kaggle.com/datasets/brsdincer/star-type-classification](https://www.kaggle.com/datasets/brsdincer/star-type-classification)
Dataset containing physical parameters of stars (temperature, luminosity, radius, star color, spectral class) used for supervised learning to classify stellar types.

## 🪐 3. Exoplanet Discovery & Catalogs

### **Open Exoplanet Catalogue**

**Link:** [https://www.kaggle.com/datasets/mrisdal/open-exoplanet-catalogue](https://www.kaggle.com/datasets/mrisdal/open-exoplanet-catalogue)
Open database of discovered exoplanets containing features such as orbital period, mass, radius, eccentricity, host star parameters, and discovery methods.

### **NASA Kepler Exoplanet Search Results**

**Link:** [https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results)
Data collected from NASA’s Kepler Space Telescope mission. Includes thousands of stellar light curves and labeled candidates for training ML models to detect exoplanets via transit method.

## 🌘 4. Solar System & Events

### **NASA Solar Eclipses Dataset**

**Link:** [https://www.kaggle.com/datasets/nasa/solar-eclipses](https://www.kaggle.com/datasets/nasa/solar-eclipses)
A dataset covering global records of solar eclipses across centuries, including type (total, partial, annular), magnitude, coordinates, and timing.

## 🔭 5. Pulsars & Deep Space Phenomena

### **Predicting a Pulsar Star**

**Link:** [https://www.kaggle.com/datasets/colearninglounge/predicting-pulsar-starintermediate](https://www.kaggle.com/datasets/colearninglounge/predicting-pulsar-starintermediate)
Dataset used to distinguish real pulsars from false positives using statistics extracted from deep space radio signals.

## 🌌 6. Astronomical Surveys & Sky Mapping

### **Sloan Digital Sky Survey (SDSS)**

**Link:** [https://www.kaggle.com/datasets/lucidlenn/sloan-digital-sky-survey](https://www.kaggle.com/datasets/lucidlenn/sloan-digital-sky-survey)
Collection of objects from SDSS with photometric and spectroscopic information. Supports research in galaxy classification, redshift estimation, and large-scale universe structure.

### **SpaceNet – Optimally Distributed Astronomy Data**

**Link:** [https://www.kaggle.com/datasets/razaimam45/spacenet-an-optimally-distributed-astronomy-data](https://www.kaggle.com/datasets/razaimam45/spacenet-an-optimally-distributed-astronomy-data)
Dataset providing a variety of astronomical measurements optimized for machine-learning tasks, often used for clustering and anomaly detection.

# 📂 How These Datasets Are Used in This Project

| Dataset Category    | Applications in *Projeto Andromeda IA*                      |
| ------------------- | ----------------------------------------------------------- |
| Galaxy images       | CNNs, morphology classification, anomaly detection          |
| Star classification | Supervised ML, stellar evolution modeling                   |
| Exoplanets          | Light-curve analysis, transit detection, time-series models |
| Eclipses            | Temporal forecasting, orbital event analysis                |
| Pulsars             | Binary classification, astrophysical signal detection       |
| SDSS survey         | Feature engineering, semi-supervised and clustering tasks   |
| SpaceNet            | Large-scale data experiments, feature distribution analysis |

# 📁 Folder Placement in the Repository

Place each dataset inside:

```
data/
│── raw/
│     ├── dummy_astronomy/
│     ├── star_types/
│     ├── open_exoplanet_catalogue/
│     ├── kepler_exoplanets/
│     ├── solar_eclipses/
│     ├── pulsar_star/
│     ├── sdss/
│     └── spacenet/
```
