# Thermal Image Analysis for Heat Transfer

## 1. Project Overview

Thermal management plays an important role in maintaining the performance, reliability, and operational safety of computer servers. Excessive heat accumulation can lead to hardware degradation, reduced efficiency, and unexpected system failures.

This project focuses on analysing thermal images of a Dell PowerEdge R720 server to identify abnormal heat patterns, localize potential hotspots, and assess their severity using image processing, deep learning, and machine learning techniques.

The project combines a ResNet18-based convolutional autoencoder, anomaly detection, hotspot localization, severity assessment, and visual explainability into an integrated thermal analysis system.

## 2. Project Objectives

- Analyse thermal images to identify abnormal heat patterns.
- Learn meaningful image features using a ResNet18-based convolutional autoencoder.
- Detect anomalous thermal regions using Elliptic Envelope.
- Localize potential hotspots using image-processing techniques.
- Estimate hotspot severity using extracted features.
- Interpret model behaviour using EigenCAM.
- Explore machine-learning-based thermal risk assessment.
- Develop a user-friendly web application for thermal image analysis and visualization.

## 3. Proposed Methodology

The project investigates the following techniques:

1. Thermal image preprocessing
2. ResNet18-based convolutional autoencoder
3. Self-supervised feature learning
4. Elliptic Envelope anomaly detection
5. Hotspot detection and localization
6. Thermal hotspot severity assessment
7. EigenCAM-based visual interpretation
8. Machine-learning-based thermal risk prediction

## 4. Web Application

An interactive web application is developed to make the thermal analysis system accessible through a user-friendly interface.

The application is designed to allow users to:

- Upload thermal images for analysis.
- Process images through the developed thermal analysis pipeline.
- Visualize detected anomalous regions and potential hotspots.
- Examine hotspot-related measurements and severity information.
- View model interpretation outputs using EigenCAM.
- Generate downloadable PDF reports containing analysis results.

The web application aims to present the analysis results in an understandable format without requiring users to interact directly with the underlying Python code.

*The final feature list should reflect the functions available in the completed application.*

## 5. Dataset

The project uses thermal images associated with a Dell PowerEdge R720 server, representing different operating conditions.

Dataset details, original source information, and access instructions are documented separately.

**Note:** The original dataset will not be redistributed through this repository unless its licence explicitly permits it.

## 6. Technologies Used

- Python
- PyTorch
- ResNet18
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Streamlit
- Machine Learning
- Deep Learning
- Computer Vision

## 7. Expected Outcomes

- Identification of potential thermal hotspots.
- Localization and visualization of anomalous regions.
- Quantitative assessment of hotspot severity.
- Visual interpretation of model predictions.
- An interactive web application for thermal image analysis.
- A framework to support server thermal monitoring and predictive maintenance research.

## 8. Project Limitations

This project is an academic prototype. Its outputs are intended for research and educational purposes and should not be considered a replacement for calibrated thermal measurements or professional server inspection.

## 9. Author

**Anamika Sujith**

MSc Data Science  
Vellore Institute of Technology  
Chennai, India
