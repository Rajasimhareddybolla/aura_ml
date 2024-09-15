# Women Safety Threat Detection Software

This project is designed to provide real-time threat detection for women's safety by leveraging advanced computer vision techniques and anomaly detection on CCTV footage. Our solution aims to enhance public safety by identifying potential threats and notifying the authorities for prompt action.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Implementation Details](#implementation-details)
- [Dataset](#dataset)
- [Future Scope](#future-scope)
- [Contributors](#contributors)
- [License](#license)

---

## Features

- **Real-time CCTV Feed Processing**: Analyzes CCTV footage in real time for identifying anomalies and potential threats.
- **Person Detection**: Identifies and tracks individuals present in the CCTV footage.
- **Gender Classification**: Determines the gender of detected persons to focus specifically on women's safety.
- **Anomaly Detection**: Detects unusual behavior or potential threats through advanced AI algorithms.
- **Alert System**: Sends notifications to the nearest police station in case a potential threat is detected.
- **No User Input Required**: Completely autonomous, relying solely on CCTV footage and integrating with police station data.

---

## Tech Stack

- **Programming Languages**: Python
- **Frameworks**: TensorFlow, Keras, OpenCV
- **Libraries**: Ultralytics (for object detection and tracking), Weights & Biases (for model monitoring), Streamlit (for front-end application)
- **Machine Learning Models**:
  - Xception Network for person detection and gender classification
  - Anomaly Detection using the model from Georgescu et al. (2021)
- **Deployment**: Azure Virtual Machines, Docker

---

## System Architecture
+––––––––+            +—————––+            +––––––––+
|  CCTV Footage  |  ——>   |   Threat Detection  |  ——>   |   Police Alert  |
+––––––––+            +—————––+            +––––––––+
|                               |                                |
v                               v                                v
Person Detection               Anomaly Detection               Alert Monitoring
|                               |
v                               v
Gender Classification           Threat Assessment

1. **Input**: Real-time CCTV footage
2. **Processing**: Person detection, gender classification, anomaly detection using AI models
3. **Output**: Alert sent to authorities if potential threats are detected

---

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/women-safety-threat-detection.git


This README covers key sections of your project, giving a professional touch while providing technical and functional clarity. You can adjust specifics to better reflect your implementation.