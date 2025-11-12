# breast-cancer-predictor
Breast Cancer Diagnosis Predictor
Overview

The Breast Cancer Diagnosis Predictor is a machine learning-based application developed to support medical professionals in identifying whether a breast tumor is benign or malignant. By analyzing specific cellular measurements, the model predicts the nature of the tumor and presents the results visually using a radar chart. Users can either manually enter the measurements or, in an extended setup, connect the system to a cytology laboratory machine for automatic data input (note: this connection feature is external and not included in the app itself).

This project was created as an educational exercise in machine learning using the publicly available Breast Cancer Wisconsin (Diagnostic) Dataset
. As the dataset and model were developed for academic learning, the app should not be used for medical or clinical diagnosis.

A live, interactive version of the app is hosted on Streamlit Community Cloud:
https://alejandro-ao-streamlit-cancer-predict-appmain-uitjy1.streamlit.app/

Installation

To ensure a smooth setup and proper dependency management, it is recommended to use a virtual environment. You can easily create one using Conda:

conda create -n breast-cancer-diagnosis python=3.10


Activate the environment:

conda activate breast-cancer-diagnosis


Next, install all required dependencies from the provided requirements.txt file:

pip install -r requirements.txt


This will automatically install the necessary libraries, including Streamlit, OpenCV, and scikit-image.

Usage

Once all dependencies are installed, you can launch the app with the following command:

streamlit run app/main.py


The app will open in your default web browser. From there, you can upload an image of breast cells, fine-tune analysis settings, and view the prediction results. The application also allows exporting the computed measurements to a CSV file for further study or analysis.
