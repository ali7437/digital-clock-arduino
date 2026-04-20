⏰ Digital Clock with Alarm — Arduino
A digital clock with alarm functionality built using Arduino Uno and a 16×2 I2C LCD display. Simulated on Wokwi.
🔗 Live Simulation: [Open in Wokwi]([YOUR WOKWI LINK])

📌 What It Does

Displays real-time hours, minutes, and seconds on a 16×2 LCD
Allows setting the current time using push buttons
Allows setting an alarm time
Buzzer beeps when the alarm time is reached
Built-in pull-up resistors used — no external resistors needed


🛠️ Components Used
ComponentQuantityArduino Uno1LCD 16×2 (I2C)1Active Buzzer1Push Button3

🔌 Wiring Table
ComponentPinArduino PinLCDVCC5VLCDGNDGNDLCDSDAA4LCDSCLA5Buzzer+ (long)Pin 8Buzzer− (short)GNDButton 1 (Set Hour)SignalPin 2Button 1Other legGNDButton 2 (Set Min)SignalPin 3Button 2Other legGNDButton 3 (Set Alarm)SignalPin 4Button 3Other legGND

🖥️ Simulation Preview
<img width="752" height="628" alt="image" src="https://github.com/user-attachments/assets/bc61bd05-a7fa-4daa-98f5-261f2f45c05b" />


🚀 How to Use

Open the [Wokwi simulation] https://wokwi.com/projects/461780937380294657
Click the green Play button to start
The clock starts ticking from 00:00:00
Button 1 → Increase hour
Button 2 → Increase minute
Button 3 → Set alarm time (cycles through minutes)
When the clock matches the alarm time → buzzer beeps 🔔


📁 Project Structure
digital-clock-arduino/
├── src/
│   └── digital_clock.ino   ← Main Arduino code
├── docs/
│   └── <img width="752" height="628" alt="image" src="https://github.com/user-attachments/assets/50db8500-e274-4a75-8dc5-c0f6746f55ef" />
      ← Wokwi simulation screenshot
└── README.md

💡 Key Concepts Learned

I2C communication (LCD display)
millis() for non-blocking timekeeping
INPUT_PULLUP for buttons without external resistors
tone() function for buzzer control
State management for alarm logic


👨‍💻 Author
ali7437 — Electrical Engineering Student
Exploring the software side of electronics, one project at a time ⚡
