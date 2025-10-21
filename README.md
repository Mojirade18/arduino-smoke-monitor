# arduino-smoke-monitor
# 🔴 Arduino Blink LED Project

This is a simple **Arduino Blink** project created to test pull requests and repository setup.  
It blinks the onboard LED connected to pin **13** — one of the classic starter projects for learning Arduino basics.

---

## 🧠 Project Overview

The goal of this project is to:
- Demonstrate how to upload and run a basic Arduino sketch.
- Practice GitHub contribution workflow (branches, pull requests, etc.).
- Explore open-source collaboration and testing.

---

## ⚙️ Components Required

| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino Uno | 1 | Main microcontroller board |
| LED | 1 | Built-in or external LED |
| Jumper Wires | 2 | For connecting LED (if external) |

---

## 💡 Arduino Code

```cpp
void setup() {
  pinMode(13, OUTPUT); // Set pin 13 as output
}

void loop() {
  digitalWrite(13, HIGH); // Turn the LED on
  delay(500);             // Wait 0.5 second
  digitalWrite(13, LOW);  // Turn the LED off
  delay(500);             // Wait 0.5 second
}
