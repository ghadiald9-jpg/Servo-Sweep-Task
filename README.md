# 4 Servo Motors Sweep Task

## Project Description
This project was implemented using **Tinkercad** and **Arduino Uno**. The objective is to control four servo motors to perform two sequential movements:

- Perform the **Sweep** movement for **2 seconds**.
- Move all servo motors to **90°** and hold their position.

---

## Components

- Arduino Uno
- 4 Servo Motors
- Jumper Wires
- Tinkercad Simulator

---

## Circuit Connections

| Servo Motor | Arduino Pin |
|--------------|------------|
| Servo 1 | D3 |
| Servo 2 | D5 |
| Servo 3 | D6 |
| Servo 4 | D9 |

**Power Connections**

- All Servo VCC pins → Arduino **5V**
- All Servo GND pins → Arduino **GND**

---

## Software

- Tinkercad
- Arduino IDE

---

## Program Description

1. The four servo motors perform the **Sweep** movement simultaneously.
2. The Sweep movement continues for **2 seconds**.
3. After 2 seconds, all servo motors move to **90°**.
4. The motors remain fixed at **90°** until the simulation stops.

---

## Expected Output

- Four servo motors move together using the Sweep motion.
- The movement lasts for 2 seconds.
- All servo motors stop and hold at **90°**.

---

## Files Included

- `Servo_Sweep_4Motors.ino`
- `README.md`
- `Servo_Task.mp4`

---

## Result

The task was completed successfully. All four servo motors performed the required Sweep movement for two seconds and then stopped at **90°**.