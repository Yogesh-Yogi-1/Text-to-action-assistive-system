# Text-to-action-assistive-system.

#  1. Project Introduction

The Text-to-Action Assistive System is an interactive application designed to convert text or voice input into visual human actions using 3D animations.
The primary objective of this project is to assist people with hearing disabilities by representing information through gestures and body movements instead of audio.

The system uses rule-based intent detection to analyze the input sentence and maps it to predefined actions. These actions are then executed on a 3D animated character using Three.js and FBX animations, providing an intuitive and accessible form of communication.

#  2. Problem Statement

People with hearing impairments often face challenges in understanding audio-based information, such as announcements, instructions, or alerts.
Existing systems mostly rely on text or sound, which may not always be effective or inclusive.
There is a need for an assistive system that can:
Interpret text or speech input
Convert it into meaningful visual actions
Present information in a human-understandable gesture format
This project aims to address that gap by offering a visual, gesture-based communication system.

#  3. System Architecture

## Input Module
1. Accepts text input through a text box 
2. Accepts voice input using browser-based speech recognition 
3. Converts voice into text for further processing

## Text Processing & Intent Detection Module
Analyzes the input sentence
Matches it with predefined phrases using a rule-based intent map
Identifies the corresponding action (intent)
## Action Mapping Module
Maps detected intent to a specific FBX animation
Ensures accurate one-to-one mapping between input and action
## Animation Rendering Module
Loads 3D character and animations using Three.js
Plays animations smoothly using AnimationMixer
Handles transitions and fallback to idle state
## User Interface Module
Displays current action status
Shows the 3D animated character
Designed for clarity, accessibility, and ease of use

# 🔹 4. Module Description
📌 Module 1: Text Input Module

Accepts user commands in textual format

Example: “Open notepad”

📌 Module 2: NLP Processing Module

Removes stop words

Extracts important keywords

Identifies semantic meaning of the sentence

Example:
“Please open the browser” → open + browser

📌 Module 3: Intent Recognition Module

Detects the intention behind the user command

Can be implemented using rule-based or machine-learning techniques

User Text	Detected Intent
Open browser	OPEN_APP
Turn on light	DEVICE_ON
📌 Module 4: Action Mapping Module

Converts detected intent into system-level commands

Intent	Action
OPEN_APP	os.system()
DEVICE_ON	GPIO / API
📌 Module 5: Action Execution Module

Executes the mapped action in real time

Opens applications, controls devices, or sends messages

# 🔹 5. Technology Stack

Frontend: HTML / Tkinter / React

Backend: Python

Natural Language Processing: NLTK / SpaCy

System Control: Python os, subprocess

Hardware (Optional): Arduino / Raspberry Pi

# 🔹 6. Example Workflow
Input
Open calculator

Processing

NLP extracts keywords

Intent detected as OPEN_APP

System executes calculator application

Output

👉 Calculator opens automatically 🧮

# 🔹 7. Advantages

Hands-free operation

User-friendly interface

Saves time and effort

Highly beneficial for disabled users

Can be integrated with smart devices

# 🔹 8. Applications

Smart Home Automation

Assistive Technologies

Desktop Automation Systems

Healthcare Applications

Voice/Text-controlled systems

# 🔹 9. Future Enhancements

Voice-to-Action integration

AI-based adaptive learning

Multi-language support

Mobile application integration

# 🔹 10. Web interface

<img width="1919" height="932" alt="image" src="https://github.com/user-attachments/assets/a93d79ba-11da-424d-b127-41e35c1e332d" />


# 🔹 11. Viva / One-Line Description

“The Text-to-Action Assistive System converts user-provided text commands into meaningful system actions using Natural Language Processing and automation techniques.”
