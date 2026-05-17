# ⚙️ Zipper Simulation

An immersive, high-fidelity physical zipper simulation built with Verlet cloth physics, WebGL texture mapping, and dynamic page peeling.

Created by **Felix Obinna**.

🔗 **Live Demo**: [felixchip.github.io/zipper](https://felixchip.github.io/zipper/)

---

## 🌟 Features

- **Verlet Cloth Physics**: Real-time physical simulation of fabric panels using Verlet integration with distance constraints and gravity.
- **WebGL Rendering**: High-performance rendering of the cloth panels with custom-generated, noise-textured procedural fabric.
- **Interactive SVG Zipper Handle**: Pull the zipper handle downwards to split the fabric panels and peel the page.
- **Dynamic CSS Masking**: Smoothly slices layers using CSS `clip-path` synchronized with the physics loop for a seamless transition.
- **Stacked Narrative Pages**: Multiple layered pages (from product landing to bio card) revealed sequentially as the zipper descends.

## 🚀 How to Run

Since the simulation is self-contained in a single HTML file, you can run it directly:

1. **Directly in browser**: Open the `index.html` file in any modern web browser.
2. **Local server (Recommended)**: Serve the file using a simple server to ensure all browser features and smooth rendering:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js
   npx http-server -p 8000
   ```
   Then open `http://localhost:8000/` or `http://localhost:8000/index.html` in your browser.

## 🛠️ Built With

- **HTML5 Canvas & WebGL** (Procedural texture generation, shader compilations, custom projection)
- **JavaScript** (Verlet integration, physics solver, pointer event handlers)
- **CSS3** (Fluid variables, glassmorphism, responsive stack layout)
