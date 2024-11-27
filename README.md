# Anomaly Detection in Well Log Data using Ensemble GANs and GMM

This repository contains code and resources used for anomaly detection in well log data. The study compares Ensemble Generative Adversarial Networks (EGANs) and Gaussian Mixture Models (GMM) for identifying anomalies in geophysical datasets, particularly focusing on analyzing well log data from the North Sea Dutch region.

---

## Overview

This project explores and demonstrates the efficacy of **EGANs** for detecting anomalies in well log data. The dataset includes **Gamma Ray (GR)**, **Bulk Density (RHOB)**, **Sonic Travel Time (DT)**, and **Neutron Porosity (NPHI)** measurements. EGANs are compared with **GMM**, a traditional method, for their ability to detect outliers and anomalies across these datasets.

### Key Features:
- **EGANs for Anomaly Detection:** Enhanced anomaly detection using ensemble models to capture complex data distributions.
- **GMM:** A traditional Gaussian Mixture Model for anomaly detection.
- **Visualization:** Resulting plots and visualizations showing how anomalies are detected in well log data.

---

## References

- [Waylong O. "GANS for Anomaly Detection"](https://github.com/waylongo/Gans-for-anomaly-detection).
- Al-Fakih, A., Koeshidayatullah, A., Mukerji, T., & Kaka, S. I. (2024). "Enhanced anomaly detection in well log data through the application of ensemble GANs," *Journal of Geophysical Research*.

---

## Repository Structure
├── Dataset
│   ├── Original dataset/
│   ├── Test/
│   └── Train/
├── Figures/
├── GMM and GAN CODES/
├── GMM Results/
├── GAN Results/
└── README.md


### Dataset Folder:
Contains the well log datasets for training, testing, and original data. The datasets include well log data for multiple wells including F17-04 and F15-A-01.

### GMM and GAN CODES:
Contains Python scripts and Jupyter notebooks for running GMM and EGAN models, preprocessing the data, and performing anomaly detection.

### Figures:
Includes visualizations and plots for model results, such as contour plots and anomaly detection visualizations.

---

## Getting Started

To replicate the results or run the code locally, follow these instructions.

### Prerequisites

Make sure you have Python installed along with the following libraries:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib

You can install them using pip:

### Running the Code

1. Clone the repository:

   ```bash
   git clone https://github.com/ARhaman/EGANs-and-GMM-for-Anomaly-Detection-in-Well-Logs.git
   cd EGANs-and-GMM-for-Anomaly-Detection-in-Well-Logs

   Prepare the dataset:

Place your original well log data in the Dataset/Original dataset folder.
Run the code:

The Jupyter notebooks in the GMM and GAN CODES folder will guide you through the preprocessing steps and model training.
You can also run Python scripts for model evaluation and anomaly detection.
Check Results:
Visualizations of the anomaly detection results are stored in the Figures/ folder.
The results include contour plots for each of the well logs.
Results
The following figures are generated during the analysis:

Gamma Ray (GR) Contour Plots: Visualizations for both training and testing data, highlighting anomalies detected by the models.
DT, RHOB, and NPHI Plots: Similar visualizations for other well logs showing how well the models perform in detecting anomalies.
Example plot:


How to Cite
If you use this code or data, please cite the following paper:

Al-Fakih, A., Koeshidayatullah, A., Mukerji, T., & Kaka, S. I. (2024). "Enhanced anomaly detection in well log data through the application of ensemble GANs," Journal of Geophysical Research.
License
This project is licensed under the Apache License 2.0.

Acknowledgments
Tapan Mukerji and SanLinn I. Kaka for their support and guidance throughout this project.
The Python community and contributors to the libraries used in this project.
Future Directions
In the future, we aim to explore:

Multivariate anomaly detection by incorporating relationships between multiple well log variables.
Real-time anomaly detection integrated into reservoir management systems.
Hyperparameter optimization for improving computational efficiency and model performance.
Contact
If you have any questions, feel free to contact me at:
Email: alja2014ser@gmail.com

### Explanation of Sections:
- **References**: A separate section that provides links to relevant papers or resources.
- **Repository Structure**: Shows how the repository is organized.
- **Getting Started**: Provides installation and usage instructions.
- **Results**: Highlights how the visualizations are structured and gives a sample figure.
- **Future Directions**: Gives a brief outlook on future research areas to explore.

