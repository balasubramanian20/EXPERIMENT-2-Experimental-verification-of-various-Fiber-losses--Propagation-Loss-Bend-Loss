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
<img width="815" height="431" alt="opt-exp-2" src="https://github.com/user-attachments/assets/8c712617-6d51-4ca3-882d-33be456c1cb7" />

**Theory:**  
- Losses due to absorption, scattering, bending  
- Plastic fiber loss ~180 dB/km  
- Bending loss increases with reduced loop diameter
- <img width="446" height="183" alt="image" src="https://github.com/user-attachments/assets/e588ad83-fd78-476e-947b-6877bf5c2137" />
<img width="476" height="192" alt="image" src="https://github.com/user-attachments/assets/fdedd762-e4f8-40a0-9706-d6e629522984" />

<img width="459" height="189" alt="image" src="https://github.com/user-attachments/assets/7495ce10-9901-4e47-8390-c03f9396465a" />


**Procedure:**  
- Setup for 660nm and 950nm measurements  
- Measure output voltages for 1m and 3m fibers  
- Calculate attenuation \( a \) using:  
V1/V2 = e [ -a (L1+L2 ) ] 
- Bend fiber and record output vs diameter  

**Tabulation:**

### Propagation Loss

| Fiber Length | Input Amplitude (V) | Output Amplitude (V) |
|--------------|---------------------|------------------------|
|      1        |         5            |          10
|     0.5       |         5             |          14         |


### Bending Loss

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|---------------------|------------------------|
|         1 for 8cm |      5               |   10.3                    
|   0.5 for 6.4cm   |       5              |   9.56              |   

### calculation
![e4aec2de-b72b-489c-9d92-61e2bb141e00](https://github.com/user-attachments/assets/738f6287-812f-482e-8236-d802af62d647)


**Result:**

Attenuation and bending loss characteristics verified.
The propagation (transmission) loss was measured over different lengths of the fiber for two wavelengths (660 nm & 950 nm) and found to increase with length, confirming the expected attenuation behaviour.

The bending loss was observed by varying the loop diameter of the fiber and measuring output amplitude — as the bend diameter decreased, the output dropped, verifying increased bending loss.

Hence, the aim of measuring both propagation loss and bending loss characteristics of the fiber was achieved.



---
