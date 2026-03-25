# Tenure Run: Publish or Perish!

**Tenure Run** is a 3D browser-based endless runner game built in a single HTML file. It serves as a fun, satirical, and educational metaphor for the modern academic publishing landscape, specifically focusing on the concepts of Open Access, Article Processing Charges (APCs), Paywalls, and Preprints.

## 🎮 Play the Game
*(Add your GitHub pages link here once deployed: `https://[username].github.io/tenure-run/`)*

## 🧠 The Educational Metaphor
This game was designed for early Master's and first-year PhD students to introduce them to the realities of "Publish or Perish":

*   👩‍🔬 **The Player:** You are an early-career researcher trapped on the academic treadmill. You have to keep moving forward.
*   🧱 **Paywalls:** Traditional publishing locks knowledge behind expensive subscriptions. If you hit a paywall, your research gets stuck, and your run is over!
*   💸 **APCs (Article Processing Charges):** Some "Gold Open Access" journals charge researchers massive fees (often $3,000 to $10,000+) to publish. You have to jump over these to save your limited grant funding!
*   🟦 **Open Science Badges:** Represents open data and open materials. Collecting these yields citations (points).
*   💎 **Diamond Open Access:** The ideal publishing model! Free to read, and free for authors to publish. Collecting this gives you a shield that protects you from one mistake.
*   🔓 **Preprint Servers / Open Access:** The Orange Lock icon. Uploading your draft to a preprint server (like bioRxiv or arXiv) acts as a jetpack. It blasts you over the obstacles and bypasses the slow delays of traditional peer review.
*   😡 **Reviewer 2:** The notoriously overly-critical anonymous peer reviewer. If you stumble (by hitting an APC), Reviewer 2 gets right on your heels. 

## 🛠️ Technical Details
*   **Zero Assets:** The game does not require any external image or audio files. 
*   **Custom Pixel Art:** All graphics are defined as string arrays inside the JavaScript and drawn directly to the HTML5 `<canvas>` using `fillRect`.
*   **Web Audio API:** All sound effects (jumping, crashing, collecting coins) are synthesized dynamically in the browser.
*   **Pseudo-3D Engine:** Uses a custom perspective projection matrix (Mode 7 style) to convert 3D coordinates (X, Y, Z) into 2D screen space, creating the illusion of moving forward through a 3D world.

## 💻 How to Host
Since the game is contained entirely within `index.html`, you can host it for free in seconds using GitHub Pages:
1. Fork or clone this repository.
2. Go to **Settings > Pages**.
3. Set the source to the `main` branch.
4. Your game will be live in minutes!
