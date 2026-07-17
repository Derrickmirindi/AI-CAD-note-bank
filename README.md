# CADNote — Canadian Banknote Detection

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://derrickmirindi.github.io/AI-CAD-note-bank/) [![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-blue)](https://derrickmirindi.github.io/AI-CAD-note-bank/) [![Model](https://img.shields.io/badge/model-YOLOv8s-orange)](https://github.com/ultralytics/ultralytics)

Real-time detection of Canadian polymer banknotes ($5, $10, $20, $50, $100 CAD), running entirely in your browser. Built for research and educational purposes.

## Live Demo

**Try it now:** https://derrickmirindi.github.io/AI-CAD-note-bank/

The app is hosted on GitHub Pages and is publicly accessible 24/7, 7 days a week.

## Features

- Real-time banknote detection via image, video, or live camera
- Banknote Assistant with design, theme, and security-feature info per denomination
- Accessibility: tactile identifier info for the visually impaired
- Live metrics: inference speed (ms), confidence scores, and IoU (NMS) controls

## How It Works

1. Provide an image or live camera feed of a banknote
2. A YOLOv8s model runs in-browser (ONNX Runtime Web) to identify the note
3. Select a detected denomination for an AI-generated explanation of its visual elements, history, and security features

## Tech Stack

- Model: YOLOv8s (exported to ONNX)
- Runtime: ONNX Runtime Web (WebAssembly)
- Frontend: Vanilla HTML/CSS/JavaScript
- AI Assistant: Google Gemini via a Cloudflare Worker proxy
- Deployment: GitHub Pages (static hosting)

## Security

The Gemini API key is never committed to this repository. All AI requests are proxied through a Cloudflare Worker, where the key is stored securely as a server-side secret. No API keys are present in the client-side code.
