# Celebrity Face Dataset

This repository contains a dataset of celebrity face images, structured in two primary categories: **full images** and **localized face crops**. It is designed for use in computer vision tasks such as face detection, recognition, and machine learning model training.

## Dataset Overview

The dataset includes a wide variety of face images featuring celebrities, captured in diverse poses, lighting conditions, and expressions. The dataset is split into the following sections:

1. **Full Images**: High-resolution images featuring the entire celebrity, including full-body shots.
2. **Localized Faces**: Cropped images of the celebrities' faces, making it easier to work with face recognition models.

Each image is accompanied by metadata, including facial bounding box coordinates for localized images.

## Features

- **Variety of Celebrities**: Includes a wide range of celebrities from different domains (e.g., actors, musicians, athletes).
- **Face Localization**: For ease of use, the dataset provides localized face crops for training face detection models.
- **Diverse Conditions**: Images captured in various lighting, facial expressions, and poses to increase robustness in model training.
- **Annotations**: Facial bounding boxes for face crops to aid in supervised learning tasks.

## Usage

You can use this dataset for various machine learning and computer vision tasks, including:

- **Face Detection**: Train models to detect faces in full images.
- **Face Recognition**: Develop models that can recognize and classify celebrity faces.
- **Facial Landmark Detection**: Work on facial landmark detection tasks using localized face crops.
- **Data Augmentation**: Use the diverse conditions in the dataset to improve generalization of machine learning models.
