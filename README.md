# 🐉 Neon Dragon Login | Cyberpunk Experience

![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20Canvas%20%7C%20Web%20Audio%20API-00ffff)
![Style](https://img.shields.io/badge/Style-Cyberpunk%20%7C%20Glassmorphism-ff0055)
![License](https://img.shields.io/badge/License-MIT-white)

A highly interactive, visually immersive login interface built with **Vanilla JavaScript** and **HTML5 Canvas**. This project moves beyond standard forms by integrating procedural animation, generative audio, and reactive UI elements to create a "Cyber Gate" experience.

## ✨ Key Features

### 1. 🐍 Procedural Dragon Animation
- **Inverse Kinematics-style Movement:** A segmented dragon follows the mouse cursor with fluid, organic delay.
- **Dynamic Particles:** Background particles react to the "tick" rate and shift hues dynamically.
- **Canvas Rendering:** All visuals are drawn programmatically using the HTML5 Canvas API (no static images).

### 2. 🐻 Reactive "Privacy" Bear
- A CSS-drawn character that reacts to user input.
- **Interaction:** When the user clicks the "Net ID" or "Access Key" fields, the bear **closes its eyes** (animating css classes), symbolizing password privacy.

### 3. 🔊 Generative Web Audio
- **No Audio Files:** Music is synthesized in real-time using the browser's **Web Audio API**.
- **The Engine:**
  - **Drone:** A low-frequency sawtooth oscillator with a lowpass filter creates a sci-fi hum.
  - **Arpeggiator:** A sequencer picks random notes from a pentatonic scale to generate a unique melody every time.

### 4. 🎨 Neon Glassmorphism
- **Moving Gradient Borders:** CSS `@keyframes` animate the border colors continuously.
- **Backdrop Filters:** Uses `backdrop-filter: blur(20px)` to create a frosted glass effect over the canvas animation.

## 🛠️ Technologies Used

- **HTML5 Canvas:** For the high-performance 2D dragon animation.
- **Web Audio API:** For synthesis-based sound generation.
- **CSS3:** Flexbox, Keyframes, Variables, and complex gradients.
- **Bootstrap 5:** For the underlying grid and form structure.

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/neon-dragon-login.git](https://github.com/your-username/neon-dragon-login.git)
