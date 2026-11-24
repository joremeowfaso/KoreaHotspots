# South Korea Hotspots Directory

A zero-dependency, client-side web application for browsing, filtering, and tagging curated travel locations across South Korea.

## What It Does
* **Multi-Attribute Filtering & Search:** Filter locations in real time by city, custom tags (`Scenery`, `Shopping`, `Beauty`), or keyword search.
* **Dynamic Tag Management:** Create new tags on the fly or toggle existing tags per location via an interactive modal overlay.
* **Client-Side Persistence:** Uses `localStorage` to persist user-submitted locations, custom tag vocabularies, and tag edits across browser sessions without a backend.

## Tech Stack
* **Frontend:** Semantic HTML5, CSS3 (Custom Properties / Dark Mode Grid), Vanilla JavaScript (ES6+)
* **Data & Storage:** Structured JSON schema with browser `localStorage` state synchronization
