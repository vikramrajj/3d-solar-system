# 3D Solar System · Cosmic Explorer 🌌

An interactive 3D solar system simulation with stunning graphics, real orbital mechanics, and time travel capabilities. Built purely with HTML, CSS, and [Three.js](https://threejs.org/).

## ✨ Features

- **All Planets & Major Moons**: Includes the Sun, 8 planets (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, Neptune), and 31 major moons.
- **Orbital Mechanics**: Real Keplerian elements (J2000 epoch) are used to calculate the exact astronomical positions of the planets.
- **Time Travel**: Enter any date between 1800 and 2200 to see the planetary alignments for that moment in history or the future.
- **Interactive Information Panels**: Click on any planet or satellite to view detailed stats (type, diameter, orbit radius, gravity, etc.).
- **Camera Controls**: Freely look around, pan, and zoom the 3D scene. Easily switch to a "Top View" for a comprehensive look.
- **Detailed Aesthetics**: Gas giant bands, planetary rings, a dynamic sun pulse, and an immersive starfield.

## 🚀 How to Run

Since the application is contained within a single `index.html` file, running it is incredibly simple:

1. Clone the repository.
2. Open `index.html` directly in your favorite modern web browser.
3. Enjoy the interactive simulation!

## 🎮 Controls

- **Left-click + drag**: Rotate camera around the center.
- **Right-click + drag**: Pan the camera.
- **Scroll wheel**: Zoom in and out.
- **Bottom HUD Buttons**: Toggle Orbit Rings, display Labels, Pause the simulation, or switch to Top View.
- **Set Date (Time Travel)**: Use the bottom-left panel to input a year, month, and day, then press **Set Date** to move to realistic celestial positions. Press **Today** to return to live continuous animation.

## 🛠️ Built With

- **HTML5 & Vanilla CSS**
- **JavaScript (ES6)**
- **Three.js** (WebGL 3D Engine)

## 📡 Keplarian Data

Planetary positions are calculated mathematically using an iterative solver for Kepler's Equation and NASA JPL positional data for standard J2000 epoch orbital elements.
