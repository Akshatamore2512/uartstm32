# uartstm32
# STM32 UART RGB LED Control 🚦

This is a personal project I built on the **STM32F446RE Nucleo board** where I control an RGB LED through **UART serial communication**. I created this project to practically understand how UART works on STM32 and how to interact with hardware through simple serial commands.

---

## 📌 Project Overview

The concept is simple — I connected an RGB LED to the microcontroller, set up UART communication with my PC, and typed characters in the serial terminal to control the color of the LED in real time.

---

## 📦 What I Used

- **Hardware**
  - STM32F446RE Nucleo board
  - Common cathode RGB LED
  - 3 resistors (220Ω)
  - USB cable for power + UART
  - Jumper wires

- **Software**
  - STM32CubeIDE
  - PUTTY for serial communication

---

## 🎮 How It Works

I configured **UART2** using CubeMX and set up three GPIO pins as PWM outputs for the RGB LED. When I type a character (`R`, `G`, or `B`) in the serial terminal, the microcontroller reads it and turns on the corresponding color on the LED.

It was a simple but effective way to see real-time interaction between the software and hardware.

---

## 🎯 Why I Made This

I didn’t just want to read UART theory — I wanted to test it on hardware and control something physical with it. This project helped me understand UART communication, GPIO control, and PWM generation on STM32 practically.

---

## 📈 What I Learned

- Configuring UART and GPIO on STM32F446RE
- Sending and receiving characters through serial
- Setting up PWM to control LED colors
- Building and debugging embedded firmware on STM32CubeIDE

---





