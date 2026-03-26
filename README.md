# Tenure Run: Publish or Perish!

🎮 **PLAY THE GAME HERE:** [t1p.de/tenurerun](https://t1p.de/tenurerun)

**Tenure Run** is a browser-based endless runner game built entirely in a single HTML file. It serves as a fun, satirical, and educational metaphor for the modern academic publishing landscape, specifically focusing on the pressure to publish, Questionable Research Practices (QRPs), Article Processing Charges (APCs), and the Open Science movement.

---

## 🎮 How to Play
You are an early-career researcher trapped on the academic treadmill (a giant, scrolling manuscript). You automatically write pages over time, but you must navigate a treacherous landscape to survive.

*   **Controls:** Swipe Left/Right (or Arrow Keys) to switch lanes. Swipe Up (or Up Arrow / Spacebar) to jump. 
*   **Goal:** Collect 15 Pages to generate 1 Publication. Gain publications to level up!
*   **Lives:** You start with 3 lives (❤️❤️❤️). Hitting obstacles without protection will cost you a life. Leveling up grants you +1 bonus life.

### 🟢 TO COLLECT (Run into these)
*   📄 **Pages:** Gives +2 Pages.
*   🟦 **Open Data Badges:** Sharing data is highly valuable! Gives +5 Pages.
*   📜 **Grants:** Research funding! Collecting a grant safely pays for your next 3 APC fees (Grants are stackable).
*   🛡️ **Preregistration (Red Badge):** Protects you from the dangers and penalties of p-hacking.
*   🟪 **p-Hacking (Purple 'p'):** A satirical take on Questionable Research Practices. Grabbing this drastically increases your speed (allowing you to gain passive pages much faster), but offers *no* protection against obstacles unless you Preregistered!

### 🔴 TO AVOID (Jump over these)
*(Note: If you jump, you will safely fly over these obstacles, but you will also fly over any good items!)*
*   🧱 **Paywalls:** Traditional publishing locks knowledge away. These massive walls block 2 out of the 3 lanes. You must switch to the open lane or jump over them.
*   📚 **Teaching & Grading:** Overflowing "To-Grade" trays and Classroom Chalkboards that block your research path. 
*   <strong style="color:red;">$</strong> **APCs (Article Processing Charges):** Some "Gold Open Access" journals charge researchers massive fees to publish. Hitting this *will* give you 1 Publication, but it will **drain 1 Life** unless you have a Grant to pay for it!

---

## 🎓 The Academic Hierarchy (Leveling Up)
As you publish, you will rank up and your character sprite will change:
1.  **PhD Student:** (0 Pubs)
2.  **Postdoc:** (3 Pubs) 
3.  **Lecturer:** (9 Pubs)
4.  **Assistant Professor:** (21 Pubs)

---

## 🌍 Advocating for Change in Academia
While the game is a comical take on the hyper-competitive academic system, the underlying issues are real. Research assessment currently heavily prioritizes quantity (number of publications) and prestige (journal impact factors) over actual research quality. 

However, the system is changing. Researchers and institutions worldwide are pushing for fairer, more qualitative evaluations:
*   **[CoARA (Coalition for Advancing Research Assessment)](https://coara.eu/):** A global coalition of institutions committing to systemic reform of research assessment. 
*   **[SF DORA (San Francisco Declaration on Research Assessment)](https://sfdora.org/):** An initiative to halt the use of journal-based metrics to evaluate individual researchers. Check out the [SF DORA National and International Initiatives](https://sfdora.org/national-and-international-initiatives-discussion-group). *Anyone can sign DORA!*
*   **[FORRT (Framework for Open and Reproducible Research Training)](https://forrt.org/):** An excellent community advocating for Open Science, reproducibility, and social justice in higher education. **[Click here to join FORRT's open Slack channel!](https://join.slack.com/t/forrt/shared_invite/enQtODMwODI0OTk4ODgzLTM0ZTQ3NDk5MzA1ZjBmNWJjYTVlN2Y2YTk0ZTJhYTY5NDliMDYzMjg2MWE0ZDRhOTY0ZDY3OTRlNDA4ODQ3NjQ)**

*(Note: This game is an independent educational project and is not officially affiliated with DORA, CoARA, or FORRT).*

---

## 🛠️ Technical Details
*   **Zero External Assets:** The game does not require any external image or audio files to run. Everything is generated dynamically.
*   **Custom Pixel Art:** All graphics are defined as string arrays inside the JavaScript and drawn directly to the HTML5 `<canvas>`.
*   **Progressive Web Audio:** Features a custom SNES-style ragtime soundtrack composed entirely in the browser using the `AudioContext` API. The music progressively builds as you level up (Melody -> Bassline -> Drums), changes dynamically when you p-hack, and increases tempo as the game speeds up!
*   **Mobile Optimized:** The game scales dynamically to fit any screen size and features full touch/swipe controls for mobile play.

---

## 💻 How to Host Your Own Copy
Since the game is contained entirely within `index.html`, you can host it for free in seconds using GitHub Pages:
1. Fork or clone this repository.
2. Go to your repository **Settings > Pages**.
3. Set the source to the `main` branch.
4. Your game will be live in minutes!
