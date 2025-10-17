# 🌍 Real-Time Location Tracker

A real-time location tracking web app built with **Express.js**, **Socket.IO**, **Leaflet**, and **EJS**. It continuously tracks users' geolocation, shares it via sockets, and visualizes their positions on a live map.

---

## 🚀 Features

- 📡 Real-time geolocation tracking using `navigator.geolocation.watchPosition`
- 🗺️ Interactive map powered by Leaflet.js with OpenStreetMap tiles
- 🔌 Live communication via Socket.IO
- 📍 Dynamic marker management for multiple users
- 🔄 Automatic marker updates and cleanup on disconnect
- 🧭 High-accuracy location tracking with timeout and no caching

---

## 🧰 Technologies Used

- **Backend**: Express.js, Socket.IO
- **Frontend**: EJS templates, Leaflet.js
- **Map Tiles**: OpenStreetMap

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/realtime-tracker.git
cd realtime-tracker
npm install
