# Air Canvas ✨

A 3D interactive drawing experience that lets you create art in the air — built with TypeScript, Three.js, and WebGL. Track hand gestures, draw in 3D space, and even collaborate in multiplayer mode.

---

## Features

- 🖐️ **Real-time hand tracking** – Draw by moving your hand in front of the camera
- 🎨 **3D drawing** – Create strokes that exist in three-dimensional space
- 🌈 **Dynamic visuals** – Balloon inflation effects, colorful particles, and scene interactions
- 👥 **Multiplayer support** – Draw together with others in real time
- 🖼️ **Gesture-based controls** – Intuitive hand gestures to control colors, clearing, and tools

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| TypeScript | Type-safe core logic |
| Three.js | 3D rendering and WebGL |
| Vite | Fast development build tool |
| MediaPipe / TensorFlow.js | Hand tracking and gesture detection |
| WebSocket | Multiplayer synchronization |

---

## Project Structure


---

## How to Run Locally

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/prai-10/Air-Canvas.git
cd Air-Canvas
```
2. Install dependencies
npm install

3. Start the development server
```bash
npm run dev
```
4. Open your browser to http://localhost:5173

How to Use
Gesture                       Action
Index finger extended	        Draw in 3D space
Two fingers extended        	Switch color
Palm open	                    Clear canvas
Fist	                        Inflate balloon / trigger effect
Gestures are detected in real time using your webcam.



This project is built for learning and experimentation. Feel free to explore, modify, and build upon it
