# NVIDIA NIM-based DMS & OMS

A low-latency multimodal pipeline for driver monitoring using:
- YOLO (object detection)
- ROI extraction
- LLaVA via NVIDIA NIM (multimodal reasoning)

## Features
- Detects driver distraction (phone usage, gaze)
- Uses ROI-based inference for efficiency
- Hybrid edge + cloud architecture

## Tech Stack
- Python, OpenCV
- Ultralytics YOLO
- NVIDIA NIM APIs
- FastAPI (optional)

## Architecture
Video → YOLO → ROI → NIM (LLaVA) → Decision Engine
