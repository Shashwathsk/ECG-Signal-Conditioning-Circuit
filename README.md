Analog ECG Signal Conditioning Circuit

Overview

This project focuses on the design and development of an analog ECG (Electrocardiogram) signal conditioning circuit.

The main objective is to acquire low-amplitude ECG signals and process them through different analog signal-conditioning states to obtain a suitable ECG output waveform.

Circuit Architecture

The proposed system consists of the following stages:

1. Instrumentation Amplifier
2. Right leg drive circuit 
3. Low-Pass Filter (150 Hz)
4. High-Pass Filter (0.05 Hz)
5. 50 Hz Active Twin-T Notch Filter
6. Additional Amplifier (Maximum Gain 20)
7. DC Offset Adjustment

Components and Software

- AD620 Instrumentation Amplifier (alternative implementation under evaluation)
- TL071 Operational Amplifiers
- Passive and active filter components
- OrCAD Capture
- PSpice

Current Progress

The initial circuit design and signal-conditioning stages have been developed.

The uploaded schematic is a preliminary design and is subject to further modifications, calculations, simulation and testing.

Repository Contents

- "ECG_Circuit_Draft_v1.pdf" – Preliminary ECG circuit schematic.

Future Work

- Finalize the instrumentation amplifier design.
- Analyze Right Leg Drive stability.
- Verify filter characteristics through simulation.
- Integrate and test all circuit stages.
- Develop the hardware prototype.

Disclaimer

This is an educational electronics project under development. It is not a certified medical device and must not be used for clinical diagnosis or connected to a person without appropriate medical electrical safety measures.
