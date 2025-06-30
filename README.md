# Pollen Profiling: Automated Classification of Pollen Grains

This project focuses on the automatic classification of pollen grains using Convolutional Neural Networks (CNNs). It includes a simple web-based user interface developed using Flask, allowing users to upload an image of a pollen grain and receive a prediction of its class.

##  Overview

Pollen grains are microscopic and vary in shape, size, and texture. Manual classification is time-consuming and requires expert knowledge. This project aims to automate the process using machine learning, specifically a deep learning-based image classifier.
## project structure 
Pollen_Grain_Classification/
│
├── app.py                          # Main Flask app file (runs the web UI)
├── train_model.py                 # Script to train CNN model
├── model/
│   └── pollen_model.h5            # Saved trained model
│
├── static/
│   ├── css/
│   │   └── style.css              # CSS styling for the web UI
│   ├── js/
│   │   └── script.js              # JS (optional)
│   └── output/
│       ├── result1.jpg            # Sample output prediction image
│       └── ...                    # Add more results as needed
│
├── templates/
│   ├── index.html                 # Homepage with upload form
│   └── result.html                # Result page showing prediction
│
├── dataset/
│   ├── train/
│   │   ├── Class1/                # Example: PollenType_A/
│   │   └── Class2/                # Example: PollenType_B/
│   └── test/
│       ├── Class1/
│       └── Class2/
│
├── requirements.txt              # Python dependencies
├── README.md                     # Project overview and instructions
├── .gitignore                    # Git ignore rules
└── output_video_demo.mp4         # Demo video of working UI (optional)

## 🌟 Features

- Image classification using a trained CNN model.
- Easy-to-use web interface built with Flask.
- Upload pollen grain images and view instant predictions.
- Minimal dataset used for demonstration purposes.
- Modular code: easily upgradable with a larger dataset or deeper model.

## 🗂️ Dataset Summary

This demo uses a small, custom dataset with three categories of floral pollen images:
- **Daisy**  
- **Sunflower**  
- **Rose**

Each class contains 10 sample images for testing and demonstration. The dataset can be extended with microscopic real-world images for better results.

## 🧑‍💻 Developed By

**YAKASIRI JAHNAVI**,
**SATHIGARI SURENDRA**,
**SAGARLA MANOHAR**,
**SAI PUPA**

---

## 📌 Note

This is a demonstration-level project designed to show the feasibility of pollen grain classification using deep learning and to demonstrate integration with a web interface. It can be extended to more classes and trained with real microscopic datasets for production use.
