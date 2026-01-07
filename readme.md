HoloBoxe: Real Steel Edition 🥊🤖

Turn your webcam into a boxing ring! HoloBoxe is a browser-based Augmented Reality (AR) fighting game where you fight a virtual robot using your real hands. Powered by Google MediaPipe for real-time hand tracking and a custom 3D rendering engine built on HTML5 Canvas.

(Screenshot of the game in action)

✨ Features

Real-Time Hand Tracking: Uses computer vision to map your real movements to robotic pneumatic arms in the game.

Immersive AR Experience: Inverse perspective scaling makes your virtual hands react realistically to depth (moving closer/further from the screen).

Custom 3D Engine: Lightweight, pseudo-3D rendering engine built from scratch using HTML5 Canvas gradients and math (no heavy 3D libraries).

Dynamic Combat System:

Velocity-based damage detection.

Visual feedback: Screen shake, particle sparks, and flash effects.

Floating health bars and real-time damage feedback.

Smart Enemy AI: The "Titan Bot" dodges, attacks, and has different behavior patterns based on difficulty.

Game Modes: 3 Difficulty levels (Easy, Normal, Hard) with pause menu support.

🎮 How to Play

Allow Camera Access: The game needs your webcam to track your hands (data stays on your device, nothing is sent to a server).

Stand Back: Ensure your upper body and hands are visible to the camera.

Fight!

Punch: Throw punches towards the screen. Speed matters! Slow movements won't register as hits.

Guard: Keep your hands up to protect yourself (visualized by the robotic arms).

Aim: Target the robot's Head (Critical Damage) or Body.

Pause: Press ESC or click the "Pause" button to change difficulty.

🚀 Installation & Usage

No complex installation or backend server is required!

Option 1: Run Locally

Clone this repository:

git clone [https://github.com/your-username/holoboxe.git](https://github.com/your-username/holoboxe.git)


Navigate to the folder.

Open index.html in any modern web browser (Chrome, Edge, Firefox).

Option 2: Live Demo (GitHub Pages)

(Recommended: Enable GitHub Pages in your repository settings to host it for free!)

[Link to your GitHub Pages Demo]

🛠️ Technologies Used

HTML5 / CSS3: Structure and UI styling (HUD, Menus).

JavaScript (ES6+): Game logic, physics, and rendering loop.

MediaPipe Hands: Machine learning solution for high-fidelity hand and finger tracking.

📂 Project Structure

holoboxe/
├── index.html       # The entire game code (Logic + UI + CSS)
├── screenshot.png   # Gameplay preview image
└── README.md        # This file


🤝 Contributing

Contributions are welcome! If you want to add new robot enemies, special moves, or sound effects:

Fork the project.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📄 License

Distributed under the MIT License. See LICENSE for more information.

Made with ❤️ and code. Don't break your monitor!