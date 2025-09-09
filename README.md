# Applied_Electronic_Circuit_Lab-En(May 2022 – Jun 2022)

&nbsp;

## 🧠 Rehabilitation Completion Detector

&nbsp;

## 📑 Table of Contents

1. [📌 Project Overview](#1--Project-Overview)  
2. [🔧 Components](#2--Components)  
3. [💻 Technologies](#3--Technologies)  
4. [🧭 System Workflow](#4--System-Workflow)   

   
&nbsp;
## 📌 Project Overview
This project aims to design a system that evaluates muscle activity in patients with severe muscle impairment (e.g., unable to contract muscles in arms or legs) and determines whether rehabilitation has been successfully completed.

Surface EMG (sEMG) signals are measured to detect muscle contraction in real time.
When the measured signal exceeds a predefined threshold, an audio feedback is generated to notify that muscle contraction is successful.

&nbsp;

### 🎯 Goal
- Assess the recovery level of patients with weakened muscle function and provide intuitive feedback when a certain threshold is reached

- Evaluate rehabilitation potential in a non-invasive way to improve patient comfort and motivation

- Utilize bio-signal–based interface as an assistive communication or response trigger device
  
&nbsp;

### 🏭 Use of Existing Technology & Scalability

- Applied surface EMG measurement technology by attaching electrodes to the skin and analyzing the electrical signal
- Amplified EMG signals using an instrumentation amplifier to exceed 5 V, triggering audio output as feedback
- Considered human muscle resonance frequency for accurate signal interpretation and reliable evaluation

&nbsp;

### ✅ Potential Applications

- Rehabilitation evaluation system: Provide quantitative indicators of muscle recovery
- Muscle-triggered alert system: Control alarms or external devices based on user signals
- Serve as fundamental research material for brain–muscle–machine interface studies
- Expandable to home exercise tracking devices for elderly patients or those undergoing rehabilitation


&nbsp;
## 2. 🔧 Components

| Component                        | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| **1N4002 Diode**                | General-purpose diode for rectification and reverse-voltage protection      |
| **Toshiba 9V Battery**          | Power source for the circuit                                               |
| **TL082CP Operational Amplifier** | Low-noise dual op-amp used for bio-signal amplification                   |
| **Round IC Socket (08P, 14P)**  | Socket to allow easy attachment/detachment of IC chips                     |
| **AT-1750-TFL-LW95-R**          | Speaker for sound output when amplified bio-signal exceeds threshold       |
| **EIC-106 Circuit Board**       | Board for soldering and assembling the circuit                             |
| **100 µF 6.3 V Electrolytic Capacitor** | Power noise suppression and signal stabilization                   |
| **LM339 Comparator**            | Compares input signal with reference voltage and outputs a digital trigger |
| **PCB Board (Dual Half Size)**  | Breadboard for experimental circuit assembly and Arduino/module mounting   |
| **AD620BNZ Instrumentation Amplifier** | High-precision amplifier for differential EMG signal acquisition    |

&nbsp;

<img width="1328" height="908" alt="image" src="https://github.com/user-attachments/assets/19d921d6-f596-4d88-84ec-da9a4cb9e17d" />

<img width="1208" height="876" alt="image" src="https://github.com/user-attachments/assets/38f5e0eb-e1c6-4f36-921f-bebbebef0af9" />

<img width="1345" height="284" alt="image" src="https://github.com/user-attachments/assets/dea76b85-a19a-4cce-b183-d5ad14f5ba2d" />


&nbsp;
<img width="821" height="280" alt="image" src="https://github.com/user-attachments/assets/3ebcf197-adfd-4b89-9ded-90b3fcc41b4e" />

<img width="928" height="416" alt="image" src="https://github.com/user-attachments/assets/fb95ef9d-be8b-49e3-a99e-9eb19074e23f" />

## 3. 💻 Technologies

| Technology                       | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| **Bio-signal Measurement**      | Captured micro-voltage muscle signals (2–10 mV, 20–70 Hz) via instrumentation amplifier |
| **Surface EMG (sEMG) Method**   | Collected EMG signals with skin-attached electrodes for non-invasive and user-friendly measurement |
| **Circuit Design & Implementation** | Built circuits on breadboards and universal boards, performed soldering and experiments |
| **Instrumentation Amplifier (IA)** | Amplified input signals (Vin+ = 5 mV, Vin- = 3 mV) about 495× for reliable low-power detection |
| **Analog Filters (LPF, Notch, HPF)** | Removed unnecessary high-frequency noise; used notch filter to suppress 60 Hz power line noise and HPF for low-frequency filtering |
| **Non-inverting Amplifier + Rectifier** | Converted signals to positive voltage for stable detection |
| **Comparator**                  | Generated digital output when input exceeded reference voltage (5 V) → used as sound trigger |
| **Audio Output**                | Played a sound via speaker when final voltage exceeded 5 V → indicating successful rehabilitation |



&nbsp;
## 4. 🧭 System Workflow
<img width="1272" height="618" alt="image" src="https://github.com/user-attachments/assets/67413147-9c72-4b5e-aa2a-0a3404333f03" />

### 1. 
<img width="1298" height="728" alt="image" src="https://github.com/user-attachments/assets/94a0cd66-6a6a-4011-8f94-2af5497a62a9" />

&nbsp;
<img width="974" height="542" alt="image" src="https://github.com/user-attachments/assets/7ebe4478-26c4-4962-a7fb-cf92bc4c0b89" />

<img width="959" height="520" alt="image" src="https://github.com/user-attachments/assets/1bac0d3a-1099-4c92-8b3f-ea2fb166260f" />

<img width="976" height="541" alt="image" src="https://github.com/user-attachments/assets/e20d48cc-ee51-4f8d-93da-02b5e6c47d1b" />

<img width="973" height="529" alt="image" src="https://github.com/user-attachments/assets/8b066117-bee0-4cfa-a28b-5948131236d5" />

<img width="969" height="536" alt="image" src="https://github.com/user-attachments/assets/ac822dc6-718c-4b77-9925-fa4735282d04" />

<img width="973" height="537" alt="image" src="https://github.com/user-attachments/assets/9f5d0020-122f-42a7-9fae-8a28bf5b8452" />

<img width="963" height="538" alt="image" src="https://github.com/user-attachments/assets/a703129f-0cff-4326-bab5-fbe99d8653c0" />

<img width="959" height="530" alt="image" src="https://github.com/user-attachments/assets/75fbd1b8-df51-4b8f-a8a4-b3e54ca312d9" />

<img width="967" height="531" alt="image" src="https://github.com/user-attachments/assets/3c074618-2319-494d-a13a-5a92f2757473" />

<img width="961" height="527" alt="image" src="https://github.com/user-attachments/assets/da5362d5-1c30-4b07-8b8a-f655f03252b6" />





&nbsp;




