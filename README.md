**Plant Disease Prediction**
This project aims to detect and classify plant diseases from images using a machine learning model trained with TensorFlow and a web interface built with Streamlit.

**Table of Contents**
Overview
Features
Installation
Usage
Model Training
Results
Contributing

**Overview**
Plant diseases can cause significant damage to crops, leading to reduced agricultural productivity and economic losses. This project uses image classification techniques to predict whether a plant is diseased and, if so, identify the specific disease. The model is trained on a dataset containing images of healthy and diseased plants and can be tested using a user-friendly web application.

**Features**
Image Upload: Upload an image of a plant leaf.
Image Preview: Preview the uploaded image.
Disease Prediction: Detect if the plant is diseased or healthy.
Disease Classification: Identify the specific disease affecting the plant.

**Installation**
To run this project locally, follow these steps:
  1.Clone the repository:
    git clone https://github.com/your-username/plant-disease-prediction.git
    cd plant-disease-prediction
  2.Create a virtual environment and activate it:
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
  3.Install the required dependencies:
    pip install -r requirements.txt
  4.Run the Streamlit app:
    streamlit run app.py
  5.Usage
    Open the Streamlit app in your web browser (usually at http://localhost:8501).
    
Upload an image of a plant leaf.
Preview the uploaded image.
Click the Predict button to get the prediction results.
  If the plant is diseased, the app will display the name of the disease.
  If the plant is healthy, it will indicate that no disease is detected.
  
**Model Training**
The model was trained using TensorFlow on a dataset containing images of various plant diseases and healthy plants. The training process involves:

Preprocessing the images (resizing, normalization).
Splitting the data into training and validation sets.
Defining a convolutional neural network (CNN) architecture.
Training the model and evaluating its performance.

**Results**
The model has been tested and shows promising results in accurately identifying plant diseases. Detailed evaluation metrics and visualizations can be found in the notebooks directory.

**Contributing**
Contributions are welcome! If you have suggestions for improvements or new features, please create an issue or submit a pull request.
