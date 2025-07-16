# Servo Motor Control using 555 Timer and Arduino

This project demonstrates two different methods to control a servo motor:

1. **Without Arduino:** Using a 555 Timer IC configured in astable mode to generate PWM signals.
2. **With Arduino:** Using Arduino's PWM output to control the servo with precise angles.

##  Objective

To explore and compare servo control using a microcontroller (Arduino) and a simple timer IC (555 Timer) — understanding PWM generation in both hardware and software forms.

---

##  Hardware Used

- Servo Motor
- 555 Timer IC (NE555)
- Arduino UNO (for version 2)
- BC547 Transistor
- Resistors (various values: 4.7Ω, 10kΩ, 68kΩ, etc.)
- Capacitors (e.g., 10nF, 100nF)
- Breadboard & Wires
- Oscilloscope (optional for waveform check)

---

##  Software Used
- Proteus simulation software

---

##  Project Versions

###  Version 1: Without Arduino
- Built using only a **555 Timer in astable mode**
- Controls servo motor via PWM signal
- The duty cycle is tuned using resistors & capacitors
- Suitable for basic hardware-based PWM learning



###  Version 2: With Arduino
- Uses `Servo.h` library to control servo angle
- Easy to calibrate and adjust rotation angles
- Demonstrates how microcontrollers simplify PWM-based control

---

##  Files in this Repo

| File Name                         | Description                          |
|----------------------------------|--------------------------------------|
| `servo_control_555_timer.png`    | Schematic image for 555 Timer circuit |
| `servo_control_arduino.ino`      | Arduino code to control the servo    |
| `README.md`                      | This documentation                   |
| `servo_timer_simulation.dsn`     | (Optional) Proteus simulation file   |

---

##  Output

- Servo rotates based on PWM signal from either the 555 Timer or Arduino
- 555 version produces basic oscillation-based motion
- Arduino version allows precise angle control

---

##  What I Learned

- How PWM works at the hardware level (using RC components)
- Using Arduino's `Servo.h` library for easy control
- Comparing analog vs digital approaches to signal generation

---

##  Future Improvements

- Add potentiometer to make 555 timer control adjustable
- Control multiple servos via Arduino
- Add display or input for angle selection

---

##  License

This project is open-source and free to use for educational purposes.
