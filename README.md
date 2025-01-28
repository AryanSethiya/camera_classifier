# Camera Classifier  

## Overview  
This Python application utilizes camera input to train a **Support Vector Machine (SVM)** to recognize and respond to specific actions in real time. It captures live video, preprocesses the data, and applies machine learning for classification.  

## Features  
- Real-time camera input processing  
- Image data preprocessing for training  
- SVM-based action classification  
- Instant feedback based on recognized actions  

## File Structure  
- `app.py` - Main application script  
- `camera.py` - Handles camera input and preprocessing  
- `model.py` - Implements SVM training and classification  
- `main.py` - Entry point for execution  
- `__init__.py` - Package initialization  
- `README.md` - Project documentation  

## Requirements
To install dependencies, run:
```bash
pip install -r requirements.txt
```

## Usage
Execute the application with:
```bash
python main.py
```

## Future Enhancements
Improve model accuracy using deep learning
Integrate gesture recognition
Optimize real-time processing for performance

