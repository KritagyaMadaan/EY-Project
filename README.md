🚀 Autonomous Predictive Maintenance System
AI-Driven Fleet Brain for Real-Time Vehicle Health Monitoring




![Adobe Express - Autonomous Predictive Maintainence Video](https://github.com/user-attachments/assets/e2057b39-ed7c-47a0-a74f-c106283b13a9)







🔑 API Key Setup (IMPORTANT)

If your project uses an external API (OpenAI, Gemini, Map APIs, IoT Cloud APIs, etc.), users must add their own API key.

✅ Where to put the API key

Inside the project, locate the file:

/scripts/config.js


In that file, replace the placeholder with your own API key:

// scripts/config.js

export const CONFIG = {
    API_KEY: "YOUR_API_KEY_HERE",   // ← Replace with your key
    MODEL: "your-model-name",       // Optional
};

If config.js does not exist yet

Create it:

/scripts/config.js


And add:

export const CONFIG = {
    API_KEY: "YOUR_API_KEY_HERE",
};

⚠️ WARNING — Do NOT commit real keys

To protect users:

.gitignore should include:

config.js
.env


Add a template file instead:

config.example.js

export const CONFIG = {
    API_KEY: "PUT_YOUR_API_KEY_HERE",
};


Users copy this:

cp scripts/config.example.js scripts/config.js


And then insert their own key locally.

🎯 Features

✔️ Autonomous fleet scanning
✔️ Real-time vehicle diagnostics
✔️ Predictive maintenance alerts
✔️ Animated engine visualization
✔️ Lightweight and mechanic-friendly UI
✔️ IoT-ready telemetry pipeline

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Visualization: Canvas/Web Animations

AI/ML: Predictive models

Optional Backend: Node.js / Python

IoT Sensors Supported: RPM, vibration, temperature, OBD-II

⚡ Setup Instructions
1️⃣ Clone repo
git clone https://github.com/yourusername/autonomous-predictive-maintenance.git
cd autonomous-predictive-maintenance

2️⃣ Add your API key

Copy template:

cp scripts/config.example.js scripts/config.js


Edit config.js and insert your API key.

3️⃣ Run locally

Just open:

index.html


Or run a simple server:

npx serve



🎬 Demo

Include your video or GIF here:



https://github.com/user-attachments/assets/b3124a4a-844c-4c2c-bc8c-f05c4a9481f0




Or embed:

![Adobe Express - Autonomous Predictive Maintainence Video (2)](https://github.com/user-attachments/assets/dcc766b6-7cc2-417d-9692-bef3c736888a)


⚡ How It Works
1. Scan Fleet

User clicks SCAN FLEET → system enumerates all connected vehicles.

2. AI Health Check

Telemetry is analyzed using ML models such as:

LSTM for anomaly detection

Random Forest for failure classification

Regression models for life-cycle prediction

3. Visualization Layer

Engine & components are overlayed with animated wireframes (like in your GIF).

4. Predictive Alerts

User receives alerts such as:

“High vibration detected → Probable bearing wear in 5 days”

“Engine overheating trend → Check coolant system”

🔧 Installation
Clone the repository
git clone https://github.com/yourusername/autonomous-predictive-maintenance.git
cd autonomous-predictive-maintenance

Run locally

Just open index.html in a browser
—or—
serve using a lightweight server:

npx serve

🚀 Future Enhancements

Mobile app with offline diagnostics

OBD-II real-time streaming

Full 3D engine mapping

Integration with AWS IoT / GCP IoT Core

Advanced LLM-powered mechanic assistant

