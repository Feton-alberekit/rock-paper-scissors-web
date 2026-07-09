# rock-paper-scissors-web
Image classification website for Rock, Paper, Scissors using Teachable Machine and TensorFlow.js
# 🪨✋✌️ Rock Paper Scissors Image Classifier

<p align="center">
  <img src="screenshots/website.png" width="800" alt="Project Website Preview">
</p>

An interactive **image classification web application** that predicts whether an uploaded hand gesture represents **Rock**, **Paper**, or **Scissors**.

The model was trained using **Google Teachable Machine**, tested through the machine learning workflow, exported in **TensorFlow.js** format, and deployed as a browser-based web application using **GitHub Pages**.

🔗 **Live Demo:**  
https://feton-alberekit.github.io/rock-paper-scissors-web/

---

## Project Overview

This project demonstrates a complete and practical machine learning deployment workflow, starting from image data preparation and model training, then moving to model export, web integration, and public deployment.

Unlike traditional machine learning projects that only run inside notebooks, this project allows users to interact with the trained model directly through a web browser. The prediction process runs entirely on the client side using **TensorFlow.js**, which means no backend server is required.

---

## Project Objective

The goal of this project is to build a simple yet complete image classification system that can:

- Classify hand gesture images into three categories
- Run predictions directly in the browser
- Provide an easy-to-use web interface
- Demonstrate AI model deployment using GitHub Pages
- Document the full workflow in a clear and professional GitHub repository

---

## Classes

The model classifies images into three gesture classes:

| Class | Description |
|------|-------------|
| 🪨 Rock | Closed fist gesture |
| ✋ Paper | Open hand gesture |
| ✌️ Scissors | Two-finger gesture |

---

## Features

- Upload an image from the device
- Predict the gesture class automatically
- Display the predicted class
- Show confidence scores for all classes
- Browser-based inference using TensorFlow.js
- No backend server required
- Public deployment using GitHub Pages
- Lightweight and easy to use

---

## Technologies Used

- Google Teachable Machine
- TensorFlow.js
- HTML5
- CSS3
- JavaScript
- GitHub Pages
- Google Colab
- GitHub

---

## Project Workflow

The project followed the workflow below:

1. Collected and prepared image data for three classes
2. Trained an image classification model using Google Teachable Machine
3. Exported the trained model in TensorFlow.js format
4. Built a web interface using HTML, CSS, and JavaScript
5. Integrated the trained model into the website
6. Uploaded model files and project assets to GitHub
7. Deployed the application using GitHub Pages
8. Added sample dataset images and documentation for reproducibility

---

## Dataset

The model was trained on image data representing three hand gestures: Rock, Paper, and Scissors.

A small sample of the dataset is included in this repository for demonstration purposes. The sample contains **5 images from each class**.

```text
dataset_sample/
├── rock/
├── paper/
└── scissors/
```

The included sample dataset helps visitors understand the type of images used for training without making the repository unnecessarily large.

---

## Model

The trained model was exported from Google Teachable Machine in **TensorFlow.js** format.

The model files are stored in the `model` folder:

```text
model/
├── model.json
├── metadata.json
└── weights.bin
```

These files are loaded directly by the web application to perform prediction inside the browser.

---

## Repository Structure

```text
rock-paper-scissors-web/
│
├── index.html
├── README.md
│
├── model/
│   ├── model.json
│   ├── metadata.json
│   └── weights.bin
│
├── dataset_sample/
│   ├── rock/
│   ├── paper/
│   └── scissors/
│
├── notebooks/
│   └── model_test_colab.ipynb
│
└── screenshots/
    ├── website.png
    └── prediction_result.png
```

---

## How to Use the Web App

1. Open the live demo link.
2. Upload an image of a hand gesture.
3. The model will analyze the image.
4. The predicted class will be displayed.
5. Confidence scores for each class will also be shown.

Live Demo:

```text
https://feton-alberekit.github.io/rock-paper-scissors-web/
```

---

## How to Run Locally

Clone the repository:

```bash
git clone https://github.com/feton-alberekit/rock-paper-scissors-web.git
```

Open the project folder and run it using a local server.

For example, using VS Code:

1. Install the **Live Server** extension.
2. Open the project folder.
3. Right-click `index.html`.
4. Choose **Open with Live Server**.

---

## Sample Prediction Output

The application displays the prediction result in a user-friendly way, including:

- The most likely predicted class
- Confidence score for each class

Example:

```text
Prediction: Rock

Rock: 98.42%
Paper: 1.10%
Scissors: 0.48%
```

---

## Screenshots

### Website Interface

<p align="center">
  <img src="screenshots/website.png" width="700" alt="Website Interface">
</p>

### Prediction Result

<p align="center">
  <img src="screenshots/prediction_result.png" width="700" alt="Prediction Result">
</p>

---

## Key Learning Outcomes

Through this project, I practiced:

- Image classification concepts
- Preparing a simple multi-class dataset
- Training a computer vision model
- Exporting a model for web deployment
- Using TensorFlow.js for browser-based inference
- Building a simple AI-powered web interface
- Deploying a machine learning project with GitHub Pages
- Organizing and documenting an AI project professionally on GitHub

---

## Future Improvements

Possible future enhancements include:

- Adding webcam-based live prediction
- Adding drag-and-drop image upload
- Improving the user interface design
- Displaying confidence scores as visual progress bars
- Adding more gesture classes
- Testing the model on a larger and more diverse dataset
- Creating a performance evaluation section
- Adding a confusion matrix and accuracy report

---



