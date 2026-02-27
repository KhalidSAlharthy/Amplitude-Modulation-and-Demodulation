# Amplitude-Modulation-and-Demodulation
MATLAB Simulink implementation of Amplitude Modulation and Demodulation demonstrating signal generation, modulation, and recovery using LPF.



## 📌 Overview

This project demonstrates the implementation of Amplitude Modulation (AM) and Demodulation using MATLAB Simulink.

The objective is to design a complete communication system that:
- Generates a message signal and carrier signal
- Performs amplitude modulation
- Recovers the original signal using demodulation techniques

---

## 🎯 Objectives

- Design an AM modulator in Simulink
- Design an AM demodulator
- Analyze signal behavior at each stage of the system

---

## 🔧 Components Used

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

## 📊 Results


  Message signal generation:
     <img width="543" height="513" alt="Message signal generation" src="https://github.com/user-attachments/assets/634d7c64-69c8-4cab-a496-f4f56803bcbf" />
---

   Carrier signal generation:
     <img width="581" height="543" alt="Carrier signal generation" src="https://github.com/user-attachments/assets/33d9452a-f65f-45c0-9f86-0f7c2e2f41df" />

---


   AM modulated waveform:
   <img width="565" height="541" alt="AM modulated waveform" src="https://github.com/user-attachments/assets/769262d7-712a-4582-b0f2-66baa61bf181" />

---

   Accurate recovery of the original message signal:
   <img width="686" height="642" alt="Accurate recovery of the original message signal" src="https://github.com/user-attachments/assets/f25bfb67-e933-4fd3-a575-59cf6098cc01" />






