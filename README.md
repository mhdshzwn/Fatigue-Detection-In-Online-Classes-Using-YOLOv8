 🧠 Real-Time Fatigue Detection System
This project is a browser-integrated system that detects student fatigue in online classes using YOLOv8. It utilizes a Chrome Extension to capture webcam frames from platforms like Google Meet, processes them via a Flask backend, and provides fatigue analytics through a real-time dashboard.

📌 Features
🔍 Detects yawning, eye closure, and head tilts

🚨 Triggers visual + audio alerts for “Extreme Fatigue”

🧠 YOLOv8 model trained on custom-labeled facial fatigue dataset

📊 Lecturer dashboard with real-time logs and visualizations

📦 Chrome Extension for browser-based webcam integration

🛠️ Tech Stack
YOLOv8 (Ultralytics)

Flask (Python Backend)

Chrome Extension (HTML, JS)

SQLite + SQLAlchemy

Chart.js Dashboard

📂 Folder Structure
chrome_extension/ – All frontend scripts and popup UI

backend/ – Flask server, API logic, model loader, dashboard

model/ – Trained YOLOv8 .pt file

dataset/ – (optional) sample dataset or Roboflow link

requirements.txt – Python dependencies

🚀 How to Run
Clone this repo

Install Python packages

bash
Copy
Edit
pip install -r requirements.txt
Start Flask server

bash
Copy
Edit
python flask_server.py
Load Chrome Extension (Developer Mode)

Open Google Meet, allow camera, and observe detection

🧪 Example Output

Real-time fatigue detection with popup alert
