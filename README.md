# Applied_Electronic_Circuit_Lab-En(May 2022 – Jun 2022)

&nbsp;

## 🧠 Rehabilitation Completion Detector

&nbsp;

## 📑 Table of Contents

1. [📌 Project Overview](#1--Project-Overview)  
2. [🔧 Components](#2--Components)  
3. [💻 Technologies](#3--Technologies)  
4. [🧭 동작 흐름 요약](#4--동작-흐름-요약)   

   
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


