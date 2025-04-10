# 😊 ExpressiFy – Emotion-Based Content Recommendation System

> 🎬 *Watch what suits your mood. Real-time emotion detection meets personalized content recommendation.*

---

## 📌 Overview

**ExpressiFy** is an innovative AI-based web app that uses your **facial expressions** to recommend **movies** tailored to your **current mood**. Unlike traditional recommendation systems that rely solely on user history, ExpressiFy uses **real-time emotion recognition** to make your digital experience emotionally intelligent.

---

## 🎯 Key Features

- 🎥 **Real-time Emotion Detection** via webcam using CNN
- 🎵 **Content Recommendation Engine** for movies via APIs
- ⚡ Seamless integration of Frontend (JS, HTML/CSS) with Backend (Flask, TensorFlow)
- 🧠 Powered by FER-2013 dataset & Deep Learning
- 📱 Clean and user-friendly UI

---

## 🧠 How It Works

flowchart TD
A[Webcam Input] --> B[Facial Emotion Detection (CNN Model)]
B --> C[Detected Emotion (e.g., Happy, Sad)]
C --> D[Recommendation Engine (Flask + OMDb API)]
D --> E[Display Personalized Movies/Music on Web UI]


---

## 💡 Motivation

> We often don't know *what* to watch—but we always *feel* something and spend hours searching and not finding anything according to our mood.

Traditional platforms suggest content based on your past. **ExpressiFy** recommends based on your **present**.

---

## 🧪 Dataset Used

### FER-2013 (Facial Expression Recognition Dataset)

- 🖼️ 35,000+ grayscale facial images (48x48 pixels)
- 7 Emotion Classes: 😠 Angry, 😖 Disgust, 😨 Fear, 😊 Happy, 😐 Neutral, 😢 Sad, 😲 Surprise

---

## 🛠️ Technologies Used

| Category | Tech Stack |
|----------|------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python, Flask |
| **AI/ML** | TensorFlow/Keras, OpenCV |
| **APIs** | OMDb (Movies), Emotion Mapping |
| **Others** | FER-2013 Dataset, Joblib |

---

## 📂 Project Structure

```
ExpressiFy/
│   
├── static/                 # CSS, JS, Images
├── templates/              # HTML templates
├── dataset/                # FER-2013 Dataset
├── model/                  # Trained CNN Model
├── app.py                  # Flask backend
├── emotion_detector.py     # Webcam & model inference
├── recommender.py          # Content mapping logic
├── README.md               # Documentation
└── requirements.txt        # Dependencies

```

---

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/ExpressiFy.git
   cd ExpressiFy
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python app.py
   ```

4. **Open in browser**
   ```
   http://localhost:5000
   ```

---

## 📸 Screenshots

| Emotion Detected | Suggested Content |
|------------------|-------------------|
| 😊 Happy          | Comedy, Feel-Good Movies |
| 😢 Sad            | Uplifting, Emotional Dramas |
| 😠 Angry          | Action, Intense Thrillers |

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| 🎯 Training Accuracy | 74.35% |
| 🧪 Test Accuracy     | 63.54% |
| 🧾 Confusion Matrix  | Evaluated across 7 emotion classes |

---

## 🚀 Future Enhancements

- ✅ Add user profile & watch history memory
- ✅ Support for music APIs (e.g., Spotify)
- 🌐 Deploy to cloud (Heroku/AWS)
- 📱 Build a mobile-friendly version

---

## 👩‍💻 Authors

| Name |
|--------------|
| Janavi Singh |
| Sakshi Sinha | 

---

## 🌟 Show Your Support

If you like this project:

✅ Star it on GitHub  
🍴 Fork it for your own experiments  
📢 Share it with your peers!
