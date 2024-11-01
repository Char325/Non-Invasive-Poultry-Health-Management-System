# Non-Invasive Poultry Health Management System
This ML + IoT based system enables the detection of unhealthy chickens through real-time audio data. Neural nets are employed to identify any chickens that exhibit rales, which are gurgling sounds indicative of common respiratory illnesses in poultry.
# Introduction
Poultry farming is a critical component of the global food supply chain, providing a significant source of protein through meat and eggs. However, maintaining the health of poultry is a constant challenge due to the susceptibility of chickens to various respiratory illnesses. Early detection and treatment of these illnesses are crucial to prevent widespread outbreaks that can lead to significant economic losses and impact food security.

The Non Invasive poultry Health Management System is an innovative solution that leverages Machine Learning (ML) and Internet of Things (IoT) technologies to enhance poultry health management. This system is designed to detect unhealthy chickens in real-time by analyzing audio data collected from the poultry environment. The core of the system is a neural network model trained on 3 types of data- noise, healthy and unhealthy (Poultry_Data), to identify rales, which are abnormal respiratory sounds indicative of common respiratory diseases in chickens.

# Built With
* <img src= "https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
* <img src="https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white"/>
* <img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/>
* <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
* Matplotlib
# Installation 
```
git clone https://github.com/Char325/Non-Invasive-Poultry-Health-Management-System.git
cd Non-Invasive-Poultry-Health-Management-System
pip install -r requirements.txt

```
# Audio Health Dataset

This repository contains a dataset of audio recordings categorized into three types: healthy, unhealthy, and noise.

### Dataset Description

- **Healthy**: Audio recordings that are considered normal.
  Sample:
  

https://github.com/user-attachments/assets/ce565806-d24d-4fcf-861c-be9831f8daa1


- **Unhealthy**: Audio recordings that indicate some form of abnormality.


https://github.com/user-attachments/assets/66bd7606-e3ae-4202-a0fc-15758120f9c9



- **Noise**: Audio recordings that contain background noise or other irrelevant sounds.


https://github.com/user-attachments/assets/02baffb3-764d-4510-a11d-b4dc16dc6e32

These data showcase minor variations in audio which are often not comprehensible to the human ears and hence, leading to neglect.


## Results

The system provides real-time health status updates and alerts based on the analysis of the collected data. The results are displayed on a dashboard for easy monitoring.

  
# Contributing
Contributions from the community are always welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (git checkout -b feature-branch)
3. Make your changes
4. Commit your changes (git commit -m 'Add some feature')
5. Push to the branch (git push origin feature-branch)
6. Open a pull request
