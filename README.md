# TrafficVisionAI

TrafficVisionAI is an AI-powered traffic management system that utilizes **YOLOv7** for vehicle detection and an adaptive signal control algorithm to optimize traffic flow.

## Features
- **Real-time Vehicle Detection**: Uses YOLOv7 to detect cars, buses, and trucks in images.
- **Adaptive Traffic Signal Control**: Dynamically adjusts signal timings based on vehicle count.
- **Traffic Flow Simulation**: A simulation using Pygame to visualize traffic movements.

## Installation

1. **Clone the Repository**:
   ```sh
   git clone <repository-url>
   cd trafficVisionAi
   ```
2. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

### 1. Run Vehicle Detection
Ensure you have YOLOv7 weights (`yolov7.weights`) and configuration (`yolov7.cfg`). Place test images inside `test_images/`.
```sh
python vehicle_detection.py
```

### 2. Run Traffic Signal Control
```sh
python signal_time.py
```
Enter the vehicle count when prompted, and the system will adjust the signal timings accordingly.

### 3. Run Traffic Simulation
```sh
python simulation.py
```
This launches a visual simulation of traffic movements and signal changes.

## Files & Directories
- `vehicle_detection.py` - Detects vehicles using YOLOv7.
- `signal_time.py` - Controls traffic lights based on vehicle count.
- `simulation.py` - Runs a traffic simulation.
- `yolov7.cfg`, `yolov7.weights` - YOLOv7 model files.
- `coco.names` - Class labels for object detection.

## Dependencies
- OpenCV
- NumPy
- Pygame
- YOLOv7 (pre-trained weights)

## Future Improvements
- Real-time video processing for live traffic monitoring.
- Integration with IoT-enabled traffic lights.


