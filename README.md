# Neural Network Model Combination for Video-Based Blood Pressure Estimation


```Python3 | TensorFlow | LSTM | CNNs```

## Required Packages

```
numpy == 1.21.6
cv2 == 4.6.0
PIL == 7.1.2
onnxruntime == 1.13.1
```

To load,
```pip3 install -r requirements.txt```

## 🩺 Overview

This repository contains the **codebase** used for experiments in our research article on: **Neural Network Model Combination for Video-Based Blood Pressure Estimation: New Approach and Evaluation** 

Our study introduces a novel method for estimating **systolic and diastolic blood pressure** from the **RGB color intensity variations** in facial skin regions. These variations correspond to blood flow patterns and are captured using an ordinary camera. Using **hybrid deep learning models**, our goal is to enable accessible, non-invasive blood pressure monitoring using only video input—eliminating the need for traditional, cumbersome, or expensive equipment.

> ⚠️ **Note:** The dataset used in this research is **confidential** and cannot be shared. This repository includes the **full code** for data preprocessing, model training/testing, and evaluation, but **no actual data** is provided.


## 🧠 Key Features

- End-to-end pipeline for **video-based blood pressure estimation**
- Hybrid deep learning models combining **CNN** and **LSTM** components

## 📁 Repository Structure

blood-pressure-estimation/
│
├── models/ # Deep learning models
├── Train.ipynb # Script for training models
├── Test.ipynb # Script for evaluating trained models
├── Automatic prediction - models.ipynb #Script to test your video to check BP values. It shows the preprrocessing steps and framework used to obtain ROIs.
├── Automatic prediction - combintations.ipynb #The same function of the previous repository with using combinations of the trained models to get better accuracy. (Check the article)
├── requirements.txt # Required Python packages
└── README.md # Project documentation

##🤝 Contributing
If you find a bug or have a suggestion for improvement, feel free to open an issue or submit a pull request. Contributions are always welcome.

##📜 Citation
If you found our work interesting, please cite it as:
```
@Article{s23041753,
AUTHOR = {Hamoud, Batol and Kashevnik, Alexey and Othman, Walaa and Shilov, Nikolay},
TITLE = {Neural Network Model Combination for Video-Based Blood Pressure Estimation: New Approach and Evaluation},
JOURNAL = {Sensors},
VOLUME = {23},
YEAR = {2023},
NUMBER = {4},
ARTICLE-NUMBER = {1753},
URL = {https://www.mdpi.com/1424-8220/23/4/1753},
PubMedID = {36850349},
ISSN = {1424-8220},
DOI = {10.3390/s23041753}
}
```

