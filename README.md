# Orbit Visualization and Free Interval Calculator

A web-based interactive satellite tracking and orbital mechanics simulation tool. It renders the Earth using projection views based on user geolocation, simulates satellite trajectories (both circular and two-body conic sections), and calculates "free overflight intervals" where no satellites are passing overhead.
<img width="1866" height="890" alt="Screenshot 2026-08-20 010107" src="https://github.com/user-attachments/assets/b36d0137-0522-489f-926c-2532cc86e615" />


<img width="1878" height="866" alt="Screenshot 2026-08-20 010129" src="https://github.com/user-attachments/assets/800c90af-57b5-4f8c-99a9-1d721816d5d6" />

## Features

* **Real-Time Geolocation Rendering:** Automatically detects the user's location via the browser and maps an overhead (zenith) view along with East-West and North-South side views.
* **Interactive Satellite Simulator:** Tracks multiple default satellites (e.g., Starlink, ISS, OneWeb, GPS, GEO)
* **Overflight Free Interval Calculator:** Computes upcoming gaps in satellite coverage based on a minimum elevation constraint.
* **Multi-View Canvas:** Provides a comprehensive look at space traffic using an overhead zenith view and dual cross-sectional side perspectives.

---

## Project Structure

```text
├── index.html                 # Main UI structure and layout
├── EarthImageRenderer.js      # Handles Earth texture mapping and canvas drawing
├── OverFlightCalculator.js    # Computes overflight periods and free intervals
└── SatelliteSimulator.js      # Manages orbital physics, simulation loops, and UI controls
```

### Installation & Running

**Clone the repository:**
   ```bash
   git clone "https://github.com/BitGlitch404/SatelliteSimulation"
   cd SatelliteSimulation
```
---

This project is open-source and available for everyone.
