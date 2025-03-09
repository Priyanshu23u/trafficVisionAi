# AI-Based Traffic Management System

## Overview
The AI-Based Traffic Management System uses deep learning techniques, specifically YOLOv7, to detect and manage vehicle traffic efficiently. The system analyzes real-time traffic data to optimize signal timings and improve traffic flow.

## Features
- **Vehicle Detection**: Uses YOLOv7 for accurate detection of vehicles.
- **Dynamic Traffic Control**: Adjusts signal timings based on real-time traffic density.
- **Simulation**: Provides a simulated environment to test traffic flow improvements.

## Installation
### Prerequisites
- Python 3.x
- OpenCV
- NumPy
- YOLOv7 weights and configuration files

### Setup
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd AI-based-Traffic-Management-System
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Download YOLOv7 weights and place them in the project directory.

## Usage
1. Run the vehicle detection script:
   ```sh
   python vehicle_detection.py
   ```
2. Run the traffic simulation:
   ```sh
   python simulation.py
   ```

## Files Overview
- `vehicle_detection.py`: Implements YOLOv7-based vehicle detection.
- `signal_time.py`: Manages dynamic traffic signal timing.
- `simulation.py`: Simulates traffic scenarios.
- `yolov7.cfg` & `yolov7.weights`: Configuration and pre-trained weights for YOLOv7.
- `coco.names`: List of object classes recognized by YOLO.
