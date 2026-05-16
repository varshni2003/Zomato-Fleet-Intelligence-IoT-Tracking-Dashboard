# Zomato-Fleet-Intelligence-IoT-Tracking-Dashboard
IoT vehicle tracking analysis simulating 500 food delivery agents across Chennai , built with Python, SQL, and Power BI to derive real fleet business insights.

A professional data analytics project simulating real-world IoT fleet tracking for a food delivery company. Analyses 4,924 trip records from 500 delivery agents across 10 Chennai zones using Python, SQL, and Power BI.

---

## 📊 Dashboard Preview
> Open `Zomato_Fleet_Dashboard.pdf` to view the full Power BI dashboard.

---

## 📁 Project Structure
```
├── vehicle_tracking.csv          # Main IoT dataset (4,924 trips)
├── zone_delays.csv               # SQL output — delays by zone
├── peak_hours.csv                # SQL output — peak delivery hours
├── speeding_agents.csv           # SQL output — speeding violations
├── maintenance_needed.csv        # SQL output — vehicles needing maintenance
├── Zomato_Fleet_Intelligence.ipynb  # Google Colab notebook
├── Zomato_Fleet_Dashboard.pdf    # Final Power BI dashboard
└── README.md
```

---

## 🔍 Problem Statement
Food delivery companies like Zomato operate thousands of delivery agents daily. Fleet managers need real-time visibility into agent performance, zone-level delays, speeding violations, and vehicle maintenance schedules. This project simulates that business problem and derives actionable insights from high-volume trip data.

---

## ❓ Business Questions Answered
- Which Chennai zones have the highest delivery delays?
- What time of day sees peak delivery activity?
- Which agents are overspeeding and by how much?
- Which vehicles have crossed safe distance thresholds and need maintenance?

---

## 📦 Dataset
- **Type:** Simulated IoT vehicle tracking data
- **Size:** 4,924 trip records · 500 delivery agents
- **Zones covered:** Anna Nagar, T Nagar, Velachery, Adyar, Tambaram, Porur, OMR, Chromepet, Mylapore, Ambattur
- **Fields:** vehicle_id, agent_name, vehicle_type, zone, timestamp, speed_kmh, distance_km, idle_time_min, delivery_time_min, status, latitude, longitude

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Python | Data simulation and generation |
| SQLite (via Python) | SQL analysis and querying |
| Pandas | Data manipulation |
| Power BI Desktop | Interactive dashboard |
| Google Colab | Development environment |

---

## 📈 Dashboard Features
- **KPI Cards** — Total vehicles, total trips, avg delivery time, avg speed
- **Donut Chart** — Trip status breakdown (Active / Idle / Delayed / Speeding)
- **Bar Chart** — Delayed trips by zone
- **Line Chart** — Peak delivery hours (8am–11pm)
- **Maintenance Table** — Agents exceeding 100km threshold
- **Map Visual** — Fleet location across Chennai by status
- **Slicers** — Filter by zone, vehicle type, and status

---

## 💡 Key Findings
- **Tambaram and T Nagar** have the highest delays — 126 delayed trips each
- **Peak hours are consistent** from 8am to 11pm — no single demand spike
- **Speeding is rare** — only 28 incidents out of 4,924 trips
- **Agent_239 and Agent_250** have crossed 144km — highest maintenance priority

---

## 🚀 How to Run
1. Open `Zomato_Fleet_Intelligence.ipynb` in Google Colab
2. Run all cells in order
3. Download the 5 generated CSV files
4. Load CSV files into Power BI Desktop
5. Recreate dashboard visuals as documented

---

## 👩‍💻 Author
**Varshini**
Aspiring Data Analyst | Chennai, Tamil Nadu
[LinkedIn](https://www.linkedin.com/in/varshini-anburaj-530260227/) · 
---

*Project 3 of a 60-day data analytics portfolio challenge.*
