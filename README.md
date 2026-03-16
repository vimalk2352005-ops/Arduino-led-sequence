# Arduino LED Sequence🚦
PROJECT LINK:https://www.tinkercad.com/things/6ZU7PMYIkH6-fabulous-uusam-turing

This is a simple Arduino project that simulates a **traffic light system using LEDs**.  
The circuit is designed and tested using **Tinkercad**.

## 📌 Project Overview
The Arduino controls three LEDs:
- 🟢 Green LED
- 🟡 Yellow LED
- 🔴 Red LED

Each LED turns ON and OFF sequentially to simulate a traffic light.

## ⚙️ Components Used
- Arduino Uno
- 3 LEDs (Red, Yellow, Green)
- 3 Resistors (220Ω)
- Jumper Wires
- Breadboard (optional)

## 🔌 Circuit Logic
Each LED is connected to a digital pin of the Arduino.  
The program turns ON each LED for **1 second** and then turns it OFF before switching to the next LED.

## 💻 Arduino Code

```cpp
int a = 1;
int b = 2;
int c = 3;

void setup()
{
  pinMode(a, OUTPUT);
  pinMode(b, OUTPUT);
  pinMode(c, OUTPUT);
}

void loop()
{
  digitalWrite(a, HIGH);
  delay(1000);
  digitalWrite(a, LOW);
  delay(1000);

  digitalWrite(b, HIGH);
  delay(1000);
  digitalWrite(b, LOW);
  delay(1000);

  digitalWrite(c, HIGH);
  delay(1000);
  digitalWrite(c, LOW);
  delay(1000);
}
```

## 🎯 Learning Outcome
- Basic Arduino programming
- Controlling LEDs using digital pins
- Understanding delay and sequential logic

## 🧪 Simulation
Built and tested using **Tinkercad Arduino Simulator**.

## 📷 Project Preview
(Add your project screenshot here)

## 👨‍💻 Author
Vimal K
