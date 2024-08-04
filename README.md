# Face Emotion Recognition App

## Overview

This project is a Face Emotion Recognition App developed using Python and a pre-trained Keras model. The app detects and classifies emotions from facial expressions in images through a web interface built using Flask.

## Features

- **Emotion Detection**: Identify and classify emotions from uploaded facial images.
- **Real-time Results**: Display emotion predictions immediately after image upload.
- **User-friendly Interface**: Simple and intuitive Python-based web interface for uploading images and viewing results.

## Technology Stack

- **Backend**: Python, Flask, Keras
- **Model**: Pre-trained Keras model (`model.hdf5`)
- **Frontend**: Python (Flask for the web interface)

## Installation

### Prerequisites

- Python 3.8+
- Flask

### Step-by-Step Guide

1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    cd face-emotion-recognition-app
    ```

2. **Install Python Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Download the Pre-trained Model**:
    - Ensure `model.hdf5` is in the project directory.

4. **Run the Flask Application**:
    ```sh
    python app.py
    ```

## Usage

1. **Launching the App**:
    - Open your web browser and navigate to `http://localhost:5000`.

2. **Using the Interface**:
    - Upload an image using the file uploader.
    - View the detected emotion and confidence score displayed on the interface.

## Project Structure

```plaintext
face-emotion-recognition-app/
│
├── app.py                # Main Flask application file
├── config.py             # Configuration file
├── model.hdf5            # Pre-trained Keras model
├── requirements.txt      # List of Python dependencies
├── templates/
│   └── index.html        # HTML template for the web interface
├── static/
│   └── style.css         # CSS file for styling
├── README.md             # Project readme file
└── ...                   # Additional files and directories
```

## Model

The model used in this application is a pre-trained convolutional neural network (CNN) trained on the FER2013 dataset. It classifies facial expressions into several categories, such as happy, sad, angry, surprised, etc.

---

Feel free to reach out with any questions or feedback!

---

*Happy Coding!*
