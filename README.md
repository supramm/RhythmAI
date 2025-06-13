# 🎵 RhythmAI - Mood-Based Music Recommendation System

RhythmAI is a smart music recommendation system that combines your mood, listening history, and genre preferences to generate a curated list of 10 songs that match your vibe.

It features a Spotify-themed React frontend and a FastAPI + Streamlit backend, designed to feel intuitive, fast, and fun.

---

## 🚀 Features

- 😄 Emoji-based mood input
- 📺 YouTube listening history analysis
- 🎶 Genre-mood fusion using audio features and platform context
- 🔟 Returns 10 relevant song recommendations
- 🌐 Google OAuth login (Streamlit version)
- 🎨 Spotify-style frontend UI

---

## 🧱 Tech Stack

- Frontend: React.js, Tailwind CSS
- Backend: Python, FastAPI
- UI (Alt version): Streamlit
- ML/Logic: Pandas, Numpy
- Deployment: Vercel (frontend), Render (backend)

---

## 📁 Project Structure

```
RhythmAI/
├── frontend/                 # React frontend
│   └── src/
│       ├── components/
│       ├── pages/
│       └── App.jsx
├── backend/                  # FastAPI backend
│   ├── main.py
│   ├── recommendation.py
│   └── data/
├── streamlit_app/            # Optional Streamlit version
│   └── app.py
├── requirements.txt
└── README.md
```

---

## 🧪 How It Works

1. You input your current mood via an emoji slider.
2. Your YouTube watch history is processed to identify frequently listened genres.
3. A genre-mood mapping (`PLATFORM_GENRE_MAP`) matches audio features to the mood.
4. RhythmAI selects and returns 10 songs that fit both your mood and context.

---

## 🔧 Installation

### Frontend (React)

```bash
cd frontend
npm install
npm start
```

> Make sure the backend URL is correctly set in your `.env` file.

### Backend (FastAPI)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Optional: Streamlit Version

```bash
cd streamlit_app
pip install -r ../requirements.txt
streamlit run app.py
```

---

## 🌍 Deployment

- Frontend deployed on [Vercel](https://vercel.com/)
- Backend deployed on [Render](https://render.com/)

---

## 🧠 Future Work

- [ ] Add Spotify/YouTube API integration
- [ ] Use facial sentiment/emotion detection for mood
- [ ] Feedback loop for better personalization
- [ ] Playlist export feature

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Supram Kumar  
[GitHub](https://github.com/supram-k) • [LinkedIn](https://www.linkedin.com/in/supram-kumar/)  
Made with ❤️ and headphones on.
