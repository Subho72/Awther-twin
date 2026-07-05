# AetherTwin // India Climate Resilience Digital Twin

AetherTwin is a sophisticated, real-time geospatial digital twin platform designed to simulate, analyze, and mitigate the impact of climate-related disasters in major Indian cities[cite: 2]. By integrating real-time weather APIs, topographical data, and AI-driven predictive modeling, AetherTwin empowers decision-makers and emergency responders to visualize flood risks, manage critical infrastructure, and optimize relief operations[cite: 1, 2].

## 🌍 Overview
The platform serves as an interactive "Resilience Digital Twin" for cities like Mumbai, Chennai, Kolkata, and New Delhi[cite: 1, 2]. Users can manipulate meteorological parameters—such as rainfall intensity, storm surge height, and wind speed—to simulate various disaster scenarios[cite: 1]. The system then provides real-time impact assessments on population centers, road networks, and hospital capacity[cite: 1].

## 🚀 Key Features
* **Dynamic Simulation Engine:** Adjustable sliders for real-time climate modeling[cite: 1, 2].
* **Geospatial Visualization:** An interactive map powered by Leaflet, displaying elevation heatmaps, population density, and infrastructure status[cite: 1, 3].
* **AI Analyst Integration:** A built-in Geospatial AI Analyst that answers complex queries about disaster impacts, suggests optimal relief camp locations, and provides emergency advice[cite: 1].
* **Real-Time Data Integration:** Connects to the Open-Meteo API for live weather data and supports Google Earth Engine (GEE) synchronization for satellite-based moisture mapping[cite: 1].
* **Incident Command Tools:** Real-time dispatch capabilities for rescue ambulances and drainage pumps[cite: 1].

## 🛠️ Technology Stack
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)[cite: 2, 3].
* **Mapping:** Leaflet.js with CartoDB Dark Matter tiles[cite: 1, 2].
* **Climate Intelligence:** Real-time data ingestion via Open-Meteo API[cite: 1].
* **Cloud Infrastructure:** Google Cloud-integrated pipelines (Vertex AI, Google Earth Engine)[cite: 1].
* **Resilience Logic:** Custom-built physics and geospatial algorithms for runoff, inundation, and resource loading[cite: 1].

## 🏗️ Project Structure
* `index.html`: Main application layout, sidebar structures, and dashboard UI[cite: 2].
* `style.css`: Custom dark-theme styling, neon-glow effects, and responsive layout management[cite: 3].
* `app.js`: Core simulation logic, event listeners, API handlers, and AI analysis engine[cite: 1].

## 💡 How to Use
1. **Select City:** Use the city selector dropdown to focus the simulation on a specific urban region[cite: 1, 2].
2. **Adjust Parameters:** Use the simulation sliders to set your desired environmental conditions (Rainfall, Surge, Wind)[cite: 1, 2].
3. **Run Simulation:** Click **"Run Resilience Simulation"** to trigger the engine and view immediate impact assessments[cite: 1].
4. **Analyze & Act:** Consult the AI Analyst panel or click on the map elements (hospitals/roads) to view detailed telemetry[cite: 1]. Use the incident dispatch controls to deploy resources[cite: 1].
5. **Live Context:** Use the "MY GPS" button to switch the simulation environment to your current location[cite: 1].

## 🌐 Live Demo
Access the live deployment here: [https://aether-twin.vercel.app/](https://aether-twin.vercel.app/)

## 📝 About
AetherTwin was developed as a proactive solution for urban climate resilience in India, demonstrating the power of integrating AI and Digital Twin technologies for humanitarian and administrative disaster response[cite: 1, 2].
