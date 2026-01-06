# GHOST_PROTOCOL // DUCHENNE_V6

Real-time emotion detection using facial landmark vectors with optional AI enhancement.

## Features

- **MediaPipe FaceMesh** - 468 landmark tracking with 13 key points for emotion inference
- **FACS-Based Analysis** - Detects joy, anger, sadness, fear, disgust, contempt using geometric vectors
- **Duchenne Detection** - Identifies genuine smiles via eye-squint + smile combination
- **5-Second Assessment** - Aggregated emotional profiling with stability scoring
- **Mistral Vision AI** - Optional semantic analysis for enhanced accuracy

## Quick Start

1. Open `index.html` in a modern browser (Chrome/Edge recommended)
2. Allow camera access when prompted
3. Your emotional profile displays in real-time

## Assessment Mode

1. Click **"START ASSESSMENT (5s)"**
2. Express naturally during capture
3. View breakdown: dominant emotion, confidence, stability score
4. Export results as JSON

## Mistral AI (Optional)

1. Get API key from [mistral.ai](https://mistral.ai/)
2. Enter key in the input field (auto-saved)
3. Toggle **MISTRAL AI ENHANCEMENT** on
4. Run assessment for semantic insights

## Tech Stack

- MediaPipe FaceMesh
- Vanilla HTML/CSS/JS
- Mistral Pixtral API (optional)
