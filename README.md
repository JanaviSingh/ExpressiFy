# 😊 ExpressiFy – Emotion-Based Content Recommendation System Driven by Facial Recognition

> 🎬 Watch what suits your mood. Real-time emotion detection meets personalized content recommendation.
--- Because sometimes we spend hours scrolling… and still can’t find something that matches our mood.

## 🧠 About the Project

**ExpressiFy** is an intelligent content recommendation system powered by real-time **facial emotion detection**. Built with deep learning and computer vision, it captures your current emotional state through your webcam and recommends **movies** that align with your mood.

Traditional platforms suggest content based on your **past**. ExpressiFy recommends based on your **present.**
---

## 💡 Why ExpressiFy?

We’ve all been there — endlessly scrolling through streaming platforms, **unable to find something good to watch**. Hours can pass, and we still feel disconnected from the recommendations.

🎯 What if your device could *feel* your mood and suggest content accordingly?

That’s the problem **ExpressiFy** solves. With a smile, a frown, or a puzzled face — ExpressiFy **adapts to you**.

---

## 🚀 Key Features

- 🎥 Real-time facial emotion detection using your webcam
- 🧠 CNN-based model trained on FER-2013 dataset
- 🎵 Movie recommendations based on detected emotion (via OMDb API)
- ⚡ Instant response through Flask-based backend
- 🌐 Simple and elegant web interface (HTML, CSS, JS)

---

## 📸 Supported Emotions

| Emotion    | Sample Recommendations        |
|------------|-------------------------------|
| Happy 😊    | Comedies, Feel-Good Movies     |
| Sad 😢      | Uplifting Dramas, Musical Healing |
| Angry 😠    | Action, High-Intensity Thrillers |
| Neutral 😐  | Documentaries, Chill Content   |
| Fear 😨     | Mystery, Horror, Thrillers      |
| Surprise 😲 | Sci-Fi, Unexpected Twists      |
| Disgust 😖  | Satire, Dark Comedy            |

---

## 🧠 How It Works

```
ExpressiFy/
│
├── Webcam Input
├── Facial Emotion Detection (CNN Model)
├── Detected Emotion (e.g., Happy, Sad)
├── Recommendation Engine (Flask + OMDb API)
├── Display Personalized Movies on Web UI
```

## 🗂️ Project Structure

```
ExpressiFy/
│
├── static/                 # CSS and JS files
├── templates/              # HTML files
├── dataset/                # FER-2013 based
├── model/                  # Trained CNN model
├── emotion_detector.py     # Emotion detection logic (OpenCV + CNN)
├── recommender.py          # Maps emotion to content category
├── app.py                  # Flask server
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🧪 Dataset Used

**FER-2013** (Facial Expression Recognition)

- 📸 35,887 grayscale images (48x48 pixels)
- 🏷️ 7 Emotion Classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- ✅ Pre-labeled, diverse, robust for training deep models

---

## 📊 Model Performance

| Metric            | Value      |
|-------------------|------------|
| Training Accuracy | 74.35%     |
| Test Accuracy     | 63.54%     |
| Model Type        | CNN        |
| Optimizer         | Adam       |
| Loss Function     | Categorical Cross-Entropy |

---

## 🔧 How to Run the Project

1. **Clone this repository**
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

## 🌈 Future Scope

- 🎧 Add Spotify API for mood-based music
- 📱 Make it mobile responsive
- 🧠 Use hybrid emotion models (e.g., LSTM + CNN)
- 👤 Build user profiles for smarter personalization
- ☁️ Host online (Streamlit, Heroku, or AWS)

---

## 👩‍💻 Authors

| Name           | 
|----------------|
| Janavi Singh   | 
| Sakshi Sinha   | 

---

## 🙌 Show Some Love

If you found this project helpful:

🌟 Star this repository  
🍴 Fork it  
📣 Share with friends  
💬 Drop feedback or open issues  

---

> "When tech understands how you *feel*, it becomes human."
> — *Team ExpressiFy*
