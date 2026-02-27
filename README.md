# Amplitude-Modulation-and-Demodulation
MATLAB Simulink implementation of Amplitude Modulation and Demodulation demonstrating signal generation, modulation, and recovery using LPF.



## 📌 Overview

This project demonstrates the implementation of Amplitude Modulation (AM) and Demodulation using MATLAB Simulink.

The objective is to design a complete communication system that:
- Generates a message signal and carrier signal
- Performs amplitude modulation
- Recovers the original signal using demodulation techniques

---

## Objectives

- Design an AM modulator in Simulink
- Design an AM demodulator
- Analyze signal behavior at each stage of the system

---

## Components Used

1. **Signal Generators (3x)**  
   Used to generate the message signal and carrier signals:
   - Message Signal: `sin(2πt)`
   - Carrier 1: `sin(2π10t)`
   - Carrier 2: `sin(2π10t)`

2. **Constant & Adder**  
   Used to apply a DC shift to the message signal before modulation.

3. **Product Blocks (2x)**  
   Used to multiply the message signal with the carrier signal during:
   - Modulation
   - Demodulation

4. **Low Pass Filter (LPF)**  
   Used to extract and recover the original message signal from the received waveform.

5. **Scopes (4x)**  
   Used for signal visualization during simulation:
   - Transmitted Signal Scope
   - Transmitter Output Scope
   - Carrier Signal Scope
   - Received Signal Scope

---

## Implemntation 




<img width="723" height="368" alt="لقطة الشاشة 2026-02-27 215233" src="https://github.com/user-attachments/assets/08472a5e-2189-4480-8443-ac217691a943" />





---



## Results

### 1.Message signal generation


   <img width="543" height="513" alt="Message signal generation" src="https://github.com/user-attachments/assets/2e5e1359-b5ba-4813-96f1-07a2b1e2478c" />


### 2.Carrier signal generation


   <img width="581" height="543" alt="Carrier signal generation" src="https://github.com/user-attachments/assets/2d23d4a7-efdb-437d-a9c1-0255ff3923d8" />


### 3.AM modulated waveform


   <img width="565" height="541" alt="AM modulated waveform" src="https://github.com/user-attachments/assets/3c8c082b-b80a-474f-a735-571cf4c7d1b0" />


### 4.Accurate recovery of the original message signal


  <img width="686" height="642" alt="Accurate recovery of the original message signal" src="https://github.com/user-attachments/assets/a83a755e-ebcc-4603-9c03-a849ddb40819" />


