# Sumil Lucky Draw

A visually stunning, interactive digital lucky draw web application.

## Features
- **Dynamic Animations**: Continuous floating cards, pulsing glows, 3D rotating podiums, and an animated spinning wheel.
- **Particle Effects**: A fully localized falling celebration (confetti shower) over highlighted elements.
- **Interactive UI**: Cards gracefully zoom, glow, and change layout on hover.
- **Audio Integration**: Dynamic background music and applause tracks upon interaction.
- **Premium Design**: Dark mode aesthetic with custom gold, silver, and bronze gradients and drop-shadow styling.

## Project Structure

This project follows a standard static web layout:

- `index.html` - The main dashboard and entry point.
- `prize.html` - The detailed prize reveal page.
- `assets/`
  - `images/` - Core imagery like logos, banners, and wheels.
  - `prizes/` - Individual prize item pictures.
  - `audio/` - Background music and sound effects.
  - `data/` - Qualifier data for the draw logic.
- `js/`
  - `audio.js` - JavaScript handling audio controls and synchronization.
- `tools/` - Development tools and layout python scripts (not required for production).

## How to Run Locally

You don't need a build system to run this! It's pure HTML, CSS, and JS. 

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Sumil-Lucky-Draw.git
   ```
2. **Start a local HTTP server** (required for Javascript modules and CORS):
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   ```
   Or using Node.js:
   ```bash
   npx serve .
   ```
3. **Open your browser** and navigate to `http://localhost:8000`.

## Design Notes
The interface relies heavily on CSS `mix-blend-mode` for seamless background removal of imported images and `filter: drop-shadow` to create the ethereal glowing effect on the prize cards and podium elements. Wait times for animations are synchronized to ensure the page always feels alive without being overwhelming.
