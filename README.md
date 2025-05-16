# 🌌 3D Solar System Simulation

## 🚀 [Experience the Cosmos](https://unanimousaditya.github.io/3D-Solar-System/)

An interactive, visually stunning 3D simulation of our solar system built with **Three.js**. Explore the planets, their orbits, and the vast beauty of space from your browser!

## 🌠 Description

This project creates an immersive, scientifically-inspired visualization of our solar system, featuring all eight planets orbiting around the sun with realistic textures and proportional orbital mechanics. The simulation allows users to navigate through space, zoom in on planets, and experience the celestial dance of our cosmic neighborhood.

## ✨ Features

- 🪐 Detailed 3D models of all eight planets with high-resolution textures
- ☀️ Realistic sun with glowing shader effects
- 🛰️ Accurate orbital paths and rotational speeds (time-scaled)
- 🖱️ Interactive camera controls for exploring the solar system
- 🔭 Ability to focus on specific planets with information panels
- 🌑 Realistic lighting and shadow effects
- 💫 Particle system for stars and distant celestial objects
- 📱 Responsive design that adapts to different screen sizes
- 🎮 User-friendly controls with intuitive navigation

## 🕹️ Controls & Interaction

- 🔄 **Orbit**: Click and drag to rotate the view around the solar system
- 🔍 **Zoom**: Use the scroll wheel to zoom in and out
- 👆 **Select Planet**: Click on any planet to focus the camera on it
- ⏯️ **Toggle Animation**: Pause/resume planetary motion
- ⏱️ **Time Controls**: Adjust simulation speed
- 🔙 **Reset View**: Return to the default perspective

## 💻 Technology Stack

- **Three.js** 🧊 - Powerful JavaScript 3D library for rendering the solar system
- **HTML5** 📝 - Structure and canvas element for rendering
- **CSS3** 🎨 - Styling, animations, and responsive design
- **JavaScript** ⚙️ - Core programming for the simulation physics and interactivity:
  - Orbital calculations
  - Lighting and effects
  - Camera management
  - User interaction handling

## 🧪 Technical Implementation Details

- **Celestial Physics** - Simplified but proportionally accurate planetary motion
- **Custom Shaders** - GLSL shaders for the sun's corona effect and atmospheric glow
- **Texture Mapping** - High-resolution NASA textures for planetary surfaces
- **Dynamic Lighting** - Sun-centered lighting system with shadow mapping
- **Optimized Rendering** - Level-of-detail adjustments for smooth performance
- **Orbital Mechanics** - Elliptical orbits with proper inclination angles

## ⚡ Installation

To run the simulation locally:

1. 📂 Clone the repository:
   ```bash
   git clone https://github.com/unanimousaditya/3D-Solar-System.git
   ```

2. 📁 Navigate to the project directory:
   ```bash
   cd 3D-Solar-System
   ```

3. 🌐 Set up a local server:
   - Using Python 3:
     ```bash
     python -m http.server
     ```
   - Using Node.js:
     ```bash
     npx serve
     ```

4. 🚀 Open your browser and go to `http://localhost:8000` or the port specified by your local server

## 📚 Code Structure

- `index.html` - Main HTML document containing the canvas and UI elements
- `styles.css` - Styling for the user interface and controls
- `main.js` - Core application logic and Three.js initialization
- `planets.js` - Data and configuration for all celestial bodies
- `orbit.js` - Orbital mechanics and motion calculations
- `camera.js` - Camera control and movement logic
- `shaders/` - Directory containing GLSL shader code for special effects
- `textures/` - Directory containing all planet and star textures
- `models/` - 3D models for any additional celestial objects

## 🎨 Customization Possibilities

You can easily modify the simulation to explore different aspects of our solar system:

- 🌓 **Add Moons** - Implement major moons for the gas giants
- 💫 **Include Asteroid Belt** - Add a particle system for the asteroid belt
- 🌠 **Comet Trajectories** - Simulate comets with highly elliptical orbits
- 📏 **Scale Adjustments** - Modify the size and distance scales for different views
- 🎭 **Alternative Textures** - Swap in different planet textures (historical maps, false color, etc.)

## 🤝 Contributing

Contributions to enhance this cosmic simulation are warmly welcomed! Here's how you can contribute:

1. 🍴 Fork the repository
2. 🌿 Create a new branch (`git checkout -b feature/amazing-cosmic-feature`)
3. ✏️ Make your stellar changes
4. 💾 Commit your changes (`git commit -m 'Add some amazing cosmic feature'`)
5. 📤 Push to the branch (`git push origin feature/amazing-cosmic-feature`)
6. 🔁 Open a Pull Request describing your cosmic additions

### 💡 Enhancement Ideas
- Add dwarf planets (Pluto, Ceres, Eris, etc.)
- Implement spacecraft models with historical mission trajectories
- Create time-based events like planetary conjunctions
- Add educational information panels for each planet
- Develop VR compatibility for immersive exploration

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔭 Astronomical Accuracy Note

This simulation balances visual aesthetics with scientific accuracy. While the orbital mechanics follow correct principles, sizes and distances are not strictly to scale (as the true scale of the solar system would make the planets nearly invisible). The simulation preserves relative planetary sizes and orbital characteristics while making the visualization accessible and engaging.

## 👏 Acknowledgments

- 🌟 Planet textures courtesy of NASA's visible imagery collection
- 🔭 Orbital calculations based on NASA JPL ephemeris data
- 🙏 Created with passion by [Aditya Raj](https://github.com/unanimousaditya)
- 📚 Special thanks to the Three.js community for examples and inspiration

## 📞 Contact

- 👨‍💻 GitHub: [@unanimousaditya](https://github.com/unanimousaditya)

---

🌌 Embark on your cosmic journey through our solar system! Don't forget to star ⭐ the repo if you enjoyed exploring!
