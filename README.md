# MIDI by Asher

<img width="941" height="927" alt="Screenshot 2026-10-25 211709" src="https://github.com/user-attachments/assets/4fbe6f93-7b00-49c7-8ee6-5154b455848a" />

**MIDI by Asher** is a custom MIDI controller designed in KiCad. The goal of this project is to build a compact controller with different types of inputs that can be used to control music software and MIDI-compatible instruments.

## Features

- 3 slide potentiometers for continuous control
- 1 EC11 rotary encoder
- 3 SK6812 MINI-E RGB LEDs
- 2 Kailh Choc low-profile mechanical switches
- 7 capacitive touch keys
- Waveshare ESP32-S3-Zero microcontroller

## Design

The schematic and PCB were designed in KiCad. The controller combines physical switches, touch inputs, rotary control, and sliders into one custom board.

### PCB Design

<img width="582" height="542" alt="Screenshot 2026-10-25 202403" src="https://github.com/user-attachments/assets/b94537d8-cb56-4f18-b9bf-6ce23a037a8e" />

### Schematic

<img width="1275" height="845" alt="Screenshot 2026-10-25 202445" src="https://github.com/user-attachments/assets/574298af-a08d-4bce-a496-8298739eebfd" />

## Hardware

The main controller is the Waveshare ESP32-S3-Zero. The components are designed to provide several different ways to interact with MIDI software. Firmware and input mapping will determine how each control behaves.

## Project Files

The `PCB` folder contains the KiCad project files, including the schematic, PCB layout, and project settings.

## Notes

Firmware will be completed once parts arrive

### Disclaimer
AI was used to help organize information in the READ ME. all ideas writing and pretty much everything was done by me 


