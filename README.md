# CADNote — Canadian Banknote Detection
<img width="1300" height="611" alt="270_20CanadianDollar_28" src="https://github.com/user-attachments/assets/3d807428-979d-40dd-95b1-34aeee3a8102" />


[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://derrickmirindi.github.io/AI-CAD-note-bank/) [![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-blue)](https://derrickmirindi.github.io/AI-CAD-note-bank/) [![Model](https://img.shields.io/badge/model-YOLOv8s-orange)](https://github.com/ultralytics/ultralytics)

Real-time detection of Canadian polymer banknotes ($5, $10, $20, $50, $100 CAD), running entirely in your browser. Built for research and educational purposes.

## Live Demo

**Try it now:** https://derrickmirindi.github.io/AI-CAD-note-bank/

## Features

- Real-time banknote detection via image, video, or live camera
- Banknote Assistant with design, theme, and security-feature info per denomination
- Accessibility: tactile identifier info for the visually impaired
- Live metrics: inference speed (ms), confidence scores, and IoU (NMS) controls

## How It Works

1. Provide an image or live camera feed of a banknote
2. A YOLOv8s model runs in-browser to identify the note
3. Select a detected denomination for an AI-generated explanation of its visual elements, history, and security features

## Tech Stack

<img width="2600" height="1300" alt="07_perclass_map_test" src="https://github.com/user-attachments/assets/d3a09b8a-0012-45f2-82a6-58663981b449" />


## Security

The product is not for sell. It was developed to advance education by Derrick Mirindi, David Sinkhonde and Frederic Mirindi. 
