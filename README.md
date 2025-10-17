🚢 Airbus Ship Detection: Image Segmentation with UNET


Overview

This project notebook, "Airbus Ship Detection", focuses on solving an image segmentation problem using satellite imagery. The primary goal is to accurately detect and segment ship pixels within the images.

The notebook provides a complete workflow, from understanding the dataset and core computer vision concepts to building and training a deep learning model for semantic segmentation.

Project Goal
The specific objective is Semantic Segmentation, which involves classifying every pixel in an input image as either belonging to a ship (foreground) or the ocean (background).

Dataset
The project utilizes data from the Kaggle Airbus Ship Detection Challenge.

Key dataset files:

train_v2 and test_v2: Folders containing the satellite images.

train_ship_segmentation.csv: A CSV file containing Run-Length Encoded (RLE) masks for the labeled images.

A dedicated section in the notebook details the process of Run Length Encoding (RLE) and Decoding, which is essential for translating the pixel mask information from the CSV into usable image masks for model training.

Methodology and Model
The core of the solution is a Convolutional Neural Network (CNN) architecture known as UNET.

The notebook's workflow includes:

Data Exploration and Preprocessing.

A brief introduction to the UNET architecture.

Building and training the UNET model.

Data preparation for the model, including the implementation of data generators (using fit_generator).

Saving the trained model weights to a file (e.g., seg_model.h5).

Prerequisites and Setup
This notebook requires the following Python libraries:

os

numpy

pandas

matplotlib.pyplot

seaborn

scikit-image (skimage.io.imread, skimage.segmentation.mark_boundaries, skimage.util.montage, skimage.morphology.label)

gc (garbage collection)

Ensure these dependencies are installed in your environment before running the notebook.

Notebook Workflow
The notebook is structured with anchored sections for easy navigation:

Introducing Dataset

Quick guide on Object Detection, Image Classification, and Segmentation

Importing necessary libraries and modules

Exploring the Dataset

Grasping the idea of Run Length Encoding and Decoding

Preparing data for our model

Brief introduction to the UNET model

Build and train UNET model

Tasks for you
