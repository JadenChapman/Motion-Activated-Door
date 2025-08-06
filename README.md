# 🚪 Motion Activated Door

The **Motion Activated Door** is an Arduino-based automation project that uses an ultrasonic sensor to detect motion and automatically open or close a door using a servo motor. It's ideal for learning basic electronics, sensor integration, and automation concepts.

---

## 📋 Project Description

This project demonstrates a simple, contactless automatic door system. When motion is detected within a certain range by the ultrasonic sensor, the Arduino activates a servo motor to open the door and optionally triggers a buzzer for audible feedback.

---

## 🧰 Components Used

| Component               | Quantity |
|------------------------|----------|
| Arduino Uno  | 1        |
| Ultrasonic Sensor (HC-SR04) | 1        |
| Servo Motor (SG90)     | 1        |
| Buzzer                 | 1        |
| Breadboard             | 1        |
| Jumper Wires           | As needed |
| USB Cable (for Arduino) | 1        |

---

## 🛠️ Installation & Setup

1. **Connect the components**:
   - Connect the **Ultrasonic Sensor** to the Arduino:
     - VCC → 5V
     - GND → GND
     - Trig → Digital Pin 9
     - Echo → Digital Pin 10
   - Connect the **Servo Motor**:
     - VCC (Red) → 5V
     - GND (Brown) → GND
     - Signal (Orange) → Digital Pin 6
   - Connect the **Buzzer**:
     - Positive → Digital Pin 7
     - Negative → GND

2. **Upload the Code**:
   - Use the Arduino IDE to upload your `.ino` file to the board.
   - Select the correct board and port from the *Tools* menu.

3. **Power On**:
   - Power the Arduino via USB or external 5V source.

---

## ⚙️ How It Works

- The **Ultrasonic Sensor** continuously measures the distance in front of the "door".
- When an object (e.g., a person) comes within a predefined range (e.g., < 20 cm), the Arduino:
  - **Activates the Servo Motor** to simulate opening the door.
  - **Triggers the Buzzer** for an alert sound (optional).
- After a short delay, the servo returns to the closed position.

---

## 📸 Images / Videos

> *Add photos or GIFs of your setup and a working demo here.*

(https://ibb.co/rR5dqZcJ)
- [🎥 Watch the demo video](https://drive.google.com/file/d/1c-EQGTHe_LyOobcXvRgOF6LtA3-USBvx/view)





## 🙌 Credits

Developed by Jaden Chapman

Special thanks to:
- Arduino Community
- Open-source tutorials & circuit references

