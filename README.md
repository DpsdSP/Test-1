
Arduino LED Blink Project
A simple Arduino project to blink an LED—perfect for beginners!
📌 Overview
This project demonstrates the classic "Hello World" of Arduino: blinking an LED. It’s a great starting point for learning how to control outputs and understand the basics of Arduino programming.
🛠️ Hardware Requirements

Arduino board (Uno, Nano, Mega, etc.)
LED
220Ω resistor (or similar)
Breadboard and jumper wires
📥 Installation

Clone this repository or download the .ino file.
Open the file in the Arduino IDE.
Connect your Arduino board to your computer.
Select the correct board and port in the Arduino IDE.
Upload the code to your Arduino.
🔧 Wiring

Connect the anode (long leg) of the LED to a digital pin (e.g., pin 13) via the resistor.
Connect the cathode (short leg) of the LED to GND.
💡 Code Explanation
cpp
Copy

void setup() {
  pinMode(LED_BUILTIN, OUTPUT); // Initialize the LED pin as an output
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH); // Turn the LED on
  delay(1000);                     // Wait for a second
  digitalWrite(LED_BUILTIN, LOW);  // Turn the LED off
  delay(1000);                     // Wait for a second
}


setup(): Runs once when the Arduino starts. Here, we set the LED pin as an output.
loop(): Runs repeatedly. We turn the LED on and off with a 1-second delay between each state.
