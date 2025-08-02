# Indicator Control using BLE (Moonrider Assignment)

This project implements an automotive indicator control system using BLE. The application logic is developed using MATLAB Simulink, and the base firmware is represented via a compiled `.bin` file.

---

## 🧠 Features

- Left and Right indicators activated via push buttons (1-second press)
- Mutual exclusivity between left and right indicators
- Hazard mode activated via simultaneous 1s press of both buttons
- LEDs toggle ON/OFF every 300 milliseconds
- Button press, indicator states logged via UART
- Application logic implemented in Simulink
- BLE module can transmit UART logs to mobile

---

## 📂 Repository Structure

- `Application123.slx` - Simulink model for indicator logic
- `indicator_firmware.bin` - Placeholder firmware binary
- `Video_Demo/` - Contains improved video demonstration
- `UART_logs/` - (Optional) UART logs captured during demo

---

## 🚀 How to Use

1. Open `Application123.slx` in MATLAB Simulink
2. Review or modify logic using Simulink blocks
3. Generate code and binary using Embedded Coder (if needed)
4. Flash `indicator_firmware.bin` (or generated file) to the board
5. Connect push buttons and LEDs as per model
6. Use UART/Serial Monitor to log events

---

## 🎥 Video Demo

📎 [Link to Video Demo](PASTE_YOUR_GOOGLE_DRIVE_LINK_HERE)

---

## 📄 UART Log

📎 [Link to UART Log (if available)](PASTE_YOUR_UART_LOG_LINK_HERE)

---

## 👨‍💻 Author

**Rahul H Hanumagatti**

