                                      Responsive 3D Solar System Simulation
An interactive, realistic, and fully responsive 3D simulation of the Solar System using Three.js. This project visualizes the sun and planets orbiting in space with adjustable speeds, clickable planets for zoom, informative tooltips, and an immersive star field — all optimized for both desktop and mobile devices.
________________________________________
🚀 Features
•	🌞 Realistic 3D Sun and planets with textures
•	🌍 Planetary orbits with rotation and revolution animation
•	🪐 Saturn rings effect
•	✨ Dynamic starfield background
•	🎛️ Individual speed control sliders for each planet
•	🧠 Informative tooltips (on hover/touch) showing:
o	Name
o	Distance from sun
o	Speed
•	🔍 Click/tap a planet to zoom into it
•	🔁 Reset button to return to original view
•	📱 Responsive UI with collapsible panels on mobile
•	☁️ Smooth performance across devices
________________________________________
📁 Project Structure
📦solar-system-simulation/
 ┣ 📄 index.html
________________________________________
🧑‍💻 Technologies Used
•	Three.js – 3D rendering library
•	HTML5, CSS3, JavaScript (Vanilla)
•	Font Awesome (for icons)
________________________________________
🌐 Live Demo
You can deploy this project using GitHub Pages, Netlify, or Vercel.
👉 Live Preview Link (Replace with actual deployed link)
________________________________________
🛠️ How to Run Locally
Option 1: Open with Live Server
1.	Clone the repository:
git clone https://github.com/your-username/solar-system-simulation.git
cd solar-system-simulation
2.	Open index.html using Live Server in VS Code OR just double-click the file to open in browser.
________________________________________
Option 2: Using a Local HTTP Server (recommended for texture loading)
If you run into CORS issues with texture loading (especially on Chrome), use a local server:
# Python 3.x
python -m http.server 8000
Then open: http://localhost:8000
________________________________________
📱 Mobile Optimization
•	Responsive layout with hidden panels on small screens
•	Mobile touch support: swipe, pinch, tap-to-zoom
•	Toggle menu button for controls and info panel
________________________________________
📸 Screenshots
                                                                     Desktop	view

 
<img width="1880" height="1026" alt="Screenshot 2025-07-20 203132" src="https://github.com/user-attachments/assets/38773c48-f5af-437a-8ee0-66f353c50bf6" />

 	 
________________________________________
🧩 Possible Future Enhancements
•	⏳ Add simulation time control (fast forward / pause)
•	🛰 Integrate satellite or asteroid belts
•	🌍 Use high-resolution glTF/GLB models via Sketchfab
•	🗺 Mini-map of the entire system
________________________________________
🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.
________________________________________
📄 License
This project is licensed under the MIT License.
________________________________________
🪐 Credits
•	Three.js Textures
•	Planet textures: NASA, Solar System Scope
•	Icons: Font Awesome
________________________________________
🙌 Acknowledgments
Thanks to the open-source community and Three.js documentation for making 3D web development accessible and fun!

