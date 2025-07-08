# Wilkinson 4-Way Power Divider



The goal is to design, simulate, and analyze a Wilkinson 4-way power divider operating in the X-band (8–12 GHz), with optimal performance centered around 10 GHz.

## Substrate Details


<img width="320" alt="image" src="https://github.com/user-attachments/assets/9ef6c1d2-8757-428b-86c5-83d48a9b39d7" />


## Design Architecture
The design consists of two stages of Wilkinson 2-way dividers to create a 4-way configuration. Each stage uses:
Quarter-wave microstrip transmission lines, calculated for center frequency of 10 GHz.


Isolation resistors of 100 Ω between branch outputs.


## Component Overview 


<img width="613" alt="image" src="https://github.com/user-attachments/assets/034c6568-f7c8-469c-aab7-f54f33198706" />



## Circuit Schematic


<img width="746" alt="image" src="https://github.com/user-attachments/assets/bff053b6-bb62-4e66-b7fb-14a5f2ceac82" />







 ## S-Parameter Setup Block and Substrate Definition

 
<img width="458" alt="image" src="https://github.com/user-attachments/assets/7729a4eb-e9f3-472c-8f18-4da4b33d80ae" />

 


## Simulation Results (S-Parameter Plots)


<img width="759" alt="image" src="https://github.com/user-attachments/assets/25967996-6620-43c3-b2df-e95f91d20f4a" />



The Wilkinson 4-way power divider exhibits excellent input matching (S11 < –40 dB), equal power division (~–6.2 dB), and high isolation between output ports (< –30 dB) at the center frequency of 10 GHz.

## Smith Chart of Reflection Coefficients


<img width="435" alt="image" src="https://github.com/user-attachments/assets/700355ef-2fbb-47a5-a66a-94d296a216e0" />


A trace centered near the origin (center of the chart) at 10 GHz, which corresponds to perfect matching (S11 ≈ 0 or < -30 dB).


## Polar Plot


<img width="435" alt="image" src="https://github.com/user-attachments/assets/21180a01-bf8d-4c16-915c-d6073c6160b9" />

The S[1,1] trace forms a small closed loop near the center, indicating excellent input matching with minimal reflection around the center frequency (10 GHz).

## Performance Analysis (From S-Parameter Plots)
 Observations @ ~10 GHz:


<img width="538" alt="image" src="https://github.com/user-attachments/assets/797ff447-cb8f-47b0-ba6d-7e898042e0d0" />

 

## Advantages of Design
 Compact layout using microstrip lines on a low-loss substrate.


 Excellent isolation due to Wilkinson topology and 100 Ω resistors.


 Broadband behavior centered around 10 GHz.


Suitable for phased array, radar, and microwave systems.



In conclusion, The designed Wilkinson 4-way divider meets key performance targets for X-band operation:
Accurate -6 dB power split across four outputs.


High isolation and excellent return loss.


Fabrication-ready on RT/duroid 5880, ideal for high-frequency use.



TOOL USED: uSimmics (QUCS Studio)
