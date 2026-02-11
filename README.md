STM32 Seven Segment Counter with Parallel LED and Buzzer Control
📌 Project Overview

This project demonstrates a simple embedded system application using an STM32 microcontroller and the HAL library.
It implements:

A two-digit multiplexed 7-segment display counter

A push button input

An LED blinking task

A buzzer activation

All running in parallel inside the main loop

The main goal of this project is to show how multiple tasks can operate at the same time on a microcontroller using simple timing techniques — without using interrupts or RTOS.

🧩 Features
1. Seven Segment Display Counter

Two 7-segment displays are used in multiplexed mode

Digits count from 00 to 99

Each button press increases the displayed number by 1

The multiplexing technique allows both digits to be updated alternately at high speed

2. Button Input

A push button connected to PA15

Each press increments the counter

Software debouncing is implemented using timing variables

3. LED Blinking Task

An LED connected to PA10

The LED toggles ON/OFF every 500 ms

Works independently from the 7-segment and button logic

4. Buzzer Control

A buzzer connected to PA9

Activates briefly when the button is pressed

Demonstrates event-based output control

💻 Written using:

STM32CubeMX for configuration

IAR Embedded Workbench for compiling

📽️Working demo video available on YouTube:https://youtube.com/@ellislearningjourney?si=BwUaMJ2tFr43R_uL
