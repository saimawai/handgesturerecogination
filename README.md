This project implements a Convolutional Neural Network (CNN) to classify hand gestures from the LeapGestRecog dataset. It recognizes multiple static hand gestures and can be used for HCI (Human–Computer Interaction), robotics control, sign-language support, or gesture-based applications.
 Features

✔️ Deep learning model built using TensorFlow / Keras

✔️ Automatically preprocesses and augments images

✔️ Trains a CNN for multi-class gesture classification

✔️ Achieves high accuracy on the test set

✔️ Easy-to-reproduce training pipeline

✔️ Well-structured and beginner-friendly code
---> Dataset

The model uses the LeapGestRecog dataset, which contains:

10 gesture classes

200 directories (20 users × 10 gestures)

2000+ grayscale images per gesture
--project structure--
    ├── data/
├── src/
│   ├── train.py
│   ├── model.py
│   ├── preprocess.py
│   └── predict.py
├── notebooks/
├── saved_models/
└── README.md
  
