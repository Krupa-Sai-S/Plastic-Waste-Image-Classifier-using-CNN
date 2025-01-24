# <p align="center">Plastic Waste Classification Using CNN</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
</p>

---

## Project Overview

<p>
  This project involves developing a Convolutional Neural Network (CNN) model to classify images of plastic waste into different categories such as organic and recyclable materials. The model is built using TensorFlow/Keras and trained on a dataset of waste images to predict and classify waste types.
</p>

---

## Dataset

<p>
  The dataset used for this project is sourced from Kaggle. It consists of labeled images of different types of waste materials like organic and recyclable materials.
</p>

- <b>Dataset Link</b>: <a href="https://www.kaggle.com/datasets/techsash/waste-classification-data/data" target="_blank">Waste Classification Data on Kaggle</a>

### Dataset Structure:
<ul>
  <li><b>TRAIN</b>: Contains training images categorized into different types of waste.</li>
  <li><b>TEST</b>: Contains testing images for model evaluation.</li>
</ul>

---

## Technologies Used

<p>
  <ul>
    <li><b>Python</b>: The primary programming language.</li>
    <li><b>TensorFlow/Keras</b>: For building and training the CNN model.</li>
    <li><b>OpenCV</b>: For image processing and visualization.</li>
    <li><b>Matplotlib/Seaborn</b>: For data visualization.</li>
    <li><b>Pandas</b>: For data manipulation.</li>
  </ul>
</p>

---

## Installation

<p>
  1. Clone the repository to your local machine:
</p>
  <pre>
    git clone https://github.com/yourusername/plastic-waste-classification.git
  </pre>

<p>
  2. Install the required dependencies:
</p>
  <pre>
    pip install -r requirements.txt
  </pre>

<p>
  3. Download the dataset from Kaggle and place it in the appropriate folder:
</p>
  <ul>
    <li><a href="https://www.kaggle.com/datasets/techsash/waste-classification-data/data" target="_blank">Waste Classification Data</a></li>
  </ul>

---

## Project Structure

<ul>
  <li><b>`main.py`</b>: Main code to train and test the CNN model.</li>
  <li><b>`model.py`</b>: Defines the architecture of the CNN model.</li>
  <li><b>`utils.py`</b>: Helper functions for data preprocessing and visualization.</li>
  <li><b>`requirements.txt`</b>: Contains the list of dependencies for the project.</li>
  <li><b>`README.md`</b>: This file.</li>
</ul>

---

## How to Run

<p>
  1. After setting up the environment, run the following command to train the model:
</p>
  <pre>
    python main.py
  </pre>

<p>
  2. The training process will start, and the model will be evaluated on the test dataset after training is complete.
</p>

---

## Visualizations

<p>
  The project includes visualizations of the class distribution in the dataset and model performance over time. These visualizations are generated using Matplotlib and Seaborn.
</p>

---

