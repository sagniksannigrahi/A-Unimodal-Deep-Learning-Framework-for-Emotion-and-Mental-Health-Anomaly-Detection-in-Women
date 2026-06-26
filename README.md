# A Unimodal Deep Learning Framework for Emotion and Mental Health Analysis

## Overview

This project presents a deep learning framework for Speech Emotion Recognition (SER) to support emotion-aware mental health analysis. The system analyzes speech recordings, extracts meaningful acoustic features, and classifies human emotions using Convolutional Neural Networks (CNN).

The framework is designed to provide accurate emotion recognition that can serve as a foundation for intelligent healthcare, mental wellness monitoring, and human-centered AI applications.

---

## Features

- Speech Emotion Recognition using Deep Learning
- MFCC-based audio feature extraction
- CNN-based emotion classification
- Real-time emotion prediction
- Model comparison and evaluation
- Performance visualization
- Confusion matrix generation
- Accuracy and F1-score analysis

---

## Dataset

**RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**

The dataset contains professionally recorded emotional speech samples across multiple emotion categories.

Detected emotions include:

- Happy
- Sad
- Angry
- Fear
- Neutral
- Calm
- Disgust
- Surprise

---

## Technology Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Librosa
- OpenCV
- Matplotlib
- Scikit-learn

---

## Project Structure

```
├── preprocess.py
├── train.py
├── predict_live.py
├── evaluate_models.py
├── compare_models.py
├── test_female.py
├── Architecture Diagram of Proposed Model.png
├── Confusion Matrix.png
├── Graphs.png
├── Model Comparison.png
└── README.md
```

---

## Workflow

1. Load and preprocess speech dataset
2. Extract MFCC features
3. Train CNN model
4. Evaluate model performance
5. Compare different models
6. Perform real-time emotion prediction

---

## Results

- CNN-based emotion recognition model
- Approximately **85% classification accuracy**
- Performance evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

---

## Applications

- Mental health monitoring
- Healthcare AI
- Emotion-aware virtual assistants
- Human-computer interaction
- Smart wellness systems
- Research in affective computing

---

## Future Improvements

- Multimodal emotion recognition
- Video + Audio fusion
- Transformer-based architectures
- LLM-powered emotion reasoning
- Cloud deployment
- Mobile application integration

---

## Repository Contents

- Source code
- Model training scripts
- Evaluation scripts
- Performance graphs
- Architecture diagram
- Model comparison results

---

## Author

**Sagnik Sannigrahi**

B.Tech Computer Science and Engineering  
SRM Institute of Science and Technology

GitHub: https://github.com/sagniksannigrahi

---

## License

This project is intended for academic and research purposes.
