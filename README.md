Solar System Simulation using Three.js:

This project is a dynamic 3D simulation of the solar system, created using Three.js. It includes textured and accurately scaled models of planets and celestial bodies with realistic orbital movements. The simulation allows users to explore the solar system interactively.

Features:

3D Solar System Model: Displays the planets, the Sun, and other celestial objects with accurate scaling and positioning.
Interactive Controls: Users can navigate through the solar system using mouse movements, zoom in and out, and rotate around objects using OrbitControls.
Realistic Orbits: The planets revolve around the Sun, simulating real-time motion.
Lighting Effects: Implemented realistic lighting with the Sun as the primary light source, illuminating the planets.
Textured Models: Planets and celestial bodies have realistic textures, creating an immersive experience.

Technologies Used:

Three.js: 3D rendering and scene creation.
JavaScript: Used to manage the application logic.
OrbitControls: For enabling interactive navigation within the 3D space.
Shaders: Custom shaders were applied for dynamic visual effects.

Installation and Usage
Clone the repository:
git clone https://github.com/abhisheksahani129/solar-system.git
Navigate to the project directory:
cd SolarSystem

Install the dependencies:

npm install

Start the project:

npm run dev

Open your browser and go to http://localhost:3000 to view the solar system simulation.

Customization:
Add New Planets: You can add additional planets or celestial bodies by modifying the solarSystem.js file.
Adjust Orbit Speed: The speed of the planets' revolution can be adjusted by modifying the parameters in the animation loop.
Change Textures: Replace the planet texture images in the assets/ folder to use your own custom textures.
