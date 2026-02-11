# Thermal Image Segmentation for Fire Localization
This project focuses on detecting and localizing fire regions in thermal images using deep learning–based image segmentation. The goal is to enable early fire detection in low-visibility environments such as nighttime, smoke-filled areas, forests, and industrial sites.

## Project Overview
Traditional fire detection systems based on RGB cameras can fail in poor lighting or smoky conditions. Thermal cameras capture heat patterns, making them more reliable for such scenarios.
Instead of only predicting whether fire exists in an image, this project performs pixel-level segmentation to precisely locate fire regions. The output can be used for monitoring fire spread, triggering alerts, and supporting IoT-based safety systems.

## Objectives
- Segment fire regions from thermal images.
- Localize fire with pixel-level accuracy.
- Reduce false alarms caused by hot non-fire objects.
- Explore RGB-to-thermal fusion for improving detection.
- Design the system for show future IoT deployment.

## Technologies Used
- Python
- OpenCV
- NumPy
- TensorFlow / PyTorch
- U-Net Architecture
- Matplotlib / Seaborn
- Jupyter Notebook / Google Colab

## Workflow
- Data Collection
- Data Preprocessing
- Resizing
- Normalization
- Noise reduction
- Data augmentation
- Mask Preparation
- Model Training using U-Net
-  Model Evaluation
- Fire Localization Output
- Future IoT Integration Planning

## Model Architecture
The project uses a U-Net-based segmentation network consisting of:
- Encoder: Extracts features and heat patterns.
- Decoder: Restores spatial resolution for localization.
- Skip Connections: Preserve fine-grained details and boundaries.

## Evaluation Metrics
- Intersection over Union (IoU)
- Dice Coefficient
- Precision & Recall

## Results
The trained model successfully segments fire regions in thermal images and highlights the exact fire boundaries. It performs well in most controlled scenarios, though challenges remain with highly reflective hot objects and limited training data.

## Future Work

- Deploy model on IoT edge devices.
- Real-time video processing.
- Multi-class segmentation (fire, smoke, hot surfaces).
- Model compression and optimization.
- Cloud dashboard for alerts and monitoring.
- Support for drone-based thermal cameras.
