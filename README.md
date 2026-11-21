# Pranjali Weds Manish — Wedding Invitation Website

## Project Structure
- `index.html` — Complete wedding invitation page
- `assets/images/` — Palace artwork, Ganesha filigree idol, couple photo, event medallions, and vintage car illustrations
- `assets/audio/din_shagna_da.mp3` — Background wedding song (auto-plays and can be paused via the top-right button)

## Run Locally
1. **Extract** `pranjali_weds_manish_website.zip` to a folder on your computer.
2. **Option A — Quick open:** Double-click `index.html` to open it in Chrome, Edge, or Safari.
3. **Option B — Local server (recommended for best audio & mobile testing):**
   - **Python 3:** Open a terminal inside the extracted folder and run:
     ```bash
     python3 -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.
   - **VS Code:** Open the folder in VS Code, right-click `index.html`, and select **Open with Live Server**.
   - **Node.js:** Run `npx serve .` in the extracted folder and open the printed local URL.
