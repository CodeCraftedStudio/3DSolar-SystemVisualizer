# 🌌 3D Solar System Visualizer

A high-fidelity, interactive 3D simulation of our solar system built with **Three.js**. This project provides a stunning visual journey through space, featuring realistic orbital mechanics, procedural textures, and a cinematic exploration mode.

---

## ✨ Key Features

- **🔭 Cinematic Tour Mode**: Experience a guided, cinematic flight through the solar system, visiting each planet with dynamic camera angles and detailed information.
- **🌍 Dynamic Scaling**:
  - **Visual Mode**: Planets are scaled for easier observation and navigation.
  - **Realistic Mode**: Accurate relative sizes and distances for a true-to-scale experience (within the constraints of 3D rendering).
- **☀️ Realistic Solar Effects**:
  - Custom GLSL shaders for the Sun's surface and corona.
  - Interactive Lens Flare effects.
  - Post-processing **Bloom** for atmospheric glow.
- **🛰️ Interactive Controls**:
  - Search any planet or celestial body.
  - Time-speed control (pause, slow down, or accelerate the universe).
  - Toggle orbital lines and planet labels.
  - Smooth OrbitControls for manual navigation.
- **📊 Real-time Planet Data**: A detailed overlay panel providing:
  - Distance from Sun (AU)
  - Orbital Period
  - Surface Temperature
  - Relative Mass
  - Atmospheric Composition
- **🎨 Procedural Generation**: Textures for rocky planets, gas giants, and rings are generated programmatically for unique, high-detail visuals.

---

## 🛠️ Technologies Used

- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Graphics Engine**: [Three.js](https://threejs.org/) (WebGL)
- **Shaders**: GLSL (Custom shaders for Sun and Atmosphere)
- **Post-processing**: UnrealBloomPass, EffectComposer
- **Polyfills**: ES Module Shims for import map support

---

## 🔭 Included Celestial Bodies

1. **The Sun**: The glowing center with custom surface noise and corona.
2. **Mercury**: Craters and rocky surface.
3. **Venus**: Thick, glowing atmosphere.
4. **Earth**: Our home, featuring clouds and realistic lighting.
5. **Mars**: The Red Planet with surface detail.
6. **Jupiter**: A massive gas giant with shifting turbulent bands.
7. **Saturn**: Featuring realistic, programmatically generated rings.
8. **Uranus & Neptune**: Distant gas giants with distinct colorations.

---

## 🚀 How to Run

1. **Directly**: Open `solar_system.html` in any modern web browser (Chrome, Edge, Firefox, etc.).
2. **Local Server (Recommended)**: For optimal performance and to handle potential CORS issues with textures/assets, use a local server like:
    - `python -m http.server`
    - `npx serve`
    - `Live Server` extension in VS Code.

---

## 📱 Mobile Support

The visualizer is fully responsive! The UI adapts for mobile devices, moving control panels and info boxes to ensure a smooth space-faring experience on the go.

---

## 🔗 Related Projects

In this workspace, you'll also find specialized visualizers:

- **`saturn.html`**: A focused 3D model of Saturn with high-fidelity ring geometry.
- **`flight_visualizer.html`**: A 3D Earth-based flight tracker and visualizer.

---

> [!NOTE]  
> This project was designed to showcase the power of modern WebGL and Three.js in creating immersive educational tools.

Developed by **Antigravity** (DeepMind) 🚀
