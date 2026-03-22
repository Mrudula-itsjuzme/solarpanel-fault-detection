# Solar Panel Fault Detection

This project applies machine learning techniques to identify and classify faults in solar panel systems using image analysis.

## Overview

Leveraging Convolutional Neural Networks (CNNs), the system detects anomalies such as cracking, shading, and dust accumulation on solar panels to ensure optimal energy production and system longevity.

## Implementation Details

- **BasicCNN.py**: Implementation of a baseline Convolutional Neural Network for initial fault classification.
- **Hot-coding.py**: Utility for data preprocessing and label encoding.
- **Applied ML**: Focuses on real-world application of computer vision in renewable energy maintenance.

## Project Structure

- **src/**: Source code for model training and evaluation.
- **experiments/**: Detailed logs and results of different training iterations.
- **docs/**: Documentation on model architecture and evaluation metrics.
- **scripts/**: Automation for data augmentation and preprocessing.

## Getting Started

1. Ensure Python and necessary ML frameworks (e.g., TensorFlow or PyTorch) are installed.
2. Run `Hot-coding.py` to prepare the dataset.
3. Execute `BasicCNN.py` to start the training or evaluation process.

## Future Work

- Integration with real-time drone-based surveillance imagery.
- Development of a lightweight model for edge-device deployment.
- Expansion of the fault category list for higher-granularity detection.
