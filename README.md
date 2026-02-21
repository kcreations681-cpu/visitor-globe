# visitor-globe
🌍 Live Visitor Globe
A stunning, interactive 3D visualization of global visitors to my GitHub profile. This project uses Three.js and Web-GL to render a real-time responsive globe that detects and highlights visitor locations using IP Geolocation.

✨ Key Features
Real-time Geolocation: Automatically detects the visitor's city and country using the ipapi service.

3D Interactive Interface: A fully rotatable and zoomable Earth rendered with high-resolution night-sky and topology textures.

Dynamic UI: Greets visitors by name based on their location (e.g., "Hello from Colombo, Sri Lanka!").

Auto-Focus Camera: The camera performantly "flies" and zooms into the visitor's coordinates upon landing.

Visual Ripples: Animated red rings (pulses) highlight visitor points on the map.

Technology,Use Case
Globe.gl-------3D Visualization layer (built on Three.js).
JavaScript (ES6+)-------Logic for data fetching and coordinate mapping.
IPAPI------External API for real-time IP-to-Location conversion.
GitHub Pages------Hosting the live production environment.
CSS3-----Glassmorphism UI effects and responsive layout.

🚀 How It Works
Request: When a user opens the site, a fetch request is sent to https://ipapi.co/json/.

Mapping: The API returns Latitude and Longitude.

Rendering: The Globe.gl engine converts those coordinates into 3D space on the sphere.

Animation: A CSS-driven ripple effect is triggered at the visitor's location, and the camera initiates a smooth transition to that point.

📈 View My Globe
You can interact with the live project here:
👉 [Launch Visitor Globe](https://kcreations681-cpu.github.io/visitor-globe/)

👨‍💻 About Me
I'm a developer passionate about merging data with beautiful visualizations. Check out my other projects on my Main Profile.
AND IAM A 13 Y.O KID❤️
