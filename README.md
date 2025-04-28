# 🔒 Arduino Digital Locker (LCD + Keypad + Servo)

A simple digital locker system using:
- Arduino Uno R3
- 16x2 LCD Display
- 4x4 Matrix Keypad
- Servo Motor

---

## 📋 Features
- Displays "Hello Krishna!" on start.
- Password entry via keypad.
- Correct password → Servo unlocks for 5 seconds.
- Wrong password → Shows "Incorrect Pass".

---

## 🛠 Components
- Arduino Uno R3
- Servo Motor (e.g., SG90)
- 16x2 LCD (Parallel mode)
- 4x4 Matrix Keypad
- Breadboard, Jumper Wires

---

## 🔌 Connections

**LCD to Arduino:**
- RS → 12
- E → 11
- D4 → 5
- D5 → 4
- D6 → 3
- D7 → 2

**Keypad to Arduino:**
- R1 → A0
- R2 → A1
- R3 → A2
- R4 → A3
- C1 → A4
- C2 → A5
- C3 → 8
- C4 → 9

**Servo to Arduino:**
- Signal → 6
- VCC → 5V
- GND → GND

---

## 🖥 How It Works
1. LCD shows **"Hello Krishna!"**.
2. Enter 4-digit password:
   - Confirm with `#`
   - Clear with `*`
3. Correct → Unlocks (servo 180° for 5 sec).
4. Incorrect → Shows error, retry allowed.

(Default Password: **1234**)
