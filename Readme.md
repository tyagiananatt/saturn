🌌 3D Saturn Gesture System

An interactive 3D particle-based Saturn visualization controlled entirely by hand gestures using MediaPipe Hands and Three.js.
The project transforms real-time webcam hand movements into immersive celestial interactions.

🚀 Features

Real-time hand tracking using MediaPipe

20,000 animated particles forming dynamic shapes

Gesture-based shape switching

Pinch gesture to collapse particles

Smooth 3D motion and glow effects

Runs directly in the browser (no backend)

🛠️ Technologies Used

HTML5

JavaScript (ES Modules)

Three.js – 3D rendering

MediaPipe Hands – Hand gesture detection

WebGL – GPU-accelerated graphics

📦 How to Run the Project
✅ Requirements

A modern browser (Chrome / Edge recommended)

Webcam access enabled

Internet connection (CDN-based libraries)

▶️ Steps to Run

Clone the repository:

git clone https://github.com/tyagiananatt/saturn.git


Navigate to the project folder:

cd saturn


Open the HTML file:

Simply double-click the .html file

OR use Live Server in VS Code (recommended)

Allow camera permission when prompted.

🎉 The 3D Saturn system will start automatically.

✋ Gesture Controls (Important)
🟢 1. Hand Movement (Index Finger)

Move your index finger

The entire particle system follows your hand

Enables natural spatial interaction

🔵 2. Shape Switch (Vertical Gesture)
Gesture Position	Action
Hand raised upwards	🪐 Saturn shape (planet + rings)
Hand lowered downwards	⚪ Sphere shape

➡️ This is detected using the Y-position of the index finger

🔴 3. Pinch Gesture (Thumb + Index Finger)

Pinch your thumb and index finger together

All particles collapse toward your hand

Creates a gravity-like compression effect

Pinch State	Effect
Fingers apart	Particles form structured shapes
Fingers pinched	Particles collapse inward
🧠 How It Works (Concept)

MediaPipe Hands tracks hand landmarks in real time

Index finger position controls particle movement

Distance between thumb & index controls pinch detection

Particles interpolate smoothly between positions

Three.js renders the scene using GPU acceleration

⚠️ Notes & Tips

Best performance on desktop browsers

Ensure good lighting for accurate hand tracking

Only one hand is tracked at a time

Refresh the page if camera doesn’t initialize

📸 Demo Use-Cases

Interactive art installations

Gesture-based UI experiments

Computer vision learning projects

Creative coding & WebGL demos

👨‍💻 Author

Anant Tyagi
B.Tech CSE | Full-Stack & Creative Developer
GitHub: https://github.com/tyagiananatt

📄 License

This project is open-source and free to use for learning and experimentation.