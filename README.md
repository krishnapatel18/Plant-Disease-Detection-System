# Plant Disease Detection System

This repository contains the code and resources for a plant disease detection system using deep learning and Streamlit.

## Overview

This project utilizes a Convolutional Neural Network (CNN) model to identify plant diseases from leaf images. The model is trained on the dataset and deployed as a web application using Streamlit for easy accessibility.

## Features

* **Accurate Disease Detection:** Utilizes a CNN model fine-tuned for plant disease classification.
* **Web-Based Interface:** Deployed as a Streamlit application for user-friendly interaction.
* **Image Upload:** Allows users to upload plant leaf images for disease diagnosis.
* **Real-Time Prediction:** Provides immediate disease prediction results.

## Technologies Used

* **Python:** Programming language.
* **TensorFlow/Keras:** Deep learning framework.
* **OpenCV:** Image processing library.
* **NumPy:** Numerical computing library.
* **Streamlit:** Web application framework.
* **Dataset:** Image dataset for training model taken from Kaggle.

## Screenshots

![Screenshot (3628)](https://github.com/user-attachments/assets/07329665-3029-4036-b270-c1988e9c10c8)

![Screenshot (3627)](https://github.com/user-attachments/assets/b327beff-a8c2-40f2-8235-51029e714576)

![image](https://github.com/user-attachments/assets/263608db-5f43-4fe1-9d82-903ba30a2e39)

### Prerequisites

* Python 3.10.11
* TensorFlow/Keras
* OpenCV
* Streamlit
* NumPy

### Installation

1.  Clone the repository:

    ```bash
      git clone [https://github.com/krishnapatel18/Plant-Disease-Detection-CNN.git](https://github.com/krishnapatel18/Plant-Disease-Detection-CNN.git)
    cd Plant-Disease-Detection-CNN
    ```

2.  Create a virtual environment (recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    venv\Scripts\activate  # On Windows
    ```

3.  Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4.  Download the dataset and place it in the appropriate directory (or update the path in the code).

5.  Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

6.  Open the provided URL in your browser.

### Usage

1.  Upload a plant leaf image using the file uploader.
2.  The model will predict the disease and display the results.

### License

MIT License
