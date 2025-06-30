# Smart-Sorting-fresh-or-rotten-classifier
# Smart Sorting: AI-Powered Produce Quality Detection

## Overview  
Smart Sorting is an innovative project focused on enhancing the precision and efficiency of detecting rotten fruits and vegetables using cutting-edge transfer learning techniques. By leveraging the pre-trained **MobileNetV2** deep learning model and adapting it to a specific dataset of fruits and vegetables, this project aims to revolutionize the process of sorting and quality control in the agricultural and food industry.

## Live Demo  
[https://neon-horse-517553.netlify.app](https://neon-horse-517553.netlify.app)

---

## Features
- **99.2% Accuracy:** High-precision classification using MobileNetV2 transfer learning  
- **28 Produce Classes:** Supports detection of 28 different fruits and vegetables  
- **Real-time Processing:** Processes thousands of images per minute  
- **Web Interface:** User-friendly Streamlit web application  
- **Production Ready:** Scalable system designed for industrial deployment  

---

## Project Structure  
smart-sorting/
├── app1.py # Main Streamlit app
├── fruitveg_model.h5 # Trained MobileNetV2 model
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── Dockerfile #  For Docker deployment

---

## Installation

### Prerequisites  
- Python 3.7+  
- 8GB+ RAM for model training  
- GPU support (optional, for faster training)  

### Setup Instructions  
1. Clone the repository  
```bash
git clone <repository-url>
cd smart-sorting
# Installation

## Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
