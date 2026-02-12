# 🎵 Graph-Based Music Recommendation System (Enhanced)

**Enhanced and upgraded version of the original graph-based music recommendation system** with improved UI, optimized recommendation logic, cleaner project structure, and enhanced interactivity.

This project builds \
🎧 interactive visual recommendations using **graph theory**, **Spotify audio features**, and **React/Next.js** visualization.

---

## 🚀 Live Demo

> ⚠️ *GitHub Pages deployment is currently disabled due to build limitations.*  
You can run the app locally (see setup below).

---

## 🧠 Overview

This system takes music data (from Spotify & Last.fm), builds a **graph representation** of similarity, and visualizes relationships between songs. It allows users to explore patterns, audio features, and receive recommendations based on graph connectivity and similarity.

Key features include:
- 📊 **Interactive graph visualization**
- 🎶 **Song similarity & recommendations**
- 📈 **Spotify audio feature analysis**
- 💡 **Improved UI with React/Next.js**
- 📁 Organized data pipelines & scripts

---

## 📌 Features

| Feature | Description |
|---------|-------------|
| Graph Construction | Builds similarity graphs using audio features |
| Recommendation | Graph-based nearest neighbor recommendations |
| Visualization | D3.js powered interactive graph |
| UI | Clean React/Next.js interface |
| Dataset Support | Works with cleaned Spotify & Last.fm datasets |

---

## 📁 Directory Structure

📦 .
├── data/ # Raw & cleaned dataset files
├── data-collection/ # Data collection & processing scripts
├── Graph/ # Graph building & random walk scripts
├── public/ # Static assets
├── src/ # Frontend app (Next.js + React)
│ ├── components/
│ ├── pages/
│ └── styles/
├── .github/ # GitHub Actions workflows
├── README.md
├── package.json
└── tsconfig.json


---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js, React |
| Graph Logic | Python |
| Visualization | D3.js |
| Build Tools | Tailwind CSS |
| Data Sources | Spotify API, Last.fm data |

---

## 🎯 Local Installation

### 1. Clone repository  
```bash
git clone https://github.com/vnit-nitesh-yadav/graph-based-music-recommendation-system-enhanced.git
cd graph-based-music-recommendation-system-enhanced
2. Install UI dependencies
(Node.js and npm required)

cd src
npm install
3. Run the frontend
npm run dev
Open a browser and visit:

http://localhost:3000
📊 Data Files
The data/ folder contains cleaned CSVs and example train/test zip files for Last.fm datasets.

⚠️ Some files are large (>50MB). These are included for reference; consider using Git LFS or downloading externally if needed.

🔍 How It Works (High-Level)
Data Collection: Scripts in data-collection/ fetch and clean Spotify/Last.fm song metadata and audio features.

Graph Construction: Python scripts in Graph/ construct a weighted similarity graph using audio feature distances or random walks.

Frontend: The UI loads precomputed data & displays an interactive graph.

Recommendation Logic: Clicking a node shows nearest neighbors and similar songs.

📌 Important Notes
GitHub Pages deployment is disabled — project runs locally.

Large dataset files exceed GitHub recommended sizes.

You can replace datasets with your own cleaned CSVs.

🛠️ Contributions
This project is open for enhancements — feel free to:

Add deployment support

Improve recommendation algorithms

Integrate real Spotify API auth flows

If you improve features or fix bugs, open a PR — feedback welcome!

📝 Attribution
Enhanced based on the original:

➡️ pmanjunath29/graph-based-music-recommendation-system

All enhancements made by @vnit-nitesh-yadav.

📄 License
Distributed under the MIT License — see LICENSE for details.
