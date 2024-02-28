# Hybrid Foundation Model for Change Detection in Remote Sensing Data

## Project Overview
Introduces a novel approach for change detection in remote sensing imagery, leveraging a UNET-like Siamese Segmentation Network to analyze Google Earth images using the LEVIR-CD dataset. Our model focuses on accuracy, computational feasibility, and versatility for various applications.

## Features
- **Innovative Architecture**: Combines Siamese networks with CNNs and UNET segmentation.
- **High Precision**: Identifies subtle geographical changes accurately.
- **Versatility**: Suitable for urban planning, environmental monitoring, and disaster management.
- **Dataset**: Uses the high-resolution LEVIR-CD dataset for detailed change detection.

## How It Works
The model processes pairs of pre-change and post-change images through a Siamese architecture, extracting and decoding features to generate a detailed change map.

## Effect of Regularization
Adding regularization to the segmentation architecture made it capture even the slightest of changes whereas the model with no regularization only captured changes in bigger structures.

## Results
The model showcases high performance with precise change detection capabilities, evaluated on metrics like precision, recall, F1 score, and IoU.

## Contact
For inquiries, please contact Dheeraj NVS at vnaganaboina@ufl.edu.

*Note: For detailed methodology, experimental setups, and in-depth analysis, refer to the full project report.*
