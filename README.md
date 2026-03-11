# STM32-MINI-PROJECTS
Mini projects


1- STM32 Blue Pill – LED Blink

## Description
Blinking external LED using GPIO PA5 on STM32F103.

## Hardware
- STM32 Blue Pill
- ST-LINK V2
- LED + 220Ω resistor

## Software
- STM32CubeIDE
- Embedded C (HAL)

## What I learned
- GPIO configuration
- HAL functions
- Debugging with ST-LINK



---

2- # Button Controlled LED using STM32 Blue Pill

## Project Overview

This project demonstrates how to control an LED using a push button with the **STM32 Blue Pill (STM32F103C8T6)** microcontroller.

When the push button is pressed, the LED turns **ON**, and when the button is released, the LED turns **OFF**.

This project helps beginners understand **GPIO input and output configuration** in STM32 microcontrollers.

---

## Components Used

* STM32 Blue Pill (STM32F103C8T6)
* Push Button
* LED
* 220Ω Resistor
* Breadboard
* Jumper Wires

---

## Working Principle

1. The push button is configured as a **GPIO input pin**.
2. The LED is connected to a **GPIO output pin**.
3. The microcontroller continuously reads the button state.
4. If the button is pressed, the LED is turned **ON**.
5. If the button is not pressed, the LED remains **OFF**.

---

## Pin Configuration (Example)

| Component | STM32 Pin |
| --------- | --------- |
| LED       | PC13      |
| Button    | PA0       |

---

## Software Used

* STM32CubeIDE
* Embedded C Programming

---

## Learning Outcome

* Understanding **GPIO input/output**
* Interfacing **push buttons with microcontrollers**
* Basic **embedded C programming on STM32**
