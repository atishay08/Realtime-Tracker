# 🌍 Real-Time Tracking App

A real-time location tracking web application built with **Node.js**, **Socket.IO**, and **Leaflet**. It displays live positions of users on a map and updates them as they move. When a user disconnects, their marker is removed from the map.

---

## 🚀 Features

- 📡 Real-time GPS location sharing
- 🗺 Live map with Leaflet and OpenStreetMap
- 👥 Multi-user support with unique markers
- 🔌 Instant updates using WebSockets (Socket.IO)
- 🚫 Removes user marker on disconnect

---

## 📦 Tech Stack

- **Backend:** Node.js, Express, Socket.IO
- **Frontend:** HTML, CSS, JavaScript, Leaflet.js
- **Map Provider:** OpenStreetMap

---

## 🛠 Installation

 **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/realtime-tracking-app.git
   cd realtime-tracking-app
Install dependencies:

```bash
  
  Edit
  npm install
```
Start the server:

```bash

  Edit
  node app.js
```

Open in browser:
Visit http://localhost:3000

📁 Project Structure

realtime-tracking-app/
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
├── views/
│   └── index.ejs
├── app.js
└── README.md
📷 Screenshots
(Add screenshots of your map interface here if available)

⚠️ Notes
Location sharing requires permission from the user’s browser.

The app uses navigator.geolocation.watchPosition, so make sure to test it on a device that supports geolocation.

📌 TODO
 Add user names or avatars

 Persist location data in a database

 Show movement trails (routes)

 Deploy to Render / Vercel / Railway

