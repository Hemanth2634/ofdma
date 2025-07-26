#  OFDMA Simulation in Python

This repository provides a simple simulation of a **multi-user OFDMA (Orthogonal Frequency Division Multiple Access)** system in Python. It includes:

**QPSK modulation and demodulation**
**Cyclic prefix (CP) handling**
**Rayleigh fading channel model**
**OFDM modulation/demodulation using IFFT/FFT**
**Bit Error Rate (BER)** evaluation per user

---

##  Features

QPSK modulation/demodulation  
Rayleigh fading per-subcarrier  
Cyclic Prefix (CP) insertion/removal  
Per-user subcarrier allocation  
Multi-user support  
BER computation per user

---

## Simulation Parameters

Number of users: 2  
Subcarriers per user: 4  
Total OFDM subcarriers: 8  
Cyclic Prefix length: 2  
Modulation: QPSK  
Channel: Rayleigh fading + AWGN  
OFDM symbols per user: 10

---

## How to Run

### Requirements

Python 3.x
NumPy

### Run the simulation

bash
python ofdma_simulation.py
