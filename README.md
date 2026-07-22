# 🏰 Fort Explorers — Canada's Historic Forts

An interactive, kid-friendly web app (ages 6–12) that maps 12 of Canada's National Historic Site forts and turns their history into games. Click a fort to see real photos, hear its story read aloud, learn what daily life was like, and play quizzes and mini-games — all in a single HTML file with no install.

**▶️ Live demo:** _add your GitHub Pages link here once published (e.g. `https://<username>.github.io/fort-explorers/`)_

![A map of Canada with red pins marking historic forts](docs/screenshot.png)
<!-- Optional: add a screenshot at docs/screenshot.png -->

## ✨ Features

- **Interactive map of Canada** (Leaflet + OpenStreetMap) with 12 forts at their real coordinates, from the Fortress of Louisbourg (NS) to Fort Rodd Hill (BC). Falls back to a clickable fort grid if the map can't load.
- **Each fort** has real photos (loaded live from Wikimedia), a story, quick facts, a **read-aloud** button, a tap-a-word **glossary**, and an **"A Day in the Life"** section (commander, commander's wife, soldier, soldier's wife, children).
- **Quizzes** with three difficulty levels (🐣 Easy, ⭐ Medium, 🔥 Hard — Hard is timed), each with its own question bank.
- **Explorer Passport** that tracks best scores per level and stamps a fort only when all three quizzes are completed, plus a printable certificate.
- **Mini-games:** 🎯 Cannon Blast (point-and-shoot arcade with difficulty/time options), 🧠 Fort Quiz Blitz (all-forts mixed quiz), ⏳ Timeline Challenge (drag forts into build-year order), and 👗 Dress-Up Time Traveler (dress men, women, and children in historically accurate outfits).
- **Classroom-friendly:** a "Reset scores" button lets you hand the device to the next student.

## 🚀 How to use

**Just open it:** download `index.html` and double-click it — it runs in any modern browser. An internet connection is needed for the map tiles and the live photos; without one, the app still works using an illustrated fallback and a fort-grid instead of the map.

**Host it free on GitHub Pages:**
1. Create a new public repository (e.g. `fort-explorers`) and upload `index.html`, `README.md`, and `LICENSE`.
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment," set **Source: Deploy from a branch**, choose your `main` branch and the `/ (root)` folder, and **Save**.
4. Wait a minute, then visit `https://<your-username>.github.io/<repo-name>/`.

## 🧩 Built with

- [Leaflet](https://leafletjs.com/) (BSD-2-Clause) for the map — loaded from cdnjs.
- [OpenStreetMap](https://www.openstreetmap.org/copyright) map tiles (© OpenStreetMap contributors, ODbL).
- The [Wikipedia / Wikimedia](https://www.mediawiki.org/wiki/API:Main_page) API for fort photos, loaded at runtime and linked back to their source pages.

No frameworks, no build tools — everything is plain HTML, CSS, and JavaScript in one file.

## 📚 Credits & data sources

- Historical facts are simplified for young readers and drawn from public sources such as Parks Canada and Wikipedia. This project is a fan-made educational resource and is **not affiliated with or endorsed by Parks Canada** or any government body.
- Fort photos are served from **Wikimedia Commons** and remain the property of their respective authors under their individual licenses; the app links to each photo's source page.
- Map data © OpenStreetMap contributors.

## ⚠️ Notes for re-use / heavy traffic

The app uses OpenStreetMap's public tile server and the Wikimedia API, which are free but have fair-use policies intended for modest traffic. For a small classroom or hobby site this is fine. If the app ever gets heavy public traffic, please switch to a dedicated map-tile provider (e.g. MapTiler, Mapbox, Stadia) and be mindful of Wikimedia's API etiquette.

## 📝 License

The **code** in this project is released under the MIT License — see [LICENSE](LICENSE). Third-party content (map tiles, photos) remains under its own licenses as noted above.

## 🙌 Contributing

Suggestions and fixes are welcome — open an issue or a pull request. Ideas for expansion: more forts, additional mini-games, or a French-language toggle (these are bilingual Canadian sites!).
