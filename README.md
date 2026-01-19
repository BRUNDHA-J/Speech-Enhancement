"## Speech Enhancement using Deep Learning

### Overview
This project focuses on single channel speech enhancement, where the goal is to reduce background noise from noisy speech signals using deep learning techniques. The project compares multiple deep learning models for noise suppression and speech quality improvement.

### Problem Statement
Speech signals are often degraded by environmental noise.
Reducing noise without losing important speech information is challenging, especially in real-world conditions where noise characteristics vary.

### Objective
Study existing speech enhancement methods
Implement deep learning models for noise suppression
Compare model performance using experimental results

### Dataset
The VCTK speech dataset is used for training and evaluation.
It contains clean and noisy speech samples from multiple speakers.
Audio sample length ranges up to 15 seconds.

### Models Implemented
DTLN (Dual-Signal Transformation LSTM Network)
Wave-U-Net
CRNN (Convolutional Recurrent Neural Network)

### Approach
Preprocess clean and noisy speech signals
Train deep learning models on noisy-clean speech pairs
Evaluate noise suppression performance using waveform and spectrogram analysis

### Results
All implemented models were able to suppress background noise.
DTLN performed better compared to Wave-U-Net and CRNN.
The enhanced speech showed reduced noise with preserved speech quality.

### Tools and Technologies
Python
Deep Learning (LSTM, CNN, CRNN)
Audio Signal Processing
TensorFlow / Keras"
