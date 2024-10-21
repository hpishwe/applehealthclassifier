




# Apple Classifier: Detecting Apple Health Using CNNs

## Overview
This project aims to classify the health of apples using Convolutional Neural Networks (CNNs). The classifier detects whether an apple is *Healthy* or affected by scab disease (*Unhealthy*). The model is trained on images of apples at various ripeness stages, focusing on color, spots, and edges to assess their health.

The Jupyter notebook in this repository walks through the entire process, from data preprocessing to model training, evaluation, and visualization of results.

## Features
- **Apple Health Classification:** Apples are classified as *Healthy* or *Unhealthy* (affected by scab).
- **Edge and Spot Detection:** Using OpenCV, the model detects and plots edges and spots for further analysis.
- **Live Image Capture:** The notebook includes functionality to capture an image from the laptop camera and classify it after a 15-second timer.

## Dataset
The dataset used for training and testing the model is split into two categories:
- **Healthy Apples:** Images of apples free from scab or visible disease.
- **Unhealthy Apples:** Images showing apples affected by scab disease.

You can modify the notebook to use your own dataset by updating the file paths.

## How to Use the Notebook
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/hpishwe/applehealthclassifier.git
   cd applehealthclassifier
   ```
2. **Open the Jupyter Notebook:**
   Make sure you have Jupyter installed. Then, run the following command to start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. **Install Required Libraries:**
   Before running the notebook, install the necessary libraries:
   ```bash
   pip install tensorflow keras opencv-python matplotlib numpy
   ```
4. **Run the Notebook:**
   Open the notebook (`applehealthclassifier.ipynb`) and follow the steps to train and test the model.

## Future Improvements
- **Tree-Specific Detection:** Extend the classifier to detect specific apple trees in orchards.
- **QR Code Integration:** Implement QR codes for individual apple plants to track health and growth.
- **Real-Time Monitoring:** Build a real-time classification and alert system for orchards.



