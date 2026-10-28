# MatchLab: Startup Hiring Intelligence

An independent interactive prototype exploring explainable candidate ranking for early-stage startup hiring.

## Features
- Three fictional startup hiring scenarios and six synthetic candidate profiles
- Live re-ranking as skills, preferences, and availability weights change
- Transparent score breakdowns and hard-constraint warnings
- Copyable match summaries

## Run locally
Open `index.html` in a modern browser. No dependencies, build tools, API keys, or server required.

## How scoring works
The demo uses a deterministic weighted heuristic combining skills overlap, work arrangement and salary preferences, and availability and activity. Weights are normalized before scoring. Scores are not calibrated probabilities, trained ML predictions, or validated hiring outcomes.

## Limitations
All data is synthetic. This is not intended for actual hiring decisions. A real system would need privacy controls, consent, fairness evaluation, accessibility review, and rigorous validation.

