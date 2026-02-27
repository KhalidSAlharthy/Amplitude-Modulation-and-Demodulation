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

The simulation successfully demonstrates:
- Message signal generation
  ![image alt](<img width="543" height="513" alt="1" src="https://github.com/user-attachments/assets/f0c83636-c521-4164-88ac-7155fce110e5" />)
---

- Carrier signal generation
   ![image alt](<img width="581" height="543" alt="2" src="https://github.com/user-attachments/assets/37f6c492-c528-400a-82b8-c1e3f0e0b9d5" />)
---


- AM modulated waveform
   ![image alt](<img width="565" height="541" alt="3" src="https://github.com/user-attachments/assets/892e10e3-5e4b-4bbf-bf21-5f192bfb00cb" />)
---


- Accurate recovery of the original message signal
  ![image alt](  <img width="686" height="642" alt="4" src="https://github.com/user-attachments/assets/03e30118-294e-4de3-a0fe-ce1976ced133" />)





