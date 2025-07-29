# 🎙️ Speech Emotion Recognition using LSTM

A deep learning project to classify human emotions from speech audio using the [TESS Dataset](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess). This project uses **LSTM (Long Short-Term Memory)** neural networks to detect emotions like anger, happiness, sadness, and more based on vocal signals.

---

## 📁 Dataset Information

- **Source:** [Toronto Emotional Speech Set (TESS)](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess)
- **Format:** WAV audio files
- **Size:** 2800 audio clips
- **Speakers:** 2 female actors (ages 26 and 64)
- **Emotions:**
  - Anger
  - Disgust
  - Fear
  - Happiness
  - Pleasant Surprise
  - Sadness
  - Neutral

Each speaker folder contains 200 target words spoken with 7 different emotions, organized neatly for training.

Additional dataset reference:  
🔗 [Speech Emotion Recognition - DmitryBabko](https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en)

---

## 🧠 Model Architecture

- Preprocessing:
  - Audio loading & feature extraction using `librosa`
  - Extracted **MFCC (Mel-Frequency Cepstral Coefficients)** features
- Neural Network:
  - LSTM-based sequential model
  - Softmax output layer for emotion classification
---

## 📚 Libraries Used

- `pandas`
- `matplotlib`
- `keras`
- `tensorflow`
- `librosa`
- `scikit-learn`
- `numpy`

---

## 📈 Results
* Model performs best on easily distinguishable emotions like `anger`, `happiness`, and `sadness`.

---

## 🙌 Acknowledgements

* [Kaggle Dataset – TESS](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess)
* [Librosa – Audio Analysis Library](https://librosa.org/)
* [TensorFlow/Keras](https://www.tensorflow.org/)

---

## 📬 Contact

For collaboration or feedback, feel free to reach out:
📧 [kurapatisowmya1@gmail.com](mailto:kurapatisowmya1@gmail.com)

---
Happy building 🎧🧠
