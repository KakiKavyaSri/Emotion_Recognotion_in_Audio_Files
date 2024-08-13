🎙️ ** Speech Emotion Recognition - Sound Classification **

📄 ** Project Overview **

This project focuses on Speech Emotion Recognition (SER) using sound classification. The goal is to identify the emotional state of a speaker based on audio recordings. By leveraging advanced neural network architectures like Long Short-Term Memory (LSTM) networks, this project aims to accurately classify seven distinct emotions from a given set of audio files.

🎧 ** Dataset Information **

The dataset used in this project consists of 2800 audio files, spoken by two actresses (aged 26 and 64 years) under different emotional states. Each target word is spoken within the carrier phrase "Say the word _," representing one of seven emotions:
Anger
Disgust
Fear
Happiness
Pleasant Surprise
Sadness
Neutral

📂 ** Dataset Structure **

Actors: 2 female actors
Emotions: 7 emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, neutral)
Audio Format: WAV files
Total Data Points: 2800 audio files
Organization: The dataset is organized by actor and emotion, with each emotion stored in separate folders.
Download link: https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess 
More Datasets: https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en

🛠️ ** Libraries and Tools **

pandas: For data manipulation and analysis.
matplotlib & seaborn: For data visualization.
librosa: For audio processing and feature extraction.
keras & tensorflow: For building and training the neural network.
sklearn: For preprocessing and model evaluation.

🧠 ** Model Architecture **

The core of this project is a Long Short-Term Memory (LSTM) neural network, which is particularly well-suited for processing sequential data like audio signals. The model architecture includes:

LSTM Layers: To capture temporal dependencies in the audio signals.
Conv1D and MaxPooling1D Layers: For feature extraction from the audio waveforms.
Dropout Layers: To prevent overfitting.
Dense Layers: For final classification.

📊 ** Results **

Accuracy: The model achieved an accuracy of 72.71% on the test dataset.

🔍 ** Conclusion **

This project demonstrates the effectiveness of using LSTM networks for speech emotion recognition. While the current model achieves a reasonable accuracy, there is room for improvement by experimenting with different model architectures, data augmentation techniques, and hyperparameter tuning.

🚀 ** Future Work **

Explore other neural network architectures, such as GRU and CNN-LSTM hybrids.
Implement real-time emotion detection using the trained model.
Expand the dataset with more diverse speakers and emotions.

** Feel free to reach out if you have any questions, suggestions **
