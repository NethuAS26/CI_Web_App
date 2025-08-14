🧠 Personality Predictor (Static Web App)

A beautiful, responsive single‑page app that predicts personality type (Extrovert/Introvert) using a lightweight client‑side algorithm. Deployable on GitHub Pages.


🌟 Features
	•	AI‑style client‑side analysis (no backend)
	•	Responsive, mobile‑first UI with gradients/animations
	•	Instant results with confidence score
	•	Privacy‑first: all processing in the browser

📁 Project Structure

web-app/
├── index.html   # App (HTML, CSS, JS in one file)
└── README.md    # This document

📊 How It Works (Brief)

Analyzes 7 inputs:
	1.	Time spent alone  2) Stage fear  3) Social events/month
	2.	Going outside/week  5) Drained after socializing
	3.	Friends circle size  7) Social post frequency

Algorithm (simplified):
	•	Normalize features to 0–1
	•	Apply weighted scoring
	•	Compute probability‑style confidence

🚀 Quick Start
	1.	Open web-app/index.html in a browser.
	2.	Fill the form → Analyze My Personality.
	3.	View result & confidence.

🌐 Deploy (GitHub Pages)
	1.	Push project to GitHub.
	2.	Settings → Pages
	•	Source: Deploy from a branch
	•	Branch: main (or default) • Folder: / (or /web-app)
	3.	App URL: https://<username>.github.io/<repo>/

🎨 Customize

Edit gradients in the <style> section of index.html:

/* Main */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
/* Extrovert */
background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
/* Introvert */
background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);


🧪 Testing

Try these examples:
	•	Extrovert: Alone 2h • No stage fear • 8 events/mo • Outside 5/wk • Not drained • 20 friends • 5 posts/wk
	•	Introvert: Alone 6h • Stage fear • 2 events/mo • Outside 2/wk • Drained • 5 friends • 1 post/wk

🛠 Tech
	•	HTML5 for structure
	•	CSS3 for styling/animations
	•	JavaScript for scoring & UI

🔒 Privacy
	•	No data storage or tracking
	•	100% client‑side

❓ Support (Basics)
	•	If GitHub Pages doesn’t load: check Settings → Pages folder/branch
	•	If results seem off: model is simplified for demo/education
	•	Check browser console for errors


