## Project Overview

This project focuses on Personal Protective Equipment (PPE) detection using deep learning.  
The implementation is divided into two main parts: **model training** and **depth detection (inference and tracking)**.

### 1. Model Training

The training module is responsible for building and optimizing a YOLOv8 and YOLOE-based detection model on a custom PPE dataset.  
It includes dataset configuration, model training, and checkpoint saving. The trained model learns to recognize PPE-related objects and people under real-world industrial scenarios.

### 2. Depth Detection

The deep detection module uses the trained model for practical deployment tasks, including image inference, video-based detection, and person tracking with consistent IDs.  
This part focuses on applying the trained model to unseen data for PPE compliance monitoring and safety analysis.
