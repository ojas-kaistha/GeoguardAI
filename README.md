# GeoguardAI
# ⚡ GeoGuard AI — Landslide Early Warning Command Center

**GeoGuard AI** is a real-time, interactive geospatial decision-support platform designed for landslide risk monitoring, automated hazard scoring, and emergency evacuation dispatch.

By fusing real-time environmental data with ensemble machine learning, GeoGuard AI provides disaster response teams with predictive insights, interactive 3D terrain visualizations, and explainable AI metrics.

---

## 🌟 Key Features

- 🛰️ **Live GIS & Satellite Data Pipeline:** Automatically fetches 24h rainfall accumulation, 3-day Antecedent Rain Index (ARI), USGS fault line proximity, and SoilGrids geotechnical properties (clay %, pore pressure, shear strength).
- ⛰️ **Dynamic DEM & 3D Spatial Visualization:** Integrated 3D Digital Elevation Model (DEM) hillshades and PyDeck spatial hazard columns for visual terrain assessment.
- 🤖 **Predictive Hazard Engine:** Machine learning core trained on multi-variable geological and hydrological inputs to predict localized incident frequencies.
- 🧠 **Explainable AI (XAI):** Integrated SHAP (SHapley Additive exPlanations) breakdown to highlight key risk drivers behind every prediction.
- 🏃 **Evacuation Routing & Facility Mapping:** Real-time OpenStreetMap Overpass API queries to locate nearby emergency shelters, medical facilities, and safe evacuation paths when hazard thresholds are breached.
- 🚨 **Automated Alerting Protocol:** Integrated email dispatch engine (via Resend API) to send instant alerts to disaster management officers during critical events.
- 🌐 **Multi-Language Support:** Multi-regional UI catering to high-risk zones across India (English, Hindi, Malayalam, Urdu, Assamese).

---

## 🛠️ Tech Stack

- **Frontend & Dashboard:** Streamlit, Streamlit-Folium
- **Geospatial & 3D Visualization:** Folium, PyDeck, Plotly, OpenStreetMap (Overpass & OSRM APIs), Open-Meteo DEM
- **Machine Learning & XAI:** Scikit-Learn (RandomForestRegressor), SHAP, Joblib, NumPy, Pandas
- **Alert System:** Resend SDK
