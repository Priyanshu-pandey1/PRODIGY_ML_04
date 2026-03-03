# Air Canvas: Real-Time Virtual Drawing System 🎨

This repository contains my submission for **Task 04** of the **Machine Learning Internship** at **Prodigy InfoTech**. The project implements an "Air Canvas" application that allows users to draw in a digital space using hand gestures.

## 🚀 Project Overview
The Air Canvas project leverages **Computer Vision** to track hand movements and map them to a virtual drawing interface. It goes beyond simple gesture recognition by implementing real-time coordinate tracking and dynamic mode switching.

### Key Features:
- **Real-Time Tracking:** Uses the index finger as a virtual pen for seamless drawing.
- **Gesture-Based Selection:** A two-finger gesture (Index + Middle) triggers "Selection Mode" to change colors or use the eraser.
- **Dual-Layer Rendering:** Blends a live camera feed with a digital drawing mask using OpenCV bitwise operations.
- **Canvas Controls:** Includes a "Clear" function and multiple color palettes (Purple, Blue, Green, Yellow).

## 🛠️ Technical Stack
- **Python 3.12**
- **MediaPipe:** Used for high-speed, 21-point hand landmark extraction.
- **OpenCV:** Handles video processing, UI overlays, and frame masking.
- **NumPy:** Manages the drawing canvas array and bitwise transformations. 

[Image of an Air Canvas project interface showing hand tracking and virtual drawing]

## ⚙️ Installation & Usage

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Priyanshu-pandey1/PRODIGY_ML_04.git](https://github.com/Priyanshu-pandey1/PRODIGY_ML_04.git)
   cd PRODIGY_ML_04
