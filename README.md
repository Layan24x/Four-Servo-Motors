# Four-Servo-Motors
Four Servo Motors Sequential Movement using Arduino (Tinkercad)
# Four Servo Motors Sequential Movement using Arduino (Tinkercad)

## Project Description
This project demonstrates controlling four servo motors using an Arduino Uno in Tinkercad.

The program performs two sequential movements:

1. All four servo motors move in a Sweep motion (0° → 180° → 0°).
2. The sweep motion continues for 2 seconds only.
3. After 2 seconds, all servo motors stop and hold their position at 90°.

---

## Components Used

- Arduino Uno
- 4 × Servo Motors (SG90)
- Breadboard
- Jumper Wires

---

## Circuit Connections

| Servo Motor | Signal Pin | Power | Ground |
|-------------|------------|--------|--------|
| Servo 1 | D3 | 5V | GND |
| Servo 2 | D5 | 5V | GND |
| Servo 3 | D6 | 5V | GND |
| Servo 4 | D9 | 5V | GND |

All servo motors share the same 5V and GND connections.

---

## Program Behavior

- Initialize four servo motors.
- Perform a synchronized Sweep movement for 2 seconds.
- Stop all servos at exactly 90°.
- Keep the motors fixed at 90° indefinitely.

---

## Files

- four_servo_motors_code.ino → Arduino source code.
- README.md → Project documentation.

---

## Simulation

This project was designed and tested using Tinkercad Circuits.
