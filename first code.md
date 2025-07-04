# 💡 Getting Started with Arduino Programming

This section will guide you to write your **first Arduino program** (Blink an LED), understand **basic commands**, and learn how to **upload it to the Arduino UNO board** using the Arduino IDE.

---

## 🖥️ Step 1: Install the Arduino IDE

1. Visit the official site: [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)
2. Download and install Arduino IDE based on your OS (Windows/Linux/Mac).
3. Open the Arduino IDE.

---

## 💡 Step 2: Write Your First Program (LED Blink)

Paste the following code in the editor:

```cpp
// This is a basic LED Blink program using the built-in LED

void setup() {
  pinMode(LED_BUILTIN, OUTPUT); // Set the built-in LED pin as OUTPUT
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH); // Turn LED ON
  delay(1000);                     // Wait for 1 second (1000 ms)
  digitalWrite(LED_BUILTIN, LOW);  // Turn LED OFF
  delay(1000);                     // Wait for 1 second
}
