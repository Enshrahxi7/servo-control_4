# servo-control_4
This project controls four servo motors one by one, sweeping each from 0° to 180° to simulate a walking pattern, then resets all servos to a balanced 90° position.

# featues
 1- Each of the four servo motors performs a controlled angular sweep in sequence
 
 2- A one-second delay staggers the start time of each servo, creating a natural motion rhythm
 
 3- After completing its movement, every servo automatically resets to a neutral 90° position
 
 4- Clean and modular Arduino code structure designed for easy integration into robotic gait systems

# components
 • Arduino Uno
 • 4 × Standard servo motors (SG90 or similar)
 • Jumper wires
 • Breadboard (optional)
 
#  Connections
 • Servo Signal Pins: D4, D7, D8, D10
 • Servo Power: Connect all VCC (red) wires to the Arduino 5V pin
 • Servo Ground: Connect all GND (brown/black) wires to the Arduino GND
 
# How to Run the Project
 1. Launch a new Arduino circuit in Tinkercad.
 2. Drag in an Arduino Uno and connect 4 servo motors.
 3. Follow the wiring guide shown in [
 4. Upload the code from servo_sweep_control.ino into the code editor.
 5. Press Start Simulation — the servos will sweep one after another, then reset to 90°.
