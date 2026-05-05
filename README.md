# 🚆 RailPulse -  Real-Time Train Location & Transit Monitoring System

The frontend component of the **RailPulse ecosystem**, engineered with **React (frontend)** to visualize real-time geospatial data and a **Node.js + MongoDB backend**.  
It allows **secure login** and displays **train locations on an interactive map** using **Leaflet**.. 
It features seamless integration with REST APIs, efficient state management for live train coordinates, and a modular component architecture. Designed for high visibility and real-time monitoring of railway networks.

---

## 📌 Features

- 🔹 **Secure Login** using JWT authentication  
- 🔹 **Session-based token storage**  
- 🔹 **Real-time train location updates** (auto-refresh every second)  
- 🔹 **Interactive Map** using [React Leaflet](https://react-leaflet.js.org/)  
- 🔹 **Dynamic markers with popup info** (Train ID, coordinates, last update)  
- 🔹 **Responsive UI** for desktop  

---

## 🛠️ Tech Stack

**Frontend:**  
- React 18  
- React Router DOM  
- React Leaflet & Leaflet CSS  
- Fetch API for HTTP requests  

**Backend:**  
- Node.js + Express  
- MongoDB (for train location data)  
- JWT for authentication  

---
## 🗺️ Train Map

- Shows **real-time train locations** on a Leaflet map  
- Each marker popup displays:  
  - **Train ID**  
  - **Latitude & Longitude**  
  - **Last updated timestamp**  


