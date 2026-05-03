# RANASPACE — Space Intelligence Platform

<div align="center">

![RANASPACE Banner](https://img.shields.io/badge/RANASPACE-v2.0-0099ff?style=for-the-badge&logo=satellite)
![Status](https://img.shields.io/badge/Status-NOMINAL-00ff00?style=for-the-badge)
![Built with Claude](https://img.shields.io/badge/Built%20with-Claude%20AI-deepblue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Real-Time Space Intelligence & Orbital Analytics Dashboard**

[🌐 Live Platform](https://rahulkneet2003-gif.github.io/Ranaspace/) • [📖 Documentation](#documentation) • [🤝 Contributing](#contributing)

</div>

---

## 📋 Overview

**RANASPACE** is a comprehensive, open-source intelligence (OSINT) platform providing real-time orbital monitoring, geopolitical space program analysis, and space domain awareness. Built as a single-page HTML5/CSS3/JavaScript application, it integrates live data from NASA, NOAA, SpaceflightNews, and **CelesTrak**.

The platform consolidates critical space data across multiple dimensions:

- ✅ **Real-time orbital tracking** — 8,900+ satellites, 28,000+ debris objects
- ✅ **Geopolitical analysis** — 20+ space-faring nations, 72+ agencies
- ✅ **Launch intelligence** — 18+ active & retired launch vehicles
- ✅ **Mission archive** — Lunar, Mars, crewed, telescope, deep space missions
- ✅ **Live space news** — Real-time aggregation & event monitoring
- ✅ **OSINT toolkit** — Curated resources for space domain awareness
- ✅ **Interactive visualization** — 3D/2D orbital rendering with WebGL

---

## 🎯 Key Features

### 1. Real-Time Orbital Dashboard
```
Active Satellites:    8,900+
LEO Objects:          4,890+ (< 2000 km)
MEO Objects:          138 (2000-35786 km)
GEO Objects:          573 (~35,786 km)
Debris Tracked:       28,000+ (10cm+)
```

### 2. ISS Live Telemetry
- Altitude: 408 km
- Speed: 7.66 km/s
- Crew: 7 aboard
- Orbit Period: 92 minutes
- Real-time position tracking

### 3. Space Weather Integration
- Solar Wind measurements
- Kp Index (geomagnetic activity)
- X-Ray flux monitoring
- Solar Cycle status
- Geomagnetic storm alerts

### 4. Nation Space Programs
Indexed profiles for 20+ nations:
- **Major Powers**: USA, Russia, China, India, ESA
- **Asia-Pacific**: Japan (JAXA), South Korea, Thailand, Vietnam
- **Europe**: France (CNES), Germany, Italy, Sweden, Netherlands
- **Middle East**: UAE, Israel
- **Emerging**: Brazil, Mexico, New Zealand, Canada

### 5. Launch Vehicle Database
18+ orbital rockets with detailed specifications:
- Falcon 9, Atlas V, PSLV, Ariane 5/6, Long March, Soyuz
- Starship (IFT-7 booster catch achievements)
- New Glenn, Vega-E, next-gen Indian launch systems
- Retired systems (Saturn V, Shuttle, N1, etc.)

### 6. Satellite Intelligence
Comprehensive catalog across categories:
- **Space Stations**: ISS, Tiangong, archived systems
- **Earth Observation**: Landsat, Sentinel, SAR systems
- **Navigation**: GPS, GLONASS, Galileo, BeiDou, NavIC
- **Communications**: Starlink, OneWeb, Kuiper, regional systems
- **Scientific**: JWST, Chandra, XMM-Newton
- **Planetary**: Mars rovers, lunar landers, deep space probes

### 7. Live Intelligence Feed
Real-time event stream featuring:
- ISS EVA activities & crew updates
- SpaceX booster catches & Starlink deployments
- Artemis & Gaganyaan mission progress
- JWST scientific discoveries
- International space program achievements

### 8. OSINT Toolkit
Curated open-source intelligence resources:
- Launch tracking platforms
- Orbital prediction tools
- Historical mission archives
- Debris collision prediction
- Space weather monitoring
- Geopolitical space analysis

---

## 🛠 Technical Stack

| Component | Technology |
|-----------|-----------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |
| **Visualization** | WebGL (3D globe), Canvas (2D maps) |
| **Data Integration** | Live REST APIs |
| **Architecture** | Single-page application (SPA) |
| **Styling** | CSS Grid, Flexbox, Custom Properties |
| **Performance** | Client-side caching, API optimization |

### Dependencies
- **NASA Space Data APIs** — Orbital elements, space weather
- **CelesTrak** — TLE (Two-Line Element) data, orbital standards
- **SpaceflightNews API** — Real-time space news aggregation
- **NOAA Space Weather** — Solar wind, geomagnetic data
- **Launch Library 2** — Launch schedule & vehicle specifications

---

## 🚀 Quick Start

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/rahulkneet2003-gif/Ranaspace.git
cd Ranaspace
```

2. **Open in browser**
```bash
# Method 1: Direct file
open index.html

# Method 2: Local server (Python 3)
python3 -m http.server 8000
# Then navigate to http://localhost:8000

# Method 3: Local server (Node.js)
npx http-server
```

3. **Explore the platform**
   - 🌍 Start with the 3D Globe view
   - 📡 Browse satellite intelligence
   - 🚀 Explore nation programs & launch vehicles
   - 📰 Check live space news feed

### Browser Requirements
- Modern browser with WebGL support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Stable internet connection for live data

---

## 📊 Data Architecture

### Primary Data Sources
| Source | Purpose | Update Frequency |
|--------|---------|-------------------|
| **CelesTrak** | TLE data, orbital elements | Real-time |
| **NASA API** | Space weather, ISS telemetry | Live |
| **NOAA SWPC** | Geomagnetic, solar wind data | Real-time |
| **SpaceflightNews** | News aggregation | Continuous |
| **Launch Library 2** | Launch schedules, vehicle specs | Daily |

### Database Coverage
- **Active Satellites**: 8,900+
- **Space Agencies**: 72 (government & private)
- **Nation Profiles**: 20+
- **Launch Vehicles**: 18+
- **Debris Objects**: 28,000+ (10cm+ tracked)
- **Historical Missions**: 200+ landmark missions
- **Key Personnel**: 100+ astronauts, cosmonauts, engineers

---

## 🎓 Use Cases

### Space Industry Professionals
- Monitor competitor launch schedules
- Track satellite constellation deployments
- Analyze emerging space nations & operators
- Research launch vehicle performance metrics

### Government & Military
- Space situational awareness (SSA)
- Debris tracking & conjunction assessment
- International capability analysis
- Policy & strategic planning

### Academia & Research
- Orbital mechanics studies
- Debris evolution research
- Historical mission analysis
- Space weather impact assessment

### Educators & Students
- Learn orbital mechanics interactively
- Explore space program achievements
- Understand geopolitical space competition
- Track real-time space events

---

## 🏆 Notable Recognition

### SMOPS-2026 Conference (Bangalore, April 2026)
RANASPACE was demonstrated to **Dr. T.S. Kelso** of **CelesTrak**, creator of the Two-Line Element (TLE) format and global standard for satellite orbital data. Dr. Kelso appreciated the work and discussed deeper integration of CelesTrak's open-source data.

This collaboration reflects RANASPACE's commitment to responsible OSINT practices and open-source development principles.

---

## 📝 Documentation

### Module Guide

| Module | Purpose | Data |
|--------|---------|------|
| **3D GLOBE** | Interactive orbital visualization | Real-time satellite positions |
| **2D MAP** | Flat projection mapping | Orbital tracks, ground stations |
| **NATIONS** | Geopolitical space program analysis | 20+ nation profiles |
| **ROCKETS** | Launch vehicle specifications | 18+ active/retired systems |
| **SATELLITES** | Orbit parameters & instruments | 8,900+ tracked objects |
| **LAUNCHES** | Live launch schedule | Real-time events via LL2 |
| **MISSIONS** | Historical mission archive | 200+ landmark missions |
| **KEY PERSONS** | Notable figures in space | Astronauts, cosmonauts, engineers |
| **AGENCIES** | Space organizations | 72+ government & commercial |
| **LIVE NEWS** | Real-time space news | SpaceflightNews feed |
| **OSINT** | Intelligence resources | Curated open-source tools |

### Navigation Flow
1. **Entry Point**: Dashboard with key metrics
2. **Explorer Modules**: Click any section to drill down
3. **Data Filtering**: Filter by region, category, status
4. **Detail Views**: Expand for full specifications
5. **Live Updates**: Real-time feed integration

---

## 🔐 Data & Ethics

### Information Classification
- ✅ **Public Data Only** — All information from open sources
- ✅ **OSINT Methodology** — Ethical, legal intelligence collection
- ✅ **Non-Classified** — No restricted government/military data
- ✅ **Educational Purpose** — Professional & academic use

### Responsible OSINT Practices
RANASPACE adheres to:
- Proper data attribution (CelesTrak, NASA, NOAA, etc.)
- Open-source principles & collaborative development
- Transparent methodology for all intelligence
- Respect for international space law & regulations
- No unauthorized data access or misuse

### Authorized Users
- Space industry professionals
- Government space program staff
- Researchers & academics
- Policy makers & analysts
- Students & educators
- Journalists & media

---

## 🔧 Development

### Project Structure
```
Ranaspace/
├── index.html          # Main application file
├── README.md           # This file
└── assets/             # (As needed)
    ├── data/           # Static data files
    └── styles/         # Custom stylesheets (if separated)
```

### Customization
The application is built as a single self-contained HTML file, making it easy to:
- Modify styling (CSS variables)
- Adjust data refresh rates
- Add new modules & features
- Integrate additional APIs
- Deploy to any static hosting

### API Integration
To add new data sources:

```javascript
// Example: Adding a new data endpoint
fetch('https://api.example.com/space-data')
  .then(response => response.json())
  .then(data => {
    // Process and integrate into dashboard
  })
  .catch(error => console.error('API Error:', error));
```

---

## 🤝 Contributing

RANASPACE welcomes contributions from the open-source & space community!

### How to Contribute
1. **Report Issues** — Found a bug or data discrepancy? [Open an issue](https://github.com/rahulkneet2003-gif/Ranaspace/issues)
2. **Suggest Features** — Have ideas? [Start a discussion](https://github.com/rahulkneet2003-gif/Ranaspace/discussions)
3. **Submit PRs** — Code improvements, data updates, documentation
4. **Data Verification** — Help verify accuracy of orbital/agency data
5. **Translation** — Help localize to other languages

### Development Guidelines
- Keep the single-file philosophy (minimal external dependencies)
- Document all API integrations & data sources
- Maintain proper attribution for data sources
- Follow ethical OSINT practices
- Test across major browsers

---

## 📜 License

**MIT License** — Free for personal, educational, and commercial use.

```
MIT License

Copyright © 2025 Rana | Ranalliya Industrie

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

See [LICENSE](LICENSE) file for full terms.

---

## 🙏 Acknowledgments

### Special Thanks

**Dr. T.S. Kelso** — CelesTrak founder, creator of TLE standards, for appreciating RANASPACE and enabling deeper integration of CelesTrak's orbital data. The conversation at SMOPS-2026 in Bangalore reinforced the power of open-source collaboration in advancing space domain awareness.

### Data & Resource Attribution

- **CelesTrak** — TLE data, orbital standards (https://celestrak.gov)
- **NASA** — Space APIs, ISS telemetry, space weather (https://api.nasa.gov)
- **NOAA** — Space Weather Prediction Center (https://www.swpc.noaa.gov)
- **SpaceflightNews** — News aggregation API (https://spaceflightnewsapi.net)
- **Launch Library 2** — Launch schedule & vehicle data (https://ll.thespacedevs.com)
- **descience Open Source Club** — Fostering open-source ethos in space education

### Built With
- **Claude AI** — AI-assisted development for rapid prototyping & iteration
- **HTML5/CSS3/JavaScript** — Web standards
- **WebGL** — 3D orbital visualization
- **Open APIs** — Public data integration

---

## 📞 Support & Contact

### Getting Help
- 📖 Check the [Documentation](#documentation) section
- 🐛 [Report bugs](https://github.com/rahulkneet2003-gif/Ranaspace/issues)
- 💬 [Start a discussion](https://github.com/rahulkneet2003-gif/Ranaspace/discussions)
- 🔗 Cross-reference with official space agency sources

### Connect
- **GitHub**: [@rahulkneet2003-gif](https://github.com/rahulkneet2003-gif)
- **Brand**: Ranalliya Industrie | Space Intelligence Research
- **Status Page**: Check [System Status](#-overview) for real-time updates

---

## 📈 Roadmap

### Upcoming Features (v2.1)
- [ ] Advanced debris collision prediction
- [ ] Extended mission archive (historical + future)
- [ ] Multi-language support (Tamil, Hindi, others)
- [ ] Export capabilities (PDF reports, data downloads)
- [ ] Advanced filtering & search
- [ ] User-defined satellite tracking

### Long-Term Vision
- [ ] Mobile app (iOS/Android)
- [ ] Collaborative intelligence community
- [ ] Integration with academic partnerships
- [ ] Government & institutional licensing
- [ ] Expanded international space program data

---

## 🌌 Current Metrics

**As of May 2026:**

```
┌─────────────────────────────┐
│   RANASPACE v2.0 STATUS     │
├─────────────────────────────┤
│ System Status: ✅ NOMINAL   │
│ Data Feeds: 📡 LIVE         │
│ Database: v2.0              │
├─────────────────────────────┤
│ Active Satellites: 8,900+   │
│ Debris Tracked: 28,000+     │
│ Space Agencies: 72          │
│ Nations Indexed: 20+        │
│ Launch Vehicles: 18+        │
│ Humans in Orbit: 13         │
│ 2024 Launches: 220+         │
└─────────────────────────────┘
```

---

## ⚠️ Disclaimer

RANASPACE is an **open-source intelligence (OSINT)** platform aggregating publicly available space data. All information is derived from:
- Official space agency announcements
- Public APIs and datasets
- Published news sources
- Academic & research institutions

**No classified, restricted, or proprietary information is included.**

For official space domain awareness products, consult government space agencies and authorized monitoring centers.

---

<div align="center">

### Made with ❤️ for the Space Community

**RANASPACE OSINT Platform © 2025**

[⭐ Star this project](https://github.com/rahulkneet2003-gif/Ranaspace) if you find it useful!

[🔗 Live Platform](https://rahulkneet2003-gif.github.io/Ranaspace/) • [📧 Feedback](https://github.com/rahulkneet2003-gif/Ranaspace/issues) • [🤝 Contribute](https://github.com/rahulkneet2003-gif/Ranaspace)

</div>

---

**Last Updated**: May 2026  
**Version**: 2.0 (Stable)  
**Status**: ✅ NOMINAL | 📡 FEEDS LIVE | 🗄️ DB v2.0
