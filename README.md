<img width="1279" alt="Screenshot 2025-04-12 at 15 42 05" src="https://github.com/user-attachments/assets/7d1136ec-a48e-48a9-a209-f008684e3e1f" />
<img width="1280" alt="Screenshot 2025-04-15 at 20 46 40" src="https://github.com/user-attachments/assets/806b7e62-d58a-48b9-9d6f-ca3c191f7a11" />
<img width="1200" alt="Screenshot 2025-04-12 at 15 42 23" src="https://github.com/user-attachments/assets/64e7657a-ca3b-4d6b-8967-1a18983640b4" />
<img width="1280" alt="Screenshot 2025-04-12 at 15 43 10" src="https://github.com/user-attachments/assets/3c8883c7-8d40-4b30-95ef-b1aa6e1666d3" />


# ⚡ Fault Detection in Transmission Line Using MATLAB Simulink

## 📘 Project Overview

This project focuses on simulating and analyzing faults in three-phase electrical transmission lines using MATLAB Simulink. The objective is to detect and classify various types of faults—such as single line-to-ground (L-G), line-to-line (L-L), double line-to-ground (L-L-G), and three-phase faults (L-L-L)—to enhance the reliability and safety of power systems.

## 🔍 Features

- Simulation of different fault scenarios in transmission lines.
- Real-time detection and classification of faults.
- Visualization of voltage and current waveforms during fault conditions.

## 🛠 Tools and Technologies

- MATLAB R2023b
- Simulink
- Simscape Electrical

## 🧭 Simulation Model

The Simulink model comprises:

- Three-phase voltage source.
- Transmission line modeled using Pi-section blocks.
- Fault injection module to simulate different fault conditions.
- Measurement blocks to capture voltage and current data.
- Display scopes for real-time waveform visualization.


## ⚙️ How It Works

1. Initialization: The simulation initializes the transmission line parameters and sets up the measurement blocks.
2. Fault Injection: At a predefined time, a fault is introduced using the fault injection module.
3. Data Acquisition: Voltage and current signals are monitored continuously.
4. Fault Detection: The system analyzes the waveforms to detect anomalies indicative of faults.
5. Classification: Based on the pattern of anomalies, the fault is classified into one of the predefined categories.
6. Visualization: The results are displayed on scopes for analysis.



