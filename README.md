# Solar Panel Fault Detection

This project applies Convolutional Neural Networks (CNN) to detect and classify faults in solar panel installations using image datasets.

## Overview

The research focuses on the real-world application of machine learning for identifying common issues such as cracking, dust accumulation, and shading that affect the efficiency and longevity of solar panels. By automating the detection process, this system helps in proactive maintenance and energy output optimization.

## Core Implementation

The repository contains primary scripts for the development of the fault detection model:
- **BasicCNN.py**: Contains the primary model architecture, training loops, and evaluation metrics using deep learning frameworks.
- **Hot-coding.py**: Provides data preprocessing utilities, including categorical encoding for labeling different fault types.

## Project Structure

- **src/**: Source code for model refinement and advanced feature engineering.
- **experiments/**: Detailed reports and logs from various model training iterations.
- **notebooks/**: Exploratory data analysis (EDA) and experimental prototyping for image preprocessing.
- **docs/**: Comprehensive documentation covering methodology, architectural decisions, and evaluation results.
- **scripts/**: Automation scripts for dataset cleaning and augmentation.

## Usage Instructions

1. **Environment Setup**: Ensure Python 3.8+ and necessary deep learning libraries (TensorFlow/Keras or PyTorch) are installed.
2. **Data Preprocessing**: Execute `Hot-coding.py` to prepare labels and imagery for the training pipeline.
3. **Model Training**: Run `BasicCNN.py` to train the classification model on your dataset and generate performance metrics.

## Future Enhancements

- **Real-time Monitoring**: Integration with drone-based thermal imaging for larger solar farms.
- **Multi-class refinements**: Enhanced granularity for identifying subtle fault variations.
- **Edge Deployment**: Optimization of the CNN model for execution on low-power IoT devices.
