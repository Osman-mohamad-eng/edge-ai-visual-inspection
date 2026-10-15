# Real-Time Edge-AI Computer Vision Inspection

An embedded computer-vision system designed to perform real-time visual inspection and defect detection directly on a BeagleY-AI.

> **Status:** In Development

## Overview

This project develops a real-time Edge-AI visual inspection system that captures camera input, processes images locally, and runs machine-learning inference on the BeagleY-AI to identify abnormal or defective objects without relying on cloud processing.

The goal is to build a complete embedded AI pipeline spanning computer vision, machine learning, Linux, and hardware integration.
## Planned System

Camera Input  
↓  
Image Preprocessing  
↓  
Edge ML Inference  
↓  
Defect Detection / Classification  
↓  
Real-Time Results + Hardware Response

## Technical Goals

- Real-time camera acquisition
- OpenCV image processing
- On-device machine-learning inference
- Defect detection and classification
- Embedded Linux deployment
- Performance benchmarking
- Measure inference latency, FPS, and model accuracy
- GPIO-based hardware response to detected faults

## Tech Stack

- **Hardware:** BeagleY-AI
- **Languages:** Python, C++
- **Computer Vision:** OpenCV
- **Platform:** Embedded Linux
- **Machine Learning:** Edge-AI inference
- **Tools:** Git, CMake

## Project Structure

```text
edge-ai-visual-inspection/
├── src/
│   ├── camera/
│   ├── inference/
│   └── detection/
├── training/
├── models/
├── tests/
├── docs/
│   ├── images/
│   └── architecture/
└── requirements.txt
