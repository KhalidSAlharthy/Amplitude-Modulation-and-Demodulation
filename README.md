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

1. Message signal generation
   [image alt](<img width="543" height="513" alt="Message signal generation" src="https://github.com/user-attachments/assets/2e5e1359-b5ba-4813-96f1-07a2b1e2478c" />)




