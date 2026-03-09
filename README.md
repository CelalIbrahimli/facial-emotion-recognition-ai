# Facial Emotion Recognition AI

Deep learning–based facial emotion recognition system built with **PyTorch** using a **ResNet18 architecture** trained on the **FER2013 dataset**.

The application allows users to upload a facial image and receive the predicted emotion along with confidence scores for each emotion class.

A modern **Gradio interface** is provided and the model is deployed as an interactive web demo.

---

## Live Demo

Try the application here:

[https://huggingface.co/spaces/CelalIbrahimli/emotion-detection-ai](https://huggingface.co/spaces/celalibr/emotion-detection-ai)

Upload a facial image and the model will classify the dominant emotion.

Supported emotions:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

## Demo Video

https://github.com/CelalIbrahimli/facial-emotion-recognition-ai/assets/preview

<video src="demo/emotion_detector_demo.mp4" controls width="800"></video>
---

## Model Information

Architecture:

**ResNet18 (Transfer Learning)**

Dataset:

**FER2013**

Validation Accuracy:

**0.6884**

Training was performed using PyTorch with data augmentation and class weighting to address dataset imbalance.

---

## Features

- Facial emotion recognition from images
- Probability scores for each emotion class
- Modern interactive UI
- Hugging Face Spaces deployment
- PyTorch deep learning pipeline

---

## Tech Stack

- Python
- PyTorch
- Torchvision
- Gradio
- Hugging Face Spaces

---

## Training Pipeline

The training pipeline includes:

1. Loading the FER2013 dataset  
2. Image preprocessing and augmentation  
3. Custom dataset and dataloaders  
4. Baseline CNN training  
5. ResNet18 transfer learning  
6. Model evaluation using confusion matrix and classification report  
7. Deployment with a Gradio web interface  

---

## Results

Classification Report Summary:


accuracy: 0.6884

angry f1: 0.63
disgust f1: 0.52
fear f1: 0.55
happy f1: 0.86
neutral f1: 0.65
sad f1: 0.57
surprise f1: 0.82


The model performs best on **happy** and **surprise** expressions while maintaining balanced performance across other emotion classes.

---

## Installation

Clone the repository:


git clone https://github.com/CelalIbrahimli/facial-emotion-recognition-ai.git

cd facial-emotion-recognition-ai


Install dependencies:


pip install -r requirements.txt


Run the application locally:


python app.py


---

## Future Improvements

- Face detection before emotion classification  
- Real-time webcam emotion recognition  
- Training on larger facial expression datasets  
- Improved augmentation strategies  

---

## Author

**Celal Ibrahimli**  

AI / Machine Learning Engineering

GitHub  
https://github.com/CelalIbrahimli  

LinkedIn  
https://www.linkedin.com/in/celal-ibrahimli-b7a47227b/
