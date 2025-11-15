# EXPERIMENT-2-OPTICAL-COMMUNICATION
## 🔍 EX.NO: 2 – Verification of Fiber Losses

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables 

**Theory:**  
- Losses due to absorption, scattering, bending  
- Plastic fiber loss ~180 dB/km  
- Bending loss increases with reduced loop diameter  

**Procedure:**  
- Setup for 660nm and 950nm measurements  
- Measure output voltages for 1m and 3m fibers  
- Calculate attenuation \( a \) using:  
V1/V2 = e [ -a (L1+L2 ) ] 
- Bend fiber and record output vs diameter  
<img width="815" height="431" alt="opt-exp-2" src="https://github.com/user-attachments/assets/ed5ffd1c-a1fd-4f8d-841f-9697eb58a1a7" />

**Tabulation:**

### Propagation Loss

| Fiber Length | Input Amplitude (V) | Output Amplitude (V) |
|--------------|---------------------|------------------------|
|      1        |       5              |                10
|   0.5         |     5               |                14     |


### Bending Loss

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|---------------------|------------------------|
|     1 for 8cm             |      5               |         10.3
|     0.5 for 6.4cm    |      5          |     9.56               |

### calculation
![30bac8bc-c63a-4c58-a464-9690cff5fa10](https://github.com/user-attachments/assets/799adfd4-503e-467d-8a66-b092381826a8)


**Result:**  
Attenuation and bending loss characteristics verified.
The propagation (transmission) loss was measured over different lengths of the fiber for two wavelengths (660 nm & 950 nm) and found to increase with length, confirming the expected attenuation behaviour.

The bending loss was observed by varying the loop diameter of the fiber and measuring output amplitude — as the bend diameter decreased, the output dropped, verifying increased bending loss.

Hence, the aim of measuring both propagation loss and bending loss characteristics of the fiber was achieved.



---
