MeloChatter 🎵🤖
AI-Powered Song Recommender Based on Emotion Detection

MeloChatter is a web application that detects a user's emotion through their webcam and recommends songs accordingly using a Convolutional Neural Network (CNN) model and the Spotify API. It combines computer vision, machine learning, and full-stack web development into a single interactive experience.

Features
Real-time Emotion Detection: Detects emotions such as happy, sad, neutral, etc., from live webcam feed using face-api.js.
Song Recommendation: Maps detected emotion to Spotify playlists and recommends songs.
Full-stack Integration: Backend in Python (Flask), frontend with HTML/CSS/JS, deployed-ready with Procfile.
Extensible & Interactive: Easy to add more emotions, songs, or custom mappings.

Technologies Used
Backend: Python, Flask
Frontend: HTML, CSS, JavaScript (face-api.js)
Machine Learning: CNN model for emotion recognition
APIs: Spotify Web API
Deployment: Ready for Heroku, Render, or local execution
Other: OpenCV (optional), NumPy, Requests

Getting Started

Follow these steps to run MeloChatter locally:
Clone the repository:
git clone https://github.com/priyagiri16/MeloChatter.git
cd MeloChatter
Install dependencies:
pip install -r requirements.txt
Set environment variables (Spotify API credentials):
export SPOTIFY_CLIENT_ID="your_client_id"
export SPOTIFY_CLIENT_SECRET="your_client_secret"
Run the Flask app:
python main.py
Open in your browser:
http://127.0.0.1:5000/

How It Works
The user opens the app and allows webcam access.
face-api.js detects facial expressions and determines the emotion.
Flask backend receives the emotion and queries the Spotify API.
A list of recommended songs is displayed to the user.

Skills Demonstrated
Real-time computer vision and emotion detection
Machine learning model integration
Full-stack web development (Python + JS + HTML/CSS)
API integration (Spotify)
Deployment readiness and project documentation

Notes & Privacy
Images are processed in-memory and not stored.
For best results, ensure proper lighting and clear webcam input.
The Spotify API requires a free developer account for access.

Future Improvements
Expand emotion categories beyond basic emotions
Add song preview and skip functionality
Include evaluation metrics for emotion detection accuracy
Improve UI/UX and responsive design
