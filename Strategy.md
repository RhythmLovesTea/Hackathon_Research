## 2️⃣ Prototype Objectives (36-hour Hackathon)

1. Visualize **satellite orbits** (public TLE data).  
2. Simulate **collision/conjunction scenarios**.  
3. Provide **maneuver conflict alerts**.  
4. Show **heatmaps of orbital congestion**.  
5. Allow **secure upload of TLE/orbital data** (anonymized).  
6. Demonstrate **dashboard UI/UX** with interactive visualizations.  

---

## 3️⃣ Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| Frontend | React.js + D3.js / CesiumJS | Interactive orbit visualization, heatmaps, maneuver alerts |
| Backend | Python (FastAPI / Flask) | API endpoints for TLE upload, collision simulation, risk calculations |
| Orbit Simulation | Skyfield / Poliastro | Parse TLEs, propagate orbits, detect conflicts, simulate maneuvers |
| Database | PostgreSQL | Store TLEs, satellite info, maneuver logs |
| Optional AI Layer | Scikit-learn / TensorFlow Lite | Predict collision risk, reduce false alarms |
| Hosting / Demo | Local server / Hackathon VM / Replit | Quick deployment for demo |

---

## 4️⃣ Team Roles & Task Allocation (6 Members)

| Member | Task | Deliverables |
|--------|------|-------------|
| 1 | **Frontend Developer** | Build interactive dashboard with satellite orbits, heatmaps, maneuver alerts | --Ankit kumar das
| 2 | **Backend Developer** | API endpoints for TLE upload, collision simulation, and risk calculations | --Nilesh
| 3 | **Orbit Simulation Specialist** | Parse TLEs, propagate orbits, detect conflicts, simulate maneuvers using Skyfield/Poliastro |--Rhythm
| 4 | **Database & Integration** | Setup PostgreSQL, store TLEs/maneuvers, connect backend with frontend | --Ashutosh
| 5 | **UI/UX & Visualization Designer** | Dashboard layout, heatmaps, color-coded alerts, user-friendly design | -- Shruti 
| 6 | **Demo Coordinator / QA / Scriptwriter** | Test end-to-end flow, prepare sample scenarios, handle deployment, create judge-ready script | --Abhisheik

> 🔹 Clear division ensures prototype completion within **36 hours**.  
> 🔹 Optional AI or advanced features can be deferred to **future expansion**.

---

## 5️⃣ Minimum Viable Prototype Features

1. Visualize **2–3 satellites** (e.g., ISS + weather satellite).  
2. Simulate a **collision course** → dashboard flags red zones.  
3. Provide **maneuver conflict alerts** → safer path recommendations.  
4. Show **heatmap of orbital congestion** (demo with limited dataset).  
5. Secure upload of **anonymized satellite TLEs**.  

---

## 6️⃣ Demo Flow

1. **Load public TLE data**.  
2. **Simulate collision scenario** → dashboard shows alert.  
3. **Plan maneuver** → conflict highlighted.  
4. **Adjust maneuver** → conflict resolved, risk zone cleared.  
5. **Display heatmap** → visualize high-density orbital regions.  

---

## 7️⃣ Future Extensions / Hackathon Bonus Points

| Feature | Scope |
|---------|-------|
| AI Collision Prediction | Train on historical conjunctions → reduce false alarms |
| Global Real-Time Dashboard | Integrate multiple datasets (commercial satellites, telescope/radar feeds) |
| Fuel-Optimized Maneuvers | Suggest minimum Δv maneuvers, combine orbit correction + avoidance |
| Proactive Orbit Allocation | AI-based long-term mission planning to avoid future conflicts |
| Multi-Agency Collaboration | Universities, startups, agencies contribute anonymized data; federated platform |
| Public/Mobile Interface | Simplified visualization for STEM education and awareness |

---

