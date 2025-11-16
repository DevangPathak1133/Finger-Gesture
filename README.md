# Finger-Gesture
🎨 AI Virtual Pen &amp; Eraser — Gesture-Controlled Drawing App  AI Virtual Pen &amp; Eraser is a real-time hand-tracking drawing tool that lets you draw, erase, and switch colors using only your hand gestures. Built using OpenCV and Media Pipe, this project turns your webcam into a smart, touch-free drawing canvas.

✨ Key Features
🎯 Gesture-Based Drawing

Draw on the canvas using your index finger

Smooth and accurate line tracking

Multiple brush colors and thickness options

🧽 Virtual Eraser

Activate the eraser using hand gestures

Adjustable erase size

Clean and intuitive erasing behaviour

🖐️ Hand-Tracking Powered

Uses MediaPipe for fast and reliable hand landmark detection

Works in real time with standard laptop webcams

💾 Additional Features

Screenshot saving

Canvas reset

Modular code structure (easy to extend or customize)

Clean separation of logic using classes in src/

🛠️ Tech Stack

Python 3.8+

OpenCV 4.8+

MediaPipe 0.10+

NumPy

📦 Installation
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt

▶️ Run the App
python main.py


Your webcam will open and you can start drawing immediately.

🧱 Project Structure
AI-Pen/
 ├── main.py
 ├── requirements.txt
 ├── src/
 │   ├── canvas_manager.py
 │   ├── gesture_detector.py
 │   ├── hand_tracking.py
 │   └── utils.py
 ├── README.md
