# Mouth-Detection
Created a Mouth Detection system to detect Mouth is Open or Close using Machine Learning in Python

## Overview
This project focuses on the development of a system capable of detecting whether a mouth is opened or closed using deep learning techniques. The model is trained on a dataset of images containing examples of both open and closed mouths.

## Dataset
The dataset used for training and testing the mouth detection model is available on the Kaggle respectively. It consists of images of both open and closed mouths.
Dataset link: https://www.kaggle.com/datasets/davidvazquezcic/yawn-dataset

## Model Architecture
The convolutional neural network (CNN) architecture used for mouth detection is defined in the `model_mouth_detection` function in the provided Python script. The model is trained to perform binary classification (open or closed) based on the input images.

## Getting Started
To get started with this project, follow these steps:
1. Clone the repository:
   git clone (https://github.com/RoshaniSahane/Mouth-Detection)
2. Navigate to the Project Directory:
   cd Mouth-Detection
3. Install Dependencies:
   pip install -r requirements.txt
4. Run the Project:
   Execute the main script or application. Since it seems to be a Python project, you might run it with:
   GUI.ipynb
5. Browse the Image of Open or Close Mouth, It will detect the mouth is open or close.
  
## Results
The project includes visualizations of training and validation accuracy over epochs, providing insights into the model's performance.

## Model Saving
The trained model can be saved in JSON format along with the weights. The saved model files are named mouth_model.json and mouth_model_weights.h5.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, feel free to contact the project maintainer:
Your Name: Roshani Sahane
Your Email: sahaneroshani25@gmail.com
