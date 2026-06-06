# DUDE AI Voice Assistant

DUDE is an AI-powered voice assistant built using Raspberry Pi, Python, OpenAI API, a USB microphone, a speaker, and a Raspberry Pi camera module.

The system responds to the wake word **"Hey Dude"**, listens to user commands, sends speech to OpenAI for processing, and replies using text-to-speech audio output. It also supports camera-based object recognition using OpenAI Vision.

---

## Project Overview

DUDE is designed as a low-cost and customizable AI assistant that combines voice interaction and computer vision on a Raspberry Pi.

The assistant can:

- Wake up using the command **"Hey Dude"**
- Listen to user questions
- Convert speech to text
- Generate intelligent responses using OpenAI
- Convert responses into speech
- Play audio through a speaker
- Activate the camera using **"Open Camera"**
- Recognize objects using OpenAI Vision
- Return to sleep mode using **"Stop Listening"**

---

## Features

- Wake word detection
- Voice command recognition
- Speech-to-text conversion
- AI-generated responses
- Text-to-speech output
- Raspberry Pi camera integration
- Object recognition
- Sleep mode command
- Portable Raspberry Pi setup

---

## Hardware Requirements

- Raspberry Pi 3B+
- Raspberry Pi Camera Module
- USB Microphone
- AUX Speaker or USB Speaker
- MicroSD Card
- Power Supply or Power Bank
- Internet Connection

---

## Software Requirements

- Raspberry Pi OS
- Python 3
- OpenAI Python Library
- Vosk
- PyAudio
- mpg123
- rpicam camera tools

---

## Technologies Used

- Python
- Raspberry Pi OS
- OpenAI API
- OpenAI Speech-to-Text
- OpenAI Text-to-Speech
- OpenAI Vision
- Vosk Speech Recognition
- PyAudio
- Raspberry Pi Camera

---

## Installation

Update the Raspberry Pi:

```bash
sudo apt update
sudo apt upgrade
