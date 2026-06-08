# omi-device-clone
Wearable AI voice recorder using XIAO ESP32-S3 Sense - continuous transcription with OpenAI Whisper
# 🎙️ OMI Device Clone — Wearable AI Voice Recorder

> DIY wearable AI pendant using XIAO ESP32-S3 Sense for continuous voice transcription

## 🎯 What it does
- Continuously records conversations via PDM microphone
- Streams audio over WiFi to Python server
- OpenAI Whisper transcribes speech to text
- Supports English & Telugu languages

## 🛠️ Tech Stack
- Seeed Studio XIAO ESP32-S3 Sense
- Arduino IDE (I2S PDM microphone)
- Python TCP server
- OpenAI Whisper (speech-to-text)
- WiFi audio streaming

## 📌 Hardware
- XIAO ESP32-S3 Sense board
- Built-in PDM microphone (GPIO 42 CLK, 41 DATA)
- USB-C power

## ✅ Status
- I2S microphone working ✅
- WiFi audio streaming working ✅
- English transcription working ✅
- Telugu transcription — improving 🔄
- Continuous recording — in progress 🔄

## 🔜 Coming Soon
- Telugu accuracy improvement (Whisper medium model)
- Continuous recording (no manual reset)
- AI summary generation

## 👨‍💻 Built by
Harish — ESP32 Developer & AI Enthusiast, Andhra Pradesh
