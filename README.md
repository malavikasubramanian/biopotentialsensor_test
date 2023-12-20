# biopotentialsensor_test

# Overview
>This GitHub repository contains the code for a project that enables Electroencephalogram (EEG) monitoring using the BioAmp EXG Pill and Maker Uno. The BioAmp EXG Pill, a compact chip from Upside Down Labs, records biopotential signals from the brain, while the Maker Uno serves as the microcontroller board for data acquisition and transmission.

# Project Description
> In this project, we leverage the capabilities of the BioAmp EXG Pill to capture EEG signals from the visual cortex part of the brain. The goal is to provide a simple yet effective setup for EEG monitoring, allowing users to record and visualize brainwave activity.

# Hardware Requirements
1. BioAmp EXG Pill
2. BioAmp Cable
3. Gel Electrodes
4. Jumper Cables
5. Nuprep Skin Preparation Gel
6. Wet Wipe
7. Brain BioAmp Band (optional)
8. Electrode Gel (if using Brain BioAmp Band)
9. Microcontroller Board
10. Arduino Uno 
11. USB Cable

# Software Requirements

1. Arduino IDE
2. Backyard Brains' Spike Recorder

# Repository Contents
arduino code: Arduino code for the Arduino Uno, responsible for sampling EEG signals, handling commands, and interfacing with the BioAmp EXG Pill.

# Instructions
1. Assemble Hardware

2. Download and install the Arduino IDE from Arduino Software.
3. Download Backyard Brains' Spike Recorder from Spike Recorder.
4. Upload Code

5. Open the arduino_code.py file in the Arduino IDE.
6. Connect the Maker Uno to your computer using the USB cable.
7. Upload the code to the Maker Uno.
8. Configure Spike Recorder

9. Start Spike Recorder and access settings.
10. Choose the COM port of the Arduino Uno.
11. Apply a 50Hz notch filter and set low bandpass filter to 1Hz and high bandpass filter to 14Hz.
12. Close settings and start recording EEG signals.

# Visualize EEG:

1. Observe brainwave signals on the Spike Recorder screen.
2. Experiment with different features of Spike Recorder for signal visualization.
   
# Important Notes
1. Ensure correct electrode placement for accurate EEG monitoring.
2. Carefully follow GND and VCC connections to prevent sensor damage.
3. Familiarize yourself with Spike Recorder features for effective signal visualization.
