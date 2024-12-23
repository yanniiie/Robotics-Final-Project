# Arduino Obstacle Avoidance Line Follower Robot

## Description
This project involves building an obstacle-avoidance line-following robot using Arduino. The robot uses ultrasonic and infrared sensors to navigate its environment, avoiding obstacles and following a designated path. It employs a combination of object detection, servo control, and motor movements to achieve autonomous navigation.

**Key Features:**
- Obstacle detection using an HC-SR04 ultrasonic sensor.
- Line-following capabilities using infrared (IR) sensors.
- Two motor system for movement.
- Servo motor for directional scanning to find clear paths.

---

## Setup and Usage

### Hardware Requirements
- 1x Arduino board (e.g., Arduino Uno)
- 1x L293D Motor driver
- 1x HC-SR04 ultrasonic sensor
- 2x Infrared sensors
- 2x DC motors
- 1x Servo motor
- Connecting(jumper) wires
- Power source (e.g., 2x batteries 3.7V)

### Circuit Connections
1. **Ultrasonic Sensor (HC-SR04):**
   - TRIG pin to Arduino `A5`
   - ECHO pin to Arduino `A4`
2. **Infrared Sensors:**
   - Left sensor to Arduino `A1`
   - Right sensor to Arduino `A2`
3. **Motors:**
   - Connect motor 1 to channel 1 of the motor driver.
   - Connect motor 2 to channel 2 of the motor driver.
4. **Servo Motor:**
   - Connect servo signal pin to Arduino pin `10`.
5. Power connections: Ensure proper voltage and current supply to the motors and sensors.

### Software Requirements
- Install the **AFMotor** library for motor control.
- Install the **NewPing** library for ultrasonic sensor functionality.
- Install the **Servo** library (pre-installed with Arduino IDE).

### Installation
1. Clone this repository or download the code as a ZIP file and extract it.
2. Open the `ObstacleAvoidance.ino` file in the Arduino IDE.
3. Verify the code to ensure there are no errors.
4. Upload the code to your Arduino board.

---

## How It Works
1. The robot uses IR sensors to follow a line on the ground.
2. The HC-SR04 ultrasonic sensor continuously scans for obstacles.
3. If an obstacle is detected, the servo motor rotates left and right to measure distances in both directions.
4. Based on the distance data, the robot chooses the path with fewer obstacles and continues to move forward.

---

## Project Purpose and Outcomes
**Purpose:** 
The goal of this project is to provide hands-on experience with Arduino-based robotics, sensor integration, and autonomous navigation algorithms.

**Outcomes:** 
- A working prototype of an autonomous robot that can follow a line and avoid obstacles.
- Enhanced understanding of motor control, sensor integration, and decision-making in robotics.

---

## Future Improvements
- Add additional sensors for improved obstacle detection.
- Implement PID control for smoother line-following performance.
- Introduce Bluetooth or Wi-Fi connectivity for remote control and monitoring.

---

## License
This project is open-source under the MIT License. Feel free to use, modify, and share!

---

## Contact
For any questions or contributions, please reach out via GitHub.


```Circuit Diagram```

![photo_5426849190799075003_y](https://github.com/user-attachments/assets/82371155-6c3a-43cf-a8af-b2e98c73bdbd)








