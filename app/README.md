# ASL Sign Language Interpreter – Real-Time Interaction Module

## Overview
This folder contains the **Human-Computer Interaction (HCI)** component of the ASL Sign Language Interpreter project.

The goal of this module is to enable **real-time, accessible interaction** between users and the trained AI model using a webcam-based interface.

---

## Objectives
- To design a simple and intuitive real-time ASL interpretation interface
- To integrate a trained deep learning model into a live system
- To evaluate usability and accessibility of AI-driven interaction
- To demonstrate AI-assisted communication support

---

## Contents

### `realtime_interpreter.ipynb`
This notebook implements the **real-time interaction pipeline**, including:
- Webcam video capture
- Frame preprocessing for model compatibility
- Loading the trained ASL model
- Real-time prediction of ASL signs
- Visual feedback displayed to the user

The notebook focuses on interaction logic rather than model training.

---

## Interaction Flow
1. User presents an ASL hand gesture to the camera
2. The frame is captured and preprocessed
3. The trained model predicts the corresponding sign
4. The predicted character is displayed on the screen in real time

---

## HCI and Accessibility Focus
This module emphasizes:
- Minimal user effort
- Immediate visual feedback
- Clear and readable on-screen output
- Support for users with hearing or speech impairments

The design follows accessibility-aware HCI principles learned through formal coursework and practical design experience.

---

## Evaluation
Usability and interaction quality are evaluated separately and documented in the `evaluation/` folder, including:
- Usability ratings
- User observations
- Accessibility-related feedback

---

## Research Context
This real-time system demonstrates how AI models can be effectively integrated into
human-centered applications, aligning with research areas such as:
- Intelligent human-computer interaction
- Assistive and accessible computing
- Vision-based interaction systems
