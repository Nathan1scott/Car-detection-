Car Detection with YOLOv8
This project uses the YOLOv8 object detection model to build a robust car detection system. The model is trained to identify and localize various traffic-related objects, including cars, traffic lights, and speed limit signs, from a custom dataset. This type of system is invaluable for applications like autonomous driving and real-time traffic monitoring.
Features
 * Object detection using the state-of-the-art YOLOv8 model.
 * Trained to recognize specific objects: cars, traffic lights, and speed limit signs.
 * Provides bounding boxes, class names, and confidence scores for each detected object.
 * Supports inference on new images or video streams.
Getting Started
This project is structured as a Jupyter Notebook, which you can run in a local environment or on a platform like Google Colab.
Prerequisites
 * Python 3.x
 * Jupyter Notebook or JupyterLab
Installation
The notebook handles the installation of all necessary libraries. The key dependencies are:
 * Ultralytics: The library that contains the YOLOv8 model.
 * Kaggle: Used for downloading the dataset from the Kaggle platform.
 * Roboflow: The platform where the dataset is hosted and managed.
Dataset
The model is trained on a custom dataset sourced from Roboflow. This dataset includes a collection of images annotated with the specific objects of interest (cars, traffic lights, and speed limit signs). The notebook code connects to Roboflow to download this dataset automatically before training the model.
Usage
 * Clone the repository to your local machine.
 * Open the Car detection.ipynb file using Jupyter Notebook or a similar environment.
 * Follow the steps in the notebook. You will need to provide your Kaggle API key to download the dataset.
 * The notebook will guide you through the process of setting up the environment, training the model, and running inference on test images to see the detection results.
Model and Inference
The notebook uses a pre-trained YOLOv8 model and fine-tunes it on the custom dataset. After training, you can run inference on test images. The output includes:
 * A visual representation of the image with bounding boxes drawn around the detected objects.
 * A printout of the detected objects, their confidence scores, and the coordinates of their bounding boxes.

