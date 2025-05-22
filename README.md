# MultiPerson Tracking and Path Overlay

This project is an end-term assignment for a Computer Vision course. It focuses on **tracking multiple people** in a custom one-minute video, **drawing real-time path overlays** using distinct colors for each individual, even when paths intersect or identities switch.

## 📽️ Project Description

- 🧍 Tracks at least **3 individuals** walking and crossing paths.
- 🔴🟢🔵 Draws each person’s walking path with a **distinct colored line** (e.g., Red, Green, Blue).
- 🔁 Maintains **identity consistency**, even during overlaps.
- 🎥 Outputs an annotated video preserving the original scene and overlaying the visual paths.

## 🚀 Features

- Real-time object tracking using YOLO-based detectors.
- Identity association for multiple targets (e.g., SORT/DeepSORT).
- Trajectory visualization.
- Exported annotated video.

