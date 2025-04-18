# 🐾 Animal Classifier - Deep Learning App

This is a simple deep learning-powered web app that classifies images of animals using a trained TensorFlow model. The app is built using [Gradio](https://www.gradio.app/) for the user interface and can predict the top 5 most probable animal classes from the uploaded image.

## 📦 Features

- 🖼️ Upload an image of an animal
- 🔍 Get top 5 predicted animal categories with confidence scores
- 🎨 Simple, clean, and interactive interface using Gradio
- 🚀 Deployable as a web app or run locally

## 🧠 Model Details

- Built with **TensorFlow/Keras**
- Input size: `180 x 180 x 3` (RGB)
- Trained on 15 animal categories:
  - `Cat`, `Dog`, `Horse`, `Elephant`, `Tiger`, `Lion`, `Monkey`, `Zebra`, `Bear`, `Deer`, `Cow`, `Sheep`, `Rabbit`, `Leopard`, `Giraffe`

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/animal-classifier.git
cd animal-classifier



pip install -r requirements.txt

python app.py
!python app.py

animal-classifier/
├── animal_classifier.h5         # Trained model file
├── app.py                       # Main application script
├── requirements.txt             # Python dependencies
└── README.md                    # This file
