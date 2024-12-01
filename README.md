Orbit Simulation in Python
This is a Python-based simulation of a simplified planetary system using Pygame. The program models the motion of celestial bodies based on gravitational forces, simulating their orbits in a visually interactive way.

Features
Simulates the Sun and four planets: Earth, Mars, Mercury, and Venus.
Each planet's motion is calculated using Newton's laws of gravity.
Realistic orbital paths are traced on the screen.
Displays the distance of each planet from the Sun in real-time.
Technologies Used
Python: Core programming language.
Pygame: For graphics and rendering.


How It Works:
Each planet is represented as an object with properties like mass, position, velocity, and color.

The gravitational attraction between planets is calculated using the formula:
𝐹 =𝐺⋅𝑚1⋅𝑚2/𝑟^2
​
 
Planets are updated frame-by-frame to simulate motion over time.
The simulation uses a scaling factor to map astronomical units (AU) into screen pixels.

Getting Started
Prerequisites
Python 3.x installed on your system.
Pygame library installed. You can install it with:

pip install pygame
Running the Simulation
Clone this repository:

git clone https://github.com/your-username/orbit-simulation.git
cd orbit-simulation

Run the script:
python orbit_simulation.py
Watch as the planets orbit around the Sun in real-time!

Visual Preview
The simulation features a black background with colored orbits and planets:

Yellow: Sun
Blue: Earth
Red: Mars
Dark Grey: Mercury
White: Venus
Future Improvements
Add more celestial bodies like moons or asteroids.
Implement collision detection.
Introduce a user interface for dynamic input and control.
