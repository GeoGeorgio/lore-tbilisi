# Project Lore: Tbilisi

## 🎯 App Concept
A mobile-optimized Web App acting as a hyper-local AI storyteller, cultural assistant, and service marketplace. It intentionally excludes flight and hotel bookings. Instead, it focuses on real-time narrative exploration, cultural advice, and direct connections with independent local guides and restaurants in Tbilisi, Georgia.

## 🛠️ Tech Stack & Constraints
* **Frontend:** Single-page application using clean HTML5, modern vanilla JavaScript, and Tailwind CSS.
* **Mapping:** Leaflet.js utilizing open-source OpenStreetMap tiles (No proprietary paid map APIs).
* **Code Architecture:** Highly modular, clean, and documented so a non-technical administrator can easily read and edit data blocks.

## ⚙️ Core Requirements for AI Agents
1. **Dynamic Design Engine:** The app interface must adapt seamlessly to style configuration arrays. The theme switcher must change elements globally (backgrounds, fonts, buttons) based on user selection.
2. **Administrator Manual Control:** All data (locations, GPS coordinates, historical text, culture tips) must be completely detached from the core interface logic. It must live in a clean, easily editable data object at the top of the script file so the site administrator can add new spots manually by just copying and pasting a text block.
3. **No Database Dependencies (MVP):** Keep data inside the front-end structure for now to ensure rapid deployment and effortless edits by a non-technical creator.
