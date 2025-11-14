# Radiomaster Transmitter Control Explanation
This document explains the primary flight controls used in multirotors (drones) or RC vehicles when operated through a Radiomaster Transmitter.
Each stick on the transmitter corresponds to a specific movement depending on the mode (Mode 1 / Mode 2).\
Below is the explanation assuming the most common configuration: Mode 2.
The image of it \
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/a45a40ff736861e2a5cfab28c73908e9c271e176/WhatsApp%20Image%202025-11-14%20at%206.02.25%20PM.jpeg)

🎛️ 1. Throttle (Left Stick – Up/Down)
Function:
Controls the altitude or power of the motors.

Throttle Up:
Increases motor speed → drone rises.\
Throttle Down:
Decreases motor speed → drone descends.\
Use Case:
Maintaining a stable hover, ascending, or landing.\

🔄 2. Yaw (Left Stick – Left/Right)
Function:
Controls the rotation of the drone around its v![ertical axis.](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/afa4a86011914623a3a33efe5edecb0990a6b5a6/WhatsApp%20Image%202025-11-14%20at%206.09.48%20PM.jpeg)

Yaw Left:
Drone rotates counterclockwise.\
Yaw Right:
Drone rotates clockwise.\
Use Case:
Changing the direction the drone is facing while hovering.

↕️ 3. Pitch (Right Stick – Up/Down)
Function:
Controls the drone’s forward and backward tilt.\

Pitch Forward:
Drone moves forward.\
Pitch Backward:
Drone moves backward.\
Use Case:
Forward flight and reverse movement.\

↔️ 4. Roll (Right Stick – Left/Right)
Function:
Controls the drone’s side tilt.\

Roll Left:
Drone moves left.\
Roll Right:
Drone moves right.\
Use Case:
Left–right strafing, smooth turns, and balancing movement.

### 🧭 Additional Controls (Switches & Aux Channels)
Modern Radiomaster transmitters include multiple switches for additional functions:

AUX1 – ARM/DISARM Switch\
ARM: Activates the motors (ready to fly).\
DISARM: Stops motors immediately.\
AUX2 – Flight Mode Selector\
Angle Mode: Self-leveling, beginner friendly.\
Horizon Mode: Allows flips with leveling assistance.\
Acro Mode: Full manual control.\
AUX3 – Buzzer Switch\
Activates the “lost model alarm.”\
AUX4 – Turtle Mode\
Used in FPV quads to flip the drone upright after a crash.

### 📡 Transmitter Calibration Notes
When configuring a Radiomaster transmitter:

Ensure all sticks read 1000–1500–2000 values in Betaflight/Ardupilot.
Verify yaw is centered at 1500 when the stick is at rest.
Ensure throttle minimum is around 1000 to avoid accidental motor spin.

### ✔️ Summary

| Control | Stick Direction | Drone Movement |
| :--- | :--- | :--- |
| Throttle | Up/Down | Increase/Decrease altitude |
| Yaw | Left/Right | Rotate left/right |
| Pitch | Up/Down | Move forward/backward |
| Roll | Left/Right | Move left/right |\
# RF FREQUENCIES AND PROTOCALS:
* 2.4 GHz offers reliable long-range communication.
* 5 GHz provides faster data transmission over shorter distances.
* We also examined a LoRaWAN network diagram, highlighting how IoT sensor networks enable seamless data exchange.
* The session concluded with a focus on ExpressLRS (ELRS), an open-source, low-latency RC link known for its affordability and high performance — a strong alternative to premium systems like Crossfire.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/afa4a86011914623a3a33efe5edecb0990a6b5a6/WhatsApp%20Image%202025-11-14%20at%206.09.48%20PM.jpeg)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-0-Report-/273b39d19c7d8534c3a4907ce66c2f85cfdf3619/WhatsApp%20Image%202025-11-14%20at%206.09.48%20PM%20(1).jpeg)

