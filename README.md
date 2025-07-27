# IR Sensor LED Reaction System 🔦

This Arduino project simulates a proximity-based LED system using an IR sensor in TinkerCAD.  
It lights up the LED when something (like a hand or mouse) comes close to the sensor,  
and blinks the LED rapidly if no motion is detected for 5 seconds.

---

## 📌 Features

- 🔍 Detects proximity using an IR sensor (digital).
- 💡 Turns ON the LED when something is near.
- ⏱ After 5 seconds of no motion, blinks LED 5 times rapidly.
- ♻️ Resets on new movement.

---

## 🔧 Components Used (in TinkerCAD)

- 1 × Arduino Uno
- 1 × IR Proximity Sensor
- 1 × LED
- 1 × 220Ω Resistor
- Breadboard + Jumper Wires

---

## 🖥️ Circuit Connections

| Component Pin     | Arduino Pin       |
|-------------------|-------------------|
| IR Sensor VCC     | 5V                |
| IR Sensor GND     | GND               |
| IR Sensor OUT     | D2                |
| LED (Anode +)     | D13               |
| LED (Cathode -)   | GND (through resistor) |

---

## 🧠 How It Works

1. When the IR sensor detects motion (e.g., hand close to sensor), the LED turns ON.
2. When the object moves away, the LED turns OFF.
3. If no motion is detected for **5 seconds**, the LED **blinks 5 times quickly**.
4. The system resets on any new movement.

---


