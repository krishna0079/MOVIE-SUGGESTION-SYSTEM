# MOVIE-SUGGESTION-SYSTEM
A premium, responsive movie discovery web app featuring a glassmorphism UI, real-time OMDB API search, smart streaming badges, and a curated Top 20 Directors Spotlight. Built with Vanilla JS.
# 🎬 Ultimate Cinema UI (Movie Finder)

A premium, highly responsive movie and TV show discovery web application. Built with vanilla HTML, CSS, JavaScript, and powered by the OMDB API, this project features a modern glassmorphism UI, an animated gradient background, and a dedicated spotlight for the world's greatest directors.

## ✨ Key Features

* **Advanced Search & Autocomplete:** Real-time search suggestions as you type, complete with movie poster thumbnails.
* **Top 20 Directors Spotlight:** A dedicated UI tab showcasing 20 legendary filmmakers (e.g., Christopher Nolan, Hayao Miyazaki, Martin Scorsese) with custom profile pictures. Clicking a director instantly fetches their curated masterpieces.
* **Deep Linking:** Click on a director's name inside any movie's detail modal to instantly search the database for more films by that creator.
* **Modern UI/UX:** * Animated diagonal gradient background.
  * Glassmorphism sticky header.
  * Skeleton loading animations while fetching API data.
  * Custom scrollbars and hover-state 3D card pop-outs.
* **Simulated OTT Integrations:** Automatically generates branded streaming badges (Netflix, Prime Video, Hulu, Disney+, Max) for a realistic platform feel.
* **Fully Responsive:** Perfectly adapts to mobile devices, tablets, and large desktop screens using CSS Grid and tailored media queries.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Grid, Flexbox, Animations), Vanilla JavaScript (ES6+)
* **API:** [OMDb API](http://www.omdbapi.com/) (Open Movie Database)
* **Assets:** Custom local portrait images and dynamic fallbacks via `ui-avatars.com`.

## 🚀 How to Run Locally

1. **Download the Files:** Ensure `index.html` and all associated director image files (`photo_*.jpg`) are saved in the exact same folder.
2. **API Key Setup:** * The project currently uses a free OMDB API key. 
   * If search limits are reached (1,000 requests/day), get a free key from [omdbapi.com](http://www.omdbapi.com/apikey.aspx) and replace the `API_KEY` variable in the `<script>` section of `index.html`.
3. **Launch:** Simply double-click `index.html` to open it in any modern web browser. No server or node modules required!

## 📁 File Structure Note

For the Director Spotlight to work perfectly, the following local images must remain in the root directory alongside `index.html`:


## 🤝 Acknowledgments

* Movie data and posters provided by the **OMDb API**.
* Fallback profile avatars generated via **UI Avatars**.
