# Quadcopter Flight Dynamics Lab

An interactive, self-contained browser-based teaching lab developed for AGUIRRETECH and college physical science / UAV instruction. Includes six instructional lessons and a Basic Flight Simulator.

## Launch

Open [the Flight Dynamics Lab](https://aguirretech.github.io/quadcopter-flight-dynamics-lab/) after GitHub Pages has been enabled, or download `index.html` and open it locally in a modern browser. No installation or internet connection is needed for the local version.

## Learning modules

1. Motor Mixer: motor thrust and pitch, roll, yaw, climb and descent
2. Tilt & Thrust: thrust vectors and horizontal acceleration
3. Stabilization: Angle versus Acro/Rate control
4. Sensor Feedback: gyroscope-based corrections
5. Motor Failure: motor allocation and control limitations
6. Mode 2 Controller & PID Laboratory: transmitter inputs and PID feedback
7. Basic Flight Simulator: DJI-style and FPV flight practice

## Basic Flight Simulator controls

Choose the **Control Method** selector and click the adjacent **?** icon for instructions.

- **Keyboard + Mouse (default):** W/S throttle, A/D yaw, mouse drag on right stick for pitch/roll.
- **Keyboard Only:** W/S throttle, A/D yaw, arrow keys for pitch/roll.
- **Game Controller:** standard dual-stick mapping, left throttle/yaw, right pitch/roll. Verify hardware mapping.
- **Touchscreen:** use two fingers to drag both sticks independently.

FPV throttle holds its position when released; pitch, roll, and yaw return to center.

## Professor review

Feedback is welcome on scientific accuracy, teaching sequence, clarity of Mode 2 controls, FPV versus stabilized flight behavior, and accessibility. The simulator uses simplified physics and is intended for conceptual education, **not** flight certification or real-world aircraft training.

## Project notes

- Version: **2.5.1**, professor-review candidate.
- Single-file HTML application; no external runtime dependencies.
- The simulation and motor visualizations are educational approximations.
- Developed for AGUIRRETECH, *Where Safety, Service, and Integrity Take Flight.*
