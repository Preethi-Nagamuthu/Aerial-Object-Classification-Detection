# Aerial-Object-Classification-Detection

# 📌 Project Workflow
1. Understand the Dataset
Inspect dataset folder structure


Check number of images per class


Identify class imbalance


Visualize sample images

2. Data Preprocessing
Normalize pixel values to [0, 1]


Resize images to a fixed size (224×224 for classification)

3. Data Augmentation
Apply transformations: rotation, flipping, zoom, brightness, cropping

4. Model Building (Classification)
Custom CNN: Conv layers, pooling, dropout, batch normalization, dense output layer


Transfer Learning: Load models like ResNet50, MobileNet, EfficientNetB0 and fine-tune

5. Model Training
Train both models


Use EarlyStopping & ModelCheckpoint


Track metrics: Accuracy, Precision, Recall, F1-score

6. Model Evaluation
Evaluate test results with confusion matrix & classification report


Plot accuracy/loss graphs



7. Model Comparison
Compare accuracy, training time, and generalization performance
Save the best performing model for Streamlit deployment

# 📌 Optional: Object Detection with YOLOv8
Steps:
Install YOLOv8.


Prepare dataset (images and YOLOv8-format .txt labels — already done).


Create a data.yaml configuration file for YOLOv8.


Train the YOLOv8 model.


Validate the trained model.


Run inference on test or new images.

# 📌 Streamlit Deployment
Create a simple UI with image upload


Display prediction (Bird / Drone) & confidence score


(Optional) Show YOLOv8 detection results with bounding boxes
