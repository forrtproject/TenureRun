Tenure Run: Publish or Perish!
Tenure Run is a browser-based endless runner game built entirely in a single HTML file. It serves as a fun, satirical, and educational metaphor for the modern academic publishing landscape, specifically focusing on the pressure to publish, Questionable Research Practices (QRPs), Article Processing Charges (APCs), and Open Science.

🧠 The Educational Metaphor
This game was designed for early Master's and first-year PhD students to introduce them to the realities of the "Publish or Perish" treadmill. You run across an endless manuscript, automatically passively writing papers, but must navigate a treacherous landscape to survive:

👩‍🔬 The Player & Leveling Up: You are an early-career researcher trapped on the academic treadmill. As you collect publications, you level up from a PhD Student all the way to a Tenured Professor, changing your appearance as you rank up.
🧱 Paywalls: Traditional publishing locks knowledge behind massive barriers. If you hit a paywall, your research gets stuck, and your run is instantly over!
<strong style="color:red;">$</strong> APCs (Article Processing Charges): Some "Gold Open Access" journals charge researchers massive fees (often $3,000 to $10,000+) to publish. You have to jump over these to save your limited funding.
📄 Papers: Standard research outputs. Collect them to increase your publication count by +1.
🟦 Open Data Badges: Representing robust Open Science practices. Sharing data is highly valuable—collecting these yields +2 publications.
📜 Grants: Research funding! Collecting a grant protects you from the next 3 APC fees you hit.
🟪 p-Hacking: The giant purple 'p'. A satirical take on QRPs. Grabbing this drastically increases your speed (allowing you to gain passive publications much faster), but offers no protection against Paywalls or APCs. It represents the desperate, frantic, and risky shortcuts researchers sometimes take when under pressure.
😡 Reviewer 2: The notoriously overly-critical anonymous peer reviewer. If you stumble (by hitting an APC without a grant), Reviewer 2 gets right on your heels!
🌍 Advocating for Change in Academia
While the game is a comical take on the hyper-competitive academic system, the underlying issues are real. Research assessment currently heavily prioritizes quantity (number of publications) and prestige (journal impact factors) over actual research quality.

However, the system is changing. Researchers and institutions worldwide are pushing for fairer, more qualitative evaluations:

SF DORA (San Francisco Declaration on Research Assessment): A global initiative to halt the use of journal-based metrics (like Journal Impact Factors) to evaluate individual researchers. Anyone can sign DORA!
CoARA (Coalition for Advancing Research Assessment): A coalition of institutions committing to systemic reform of research assessment.
FORRT (Framework for Open and Reproducible Research Training): An excellent community to join if you are concerned with Open Science, reproducibility, and social justice in higher education.
(Note: This game is an independent educational project and is not officially affiliated with DORA, CoARA, or FORRT).

🛠️ Technical Details
Zero External Assets: The game does not require any external image or audio files to run.
Custom Pixel Art: All graphics (the player sprites, badges, and items) are defined as string arrays inside the JavaScript and drawn directly to the HTML5 <canvas> using fillRect.
Web Audio API: All sound effects (jumping, crashing, leveling up) and the dynamic, adaptive background music are synthesized live in the browser using oscillators.
Mobile Optimized: The game scales dynamically to fit any screen size and features full touch/swipe controls for mobile play.
