# Image based Deep Fake Detection using Gradio and PyTorch

This repository contains code for a deep fake detection system using Gradio for building the user interface and PyTorch for the model.

## Prerequisites

Make sure you have the necessary dependencies installed by running:

```bash
pip install gradio torch facenet-pytorch opencv-python
```

## Model Setup

1. **Download the Pre-trained Model:**
   Download the pre-trained model checkpoint `resnetinceptionv1_epoch_32.pth`

2. **Run the Code:**
   Execute the main code file in a Jupyter notebook or a Python script. This code includes the Gradio interface setup, model loading, and prediction logic for the provided image and Launch Gradio Interface.
  

## Usage

1. **Start the Gradio Interface:**
   Run the Gradio interface using the provided code. It will create a user-friendly interface for detecting whether an input image is real or fake.

2. **Upload Image:**
   Upload an image using the interface. The model will analyze the image and provide a prediction.

3. **Interpret the Results:**
   The model will output whether the image is predicted as "Real" or "Fake." Additionally, confidence scores for both classes will be displayed.

## Additional Notes

- The model uses the InceptionResnetV1 architecture pre-trained on the VGGFace2 dataset.
- GradCAM is utilized for visualizing the regions of the image influencing the model's prediction.

