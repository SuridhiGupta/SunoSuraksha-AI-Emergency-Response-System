# 🚨 SunoSuraksha – AI Emergency Response System (Prototype V1)

Most safety applications are reactive. They depend on users manually pressing an SOS button or making a phone call during situations where panic, physical restraint, or unconsciousness may make these actions impossible.

SunoSuraksha explores a different approach:

> **Can an AI system detect distress automatically and initiate emergency actions without requiring user interaction?**

The long-term vision is an AI-powered ambient distress detection system that can eventually be integrated into wearable devices such as smart rings, bracelets, or pendants.

## 📖 The Problem

Traditional safety solutions assume users are always capable of interacting with their devices.

Real emergencies often don't provide that opportunity.

SunoSuraksha investigates whether distress situations can be recognized passively through environmental audio analysis.

## 🧠 Prototype V1

Current prototype capabilities:

* 🎤 Real-time microphone monitoring
* 🧠 Distress classification using CNN + MFCC
* 🚨 Alert triggering
* 🕒 Event timestamp logging
* 📊 Confidence estimation

## 🛠 Tech Stack

**Frontend**

* Streamlit

**Backend**

* Python

**Machine Learning**

* TensorFlow
* CNN
* MFCC

**Audio Processing**

* Librosa

## 🚧 Current Status

Prototype Version : **V1**

Implemented:

✅ Audio Monitoring

✅ Distress Detection

✅ Event Logging

Planned Future Work:

🔵 Wearable Integration

🔵 Edge AI Optimization

🔵 Notification Services

🔵 Smart Campus Safety Ecosystem

## ⚠ Limitations

This project is currently a proof-of-concept prototype.

Some challenges still under investigation include:

* Limited distress datasets
* Model validation
* Wearable deployment feasibility
* Real-world testing

Built to explore the idea that **personal safety systems should assist users proactively rather than waiting for users to ask for help.**
