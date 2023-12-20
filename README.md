# biopotentialsensor_test

Overview
>This GitHub repository contains the code for a project that enables Electroencephalogram (EEG) monitoring using the BioAmp EXG Pill and Maker Uno. The BioAmp EXG Pill, a compact chip from Upside Down Labs, records biopotential signals from the brain, while the Maker Uno serves as the microcontroller board for data acquisition and transmission.

Project Description
> In this project, we leverage the capabilities of the BioAmp EXG Pill to capture EEG signals from the visual cortex part of the brain. The goal is to provide a simple yet effective setup for EEG monitoring, allowing users to record and visualize brainwave activity.

Hardware Requirements
BioAmp EXG Pill
BioAmp Cable
Gel Electrodes
Jumper Cables
Nuprep Skin Preparation Gel
Wet Wipe
Brain BioAmp Band (optional)
Electrode Gel (if using Brain BioAmp Band)
Microcontroller Board:

Arduino Uno or Maker Uno
USB Cable
Software Requirements
Arduino IDE
Backyard Brains' Spike Recorder
Repository Contents
EEG_Monitoring_Code.ino: Arduino code for the Maker Uno, responsible for sampling EEG signals, handling commands, and interfacing with the BioAmp EXG Pill.
Instructions
Assemble Hardware:

Follow the hardware assembly steps outlined in the project documentation.
Connect the BioAmp EXG Pill to the Maker Uno as instructed.
Install Software:

Download and install the Arduino IDE from Arduino Software.
Download Backyard Brains' Spike Recorder from Spike Recorder.
Upload Code:

Open the arduino_code.py file in the Arduino IDE.
Connect the Maker Uno to your computer using the USB cable.
Upload the code to the Maker Uno.
Configure Spike Recorder:

Start Spike Recorder and access settings.
Choose the COM port of the Maker Uno.
Apply a 50Hz notch filter and set low bandpass filter to 1Hz and high bandpass filter to 14Hz.
Close settings and start recording EEG signals.
Visualize EEG:

Observe brainwave signals on the Spike Recorder screen.
Experiment with different features of Spike Recorder for signal visualization.
Important Notes
Ensure correct electrode placement for accurate EEG monitoring.
Carefully follow GND and VCC connections to prevent sensor damage.
Familiarize yourself with Spike Recorder features for effective signal visualization.
