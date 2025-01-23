# Anomaly Detection in Well Log Data using Ensemble GANs and GMM

This repository contains code and resources for anomaly detection in well log data. The study compares Ensemble Generative Adversarial Networks (EGANs) and Gaussian Mixture Models (GMM) for identifying anomalies in geophysical datasets, particularly focusing on analyzing well log data from the North Sea Dutch region.

---

## Overview

This project explores and demonstrates the efficacy of **EGANs** for detecting anomalies in well log data. The dataset includes **Gamma Ray (GR)**, **Bulk Density (RHOB)**, **Sonic Travel Time (DT)**, and **Neutron Porosity (NPHI)** measurements. EGANs are compared with **GMM**, a traditional method, for their ability to detect outliers and anomalies across these datasets.

### Key Features:
- **EGANs for Anomaly Detection:** Enhanced anomaly detection using ensemble models to capture complex data distributions.
- **GMM:** A traditional Gaussian Mixture Model for anomaly detection.
- **Visualization:** Resulting plots and visualizations showing how anomalies are detected in well log data.

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
pip install numpy pandas scikit-learn matplotlib


### Running the Code

1. Clone the repository:

   ```bash
   git clone https://github.com/ARhaman/EGANs-and-GMM-for-Anomaly-Detection-in-Well-Logs.git
   cd EGANs-and-GMM-for-Anomaly-Detection-in-Well-Logs


## Prepare the dataset:

Place the original well log data in the Dataset/Original dataset folder.
Run the code:

The Jupyter notebooks in the GMM and GAN CODES folder will guide you through the preprocessing steps and model training.
You can also run Python scripts for model evaluation and anomaly detection.
Check Results:
Visualizations of the anomaly detection results are stored in the Figures/ folder.
The results include contour plots for each of the well logs.
##  Results
The following figures are generated during the analysis:

Gamma Ray (GR) Contour Plots: Visualizations for both training and testing data, highlighting anomalies detected by the models.
DT, RHOB, and NPHI Plots: Similar visualizations for other well logs show how well the models detect anomalies.
Example plot:

## References

1. [Waylong O. "GANS for Anomaly Detection"](https://github.com/waylongo/Gans-for-anomaly-detection).
2. Goodfellow, Ian, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, and Yoshua Bengio. "Generative adversarial nets." In *Advances in neural information processing systems*, pp. 2672-2680. 2014.
3. Brock, Andrew, Jeff Donahue, and Karen Simonyan. "Large scale GAN training for high fidelity natural image synthesis." *arXiv preprint arXiv:1809.11096* (2018).
4. Reynolds, D. "Gaussian Mixture Models". *Encyclopedia of Biometrics*, pp.827-832, 2015.
5. Bishop, C. *Pattern Recognition and Machine Learning (Information Science and Statistics)*. Springer-Verlag New York, Inc., Secaucus, NJ, USA, 2006.
6. Stauffer, C., and Grimson, W. "Adaptive background mixture models for real-time tracking". *Proceedings. 1999 IEEE Computer Society Conference on Computer Vision and Pattern Recognition* (Cat. No PR00149).
7. Krishnapuram, R., and Keller, J. M. "A possibilistic approach to clustering", *IEEE Transactions on Fuzzy Systems*, vol. 1, no. 2, pp. 98-110, 1993.
8. Al-Fakih, A., Koeshidayatullah, A., Mukerji, T., & Kaka, S. I. (2024). "Enhanced anomaly detection in well log data through the application of ensemble GANs," *Journal of Geophysical Research*.



## How to Cite
If you use this code or data, please cite the following paper:

https://doi.org/10.48550/arXiv.2411.19875

Al-Fakih, A., Koeshidayatullah, A., Mukerji, T., & Kaka, S. I. (2024). "Enhanced anomaly detection in well log data through the application of ensemble GANs," Journal of Geophysical Research.
License
This project is licensed under the Apache License 2.0.

## Acknowledgments
Tapan Mukerji, A., Koeshidayatullah, and SanLinn I. Kaka for their support and guidance throughout this project.
The Python community and contributors to the libraries used in this project.

## Contact
If you have any questions, feel free to contact me at:
Email: alja2014ser@gmail.com
