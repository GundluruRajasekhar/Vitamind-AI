# Mediverse-AI
A fully offline health guardian built with a transparent rule engine. No API key, no server.

## Run
Open `index.html` in any browser, or deploy the folder to GitHub Pages or Vercel.

## Features
BMI calculator, blood pressure analyser, health risk score, reading history, trend charts, medical report analyser (pasted or .txt/.csv lab values), symptom checker, medicine adherence alerts, emergency guide with location.

## How the AI works
Explicit if-then rules (for example heart rate above 100 raises a tachycardia alert) add points to a 0-100 risk score and attach recommendations. Every decision is explainable. It does not use a language model, so it cannot reason about free-form questions beyond keyword matching.

## Privacy
All data is stored in your browser's localStorage. Nothing is sent anywhere.

## Disclaimer
General information only; not medical advice or diagnosis.

## Files
index.html, requirements.md, readme.md, tasks.md
