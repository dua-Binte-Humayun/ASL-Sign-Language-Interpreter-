# ASL Sign Language Interpreter – Model Development

## Overview
This folder contains the **machine learning component** of the ASL Sign Language Interpreter project.  
The focus here is on **data preprocessing, model design, training, and evaluation** for recognizing static American Sign Language (ASL) hand gestures.

The model development is presented in a **single notebook**, consolidating exploratory analysis, experimentation, and final model training.

---

## Objectives
- To build an accurate image-based classifier for ASL alphabets
- To explore preprocessing techniques suitable for hand gesture recognition
- To train and evaluate a deep learning model for sign classification
- To provide a trained model for real-time HCI applications

---

## Contents

### `asl_model.ipynb`
This notebook documents the **full workflow**, including:
- Dataset loading and inspection
- Image preprocessing (resizing, grayscale conversion, normalization)
- Model architecture experimentation and selection
- Training and validation analysis
- Performance evaluation
- Saving the trained model (`asl_model.h5`)

Markdown cells are used to explain design decisions and observations.

---

## Model Description
- Input: Preprocessed grayscale hand gesture images
- Architecture: Convolutional Neural Network (CNN)
- Output: ASL alphabet class prediction
- Optimization: Adam optimizer
- Loss function: Categorical / Sparse Categorical Crossentropy

---

## Research Relevance
This notebook supports research in:
- Intelligent sensing
- Vision-based human-computer interaction
- Assistive technologies for accessibility

It is later integrated into the interactive module for **real-time ASL interpretation**.

---

## Notes
Although originally developed as a single notebook, this workflow demonstrates:
- clear data preprocessing  
- thoughtful model experimentation  
- reproducible training and evaluation  

This approach reflects good research practice suitable for academic submission.
