# TrafficVisionAI

TrafficVisionAI is a traffic simulation tool designed to model vehicle movement and traffic signal management at an intersection. The simulation uses Pygame for visualization and incorporates configurable signal timings and vehicle behavior.

## Features
- Simulates traffic signals with configurable timing
- Supports multiple vehicle types (cars, buses, bikes, etc.)
- Uses Pygame for interactive visualization
- Adjustable simulation duration

## Installation
Ensure you have Python installed, then install the required dependencies:

```sh
pip install pygame
```

## Usage
Run the simulation script:

```sh
python simulation.py
```

## Configuration
Modify `simulation.py` to adjust traffic signal timings and vehicle behavior:
- `defaultRed`, `defaultYellow`, `defaultGreen` control signal durations.
- `simTime` sets the total simulation time.
- Vehicle-specific timing can be adjusted in the script.



