# Signix

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
</p>

<p align="center">
  <strong>Hand Gesture Recognition System</strong><br>
  A computer vision project that connects hand gesture recognition with electronic hardware.
</p>

---

## About the Project

**Signix** is a hand gesture recognition system designed to identify numbers from 1 to 5 using a camera. It combines computer vision and electronics to recognize hand positions and display the detected number through an Arduino-controlled digital display.

## Purpose

The main goal of Signix is to explore how computer vision can be used to interpret hand gestures and transform them into digital outputs. It demonstrates the integration of software and hardware through real-time image processing and serial communication.

## How It Works

1. **Image Capture:** A camera captures the user's hand in real time.
2. **Hand Detection:** MediaPipe identifies the hand and its landmarks.
3. **Gesture Recognition:** Python processes the hand position to determine the represented number.
4. **Serial Communication:** The detected number is sent to Arduino.
5. **Visual Output:** Arduino controls LEDs and a digital display to show the result.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| OpenCV | Camera access and image processing |
| MediaPipe | Hand landmark detection |
| Arduino | Electronic control |
| Serial Communication | Data exchange between Python and Arduino |
| LEDs & Display | Visual representation of results |

## Features

- Real-time hand detection.
- Recognition of numbers from 1 to 5.
- Integration between Python and Arduino.
- Visual output using LEDs and a digital display.
- Computer vision and hardware interaction.

## Skills Applied

- Computer Vision
- Image Processing
- Python Programming
- Embedded Systems
- Hardware-Software Integration
- Serial Communication

---

<p align="center">
  <strong>Developed by Diego Contreras</strong><br>
  <sub>Exploring the connection between software, electronics and computer vision.</sub>
</p>
