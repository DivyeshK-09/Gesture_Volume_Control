
# Gesture Volume Control

## Overview
A computer vision-based system that controls system volume using hand gestures.

## Objective
- Enable touchless control
- Explore real-time hand tracking

## Approach
- Hand detection using computer vision
- Distance between fingers mapped to volume level

## Tech Stack
- Python
- OpenCV
- MediaPipe
- Pycaw (system volume control)

## Workflow
1. Capture webcam input
2. Detect hand landmarks
3. Measure finger distance
4. Map to system volume

## Results
- Real-time gesture-based control
- Smooth interaction

## Challenges
- Lighting conditions
- Detection accuracy

## Future Improvements
- Multi-gesture support
- Gesture customization

## How to Run
```bash
python main.py
