# ❤️ Love Light ❤️ - A WebGL Heart Animation

![Love Light Demo](demo.gif) <!-- Add a GIF or screenshot of your project here -->

**Love Light** is a visually captivating WebGL-based animation that renders a glowing, pulsating heart on a webpage. The project leverages the power of WebGL shaders to create a smooth and dynamic heart animation with a glowing effect. The heart is drawn using a combination of quadratic Bézier curves and a custom heart curve algorithm, resulting in a visually stunning and interactive experience.

---

## 🚀 Features

- **WebGL Rendering:** Utilizes WebGL for high-performance rendering of the heart animation.
- **Shader Programming:** Implements custom vertex and fragment shaders to control the heart's shape, glow, and color.
- **Responsive Design:** The canvas dynamically adjusts to the window size, ensuring the animation looks great on any device.
- **Smooth Animation:** The heart pulsates and glows smoothly, creating a mesmerizing effect.
- **Interactive Background:** The background is set to black to enhance the glowing effect of the heart.

---

## 🛠️ Technologies Used

- **HTML5:** Structure of the webpage.
- **WebGL:** For rendering the heart animation.
- **GLSL (OpenGL Shading Language):** For writing custom shaders.
- **JavaScript:** Handles the animation logic and WebGL context setup.
- **CSS:** Ensures the webpage is visually appealing and responsive.

---

## 🎥 How It Works

1. The WebGL context is initialized, and the canvas is set to fill the entire window.
2. Custom vertex and fragment shaders are compiled and linked to create the WebGL program.
3. The heart's shape is generated using a mathematical heart curve, and the glow effect is achieved through distance-based calculations in the fragment shader.
4. The animation loop continuously updates the time uniform, creating the pulsating effect.

---
