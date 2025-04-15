# 🎧 Moodify – Facial Emotion Based Music Recommender

> **"Let your face pick your playlist."**  
Moodify is an intelligent Machine Learning app that captures your facial expression in real-time and recommends music based on your current mood. Whether you're vibing, crying, or raging — Moodify's got a playlist ready for you.

---

## 🧠 Powered By:
- **DeepFace** – for real-time emotion recognition  
- **OpenCV** – to capture webcam input  
- **Streamlit** – to build a sleek and fast web interface  
- **YouTube** – for music playlist suggestions  

---

## 🚀 Features
- 📸 One-click facial emotion detection
- 🎶 Music genre mapped to your emotion
- 🖥️ Clean and interactive Streamlit UI
- 🔗 Instant redirection to YouTube playlists
- 💡 Easily extendable to use Spotify or store mood history

---

## 🛠️ How to Run Locally

### 1. Clone the repo
```bash
git clone https://github.com/<your-username>/Moodify.git
cd Moodify 
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the app
```bash
streamlit run app.py
```
### 📂 Project Structure
```bash
Moodify/
├── app.py                # Main Streamlit app
├── emotion_detector.py   # Captures webcam and detects emotion
├── recommender.py        # Maps emotion to genre & opens music
├── requirements.txt      # Dependencies
└── README.md             # This file
```
### 🎭 Emotion to Genre Mapping
| Emotion     | Genre           |
|-------------|-----------------|
| Happy       | Pop Music       |
| Sad         | Lo-fi Beats     |
| Angry       | Rock Music      |
| Surprise    | EDM             |
| Neutral     | Instrumental    |
| Fear        | Ambient Sounds  |
| Disgust     | Indie Music     |
### 🔮 Future Ideas
- 🎧 Spotify API Integration

- 🧾 Mood logging + analytics

- 📊 Visual mood trend graphs

- 🗣️ Voice-based interaction

### 🙌 Made with ❤️ by Aman Chhimwal
