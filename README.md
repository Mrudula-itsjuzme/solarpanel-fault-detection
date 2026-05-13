# Solar Panel Fault Detection

A computer-vision project for detecting and classifying faults in solar-panel images using convolutional neural networks.

The goal is to support faster inspection of solar installations by identifying visual fault patterns such as cracks, dust accumulation, shading, or damaged regions.

---

## Project links and evidence

| Item | Link / Note |
|---|---|
| Repository | https://github.com/Mrudula-itsjuzme/solarpanel-fault-detection |
| Paper / reference | No paper attached yet; project is an applied computer-vision prototype |
| Demo video | Not uploaded yet |
| Deployment | Not applicable yet; training/inference workflow is local |
| Dataset note | Solar-panel image dataset should be configured locally; dataset provenance and class labels need to be documented in a future update |
| Result screenshots / plots | Add confusion matrix, sample predictions, and training curves under `docs/`, `experiments/`, or `notebooks/` when finalized |

---

## Problem statement

Solar panels lose efficiency when faults go unnoticed. Manual inspection is slow, inconsistent, and difficult to scale across large solar farms.

This project explores image-based fault detection as a step toward automated solar-panel maintenance and energy-output protection.

---

## What this project includes

- image preprocessing for solar-panel fault data
- categorical encoding for fault labels
- CNN-based model training
- experimental model scripts
- documentation and training notes
- future direction for edge or drone-based deployment

---

## Pipeline

```text
Solar Panel Images
        ↓
Preprocessing + Label Encoding
        ↓
CNN Training
        ↓
Fault Classification
        ↓
Evaluation Metrics
```

---

## Key files

| File | Purpose |
|---|---|
| `BasicCNN.py` | main CNN architecture, training loop, and evaluation flow |
| `Hot-coding.py` | preprocessing and categorical label encoding utilities |
| `src/` | source code for model refinement and feature work |
| `experiments/` | experiment logs and training reports |
| `notebooks/` | exploratory analysis and preprocessing prototypes |
| `docs/` | methodology and evaluation documentation |
| `scripts/` | automation utilities for cleaning and augmentation |

---

## Quick start

```bash
git clone https://github.com/Mrudula-itsjuzme/solarpanel-fault-detection.git
cd solarpanel-fault-detection

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

Install the deep-learning stack used by your local setup, then run preprocessing and training:

```bash
python Hot-coding.py
python BasicCNN.py
```

---

## Tech stack

- Python
- CNNs
- TensorFlow/Keras or PyTorch workflow
- Image preprocessing
- Classification metrics
- Solar-energy fault analysis

---

## Why this project matters

Fault detection in renewable-energy infrastructure is a real operational problem. Automating visual inspection can reduce downtime, improve maintenance planning, and help protect energy output at scale.

---

## Future improvements

- add a clean `requirements.txt`
- include sample predictions and confusion matrix images
- add dataset provenance and preprocessing assumptions
- train deeper CNN/transfer-learning baselines
- optimize for edge devices or drone-assisted inspection

---

## Author

Built by [Pedamallu Sai Mrudula](https://github.com/Mrudula-itsjuzme) as part of an applied AI, computer-vision, and renewable-energy analytics portfolio.
