# Mediverse-AI: Requirements
Offline, rule-based health guardian. No Gemini, OpenAI or any model API; no account; data stays in the browser.

## Functional
- FR1 Profile (age, sex, height, weight, smoker, family history) and BMI calculator
- FR2 Reading log: heart rate, blood pressure, glucose, SpO2, temperature, weight
- FR3 Blood pressure analyser (normal, elevated, stage 1, stage 2, crisis, low)
- FR4 Local rule engine with severity, points and a recommendation for each rule
- FR5 Overall health risk score 0-100 and dashboard
- FR6 Trend charts (canvas) with rising/falling summary
- FR7 Medical report analyser: .txt/.csv or pasted text matched to reference ranges for 11 lab tests
- FR8 Keyword symptom checker with emergency detection
- FR9 Medicine tracker with adherence % and missed-dose alert (more than 3 days)
- FR10 Emergency guide, call button, location display
- FR11 History table, JSON export, clear data

## Rules (examples)
- Heart rate > 100 -> tachycardia alert; BP >= 140/90 -> hypertension; BMI >= 30 -> obesity; glucose >= 126 -> diabetic range; SpO2 < 92 -> emergency prompt; no dose for > 3 days -> adherence alert

## Non-functional
- Works offline from one HTML file; responsive; dark/light; keyboard focus visible; no network calls
- General information only, not a diagnosis

## Limits
- No natural-language reasoning, no PDF/photo OCR, no wearable or live health data integrations
