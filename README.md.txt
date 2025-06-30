Smart Sorting: AI-Powered Produce Quality Detection

Overview
Smart Sorting is an innovative project focused on enhancing the precision and efficiency of detecting rotten fruits and vegetables using cutting-edge transfer learning techniques. By leveraging a pre-trained MobileNetV2 deep learning model and adapting it to specific datasets of fruits and vegetables, this project aims to revolutionize the process of sorting and quality control in the agricultural and food industry.

Live Demo
Try the app live here: https://neon-horse-517553.netlify.app

Features

High Accuracy: Robust classification using MobileNetV2 transfer learning

28 Produce Classes: Supports detection of 28 different fruits and vegetables

Real-time Processing: Fast image analysis with Streamlit interface

User-Friendly Interface: Clean and responsive web app using Streamlit

Production Ready: Scalable system suitable for real-world deployment

Project Structure
smart-sorting/
├── app1.py # Main Streamlit application
├── fruitveg_model.h5 # Trained MobileNetV2 model
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── Documents/ # Project reports and docs
├── Frontend/ # (Optional) Frontend files if using Flask/HTML
├── Video Demo/ # Demo video of the application

Installation
Prerequisites

Python 3.7 or higher

8GB+ RAM recommended for model training

GPU support (optional, speeds up training)

Setup Instructions

Clone the repository:
git clone <repository-url>

Change directory:
cd smart-sorting

(Optional) Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate (Linux/macOS) or venv\Scripts\activate (Windows)

Install dependencies:
pip install -r requirements.txt

Place the trained model (fruitveg_model.h5) in the root directory.

Run the Streamlit app:
streamlit run app1.py

Open your browser at the URL shown (usually http://localhost:8501)

Usage

Upload an image of any fruit or vegetable using the upload widget

The AI model predicts if the produce is healthy or rotten

Displays confidence scores and prediction results

Visual feedback to help users reduce food waste and improve sorting

Supported Produce Classes
The model supports 28 classes of fruits and vegetables (healthy and rotten for each):
Apple, Banana, Bell Pepper, Carrot, Cucumber, Grapes, Guava, Jujube, Mango, Orange, Pomegranate, Potato, Strawberry, Tomato, Watermelon, Onion.

Model Architecture

Transfer Learning with MobileNetV2

Input size: 224×224 RGB images

Pre-trained on ImageNet

Custom dense layers added for classification

Optimizer: RMSprop

Loss: Binary Crossentropy

Performance Metrics

Accuracy: Approximately 99% (varies with training)

Fast inference speed suitable for real-time use

Deployment

Local deployment with Streamlit as described above

Optionally deploy with Docker for cloud hosting

Live demo hosted for real-time testing

Future Enhancements

Support more produce types and diseases

Develop mobile app interface

Integrate IoT sensors for automatic sorting

Add real-time video processing

Multi-language support for wider accessibility
