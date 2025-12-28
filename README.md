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

<img width="894" height="511" alt="image" src="https://github.com/user-attachments/assets/6e57d121-e8eb-4986-b107-9ebdd467aafc" />

   
#  4. Module Description

## Input Module
1. Accepts text input through a text box 
2. Accepts voice input using browser-based speech recognition 
3. Converts voice into text for further processing

## Text Processing & Intent Detection Module
1. Analyzes the input sentence
2. Matches it with predefined phrases using a rule-based intent map
3. Identifies the corresponding action (intent)
## Action Mapping Module
1. Maps detected intent to a specific FBX animation
2. Ensures accurate one-to-one mapping between input and action
## Animation Rendering Module
1. Loads 3D character and animations using Three.js
2. Plays animations smoothly using AnimationMixer
3. Handles transitions and fallback to idle state
## User Interface Module
1. Displays current action status
2. Shows the 3D animated character
3. Designed for clarity, accessibility, and ease of use

#  5. Technology Stack

Frontend: HTML, CSS, JavaScript
3D Rendering: Three.js(WebGL)
Animation Format: FBX
Animation Control: AnimationMixer
Speech Recognition: Web Speech API
Styling: Responsive CSS

#  6. Example Workflow

1. User enters a sentence or speaks a command
2. System converts voice input into text
3. Text is analyzed to detect intent
4. Detected intent is matched with an action
5. Corresponding FBX animation is loaded
6. 3D character performs the action
7. Status is updated on the interface

#  7. Advantages

1. Improves accessibility for hearing-impaired users
2. Real-time visual feedback
3. Works offline for text input
4. Lightweight and browser-based
5. Scalable and extendable
6. No expensive hardware required

#  8. Applications

1. Assistive technology for hearing-impaired individuals
2. Educational and e-learning platforms
3. Emergency information systems
4. Virtual assistants
5. Human–computer interaction systems
6. Training and simulation environments

#  9. Future Enhancements

1. Integration of Natural Language Processing (NLP) models
2. Support for sign language gestures
3. Multilingual input support
4. Mobile and tablet version
5. AI-based intent classification
6. Integration with VR/AR environments

# 🔹 10. Web interface

<img width="1919" height="932" alt="image" src="https://github.com/user-attachments/assets/a93d79ba-11da-424d-b127-41e35c1e332d" />


# 🔹 11. Viva / One-Line Description

“The Text-to-Action Assistive System converts user-provided text commands into meaningful system actions using Natural Language Processing and automation techniques.”
