# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
<img width="1600" height="1077" alt="image" src="https://github.com/user-attachments/assets/1859d276-a73e-4ce3-ae20-e7a6c3bfede3" />


## SIMULATION CIRCUIT DIAGRAM
<img width="1600" height="1046" alt="image" src="https://github.com/user-attachments/assets/d36795e6-1e40-44b1-99b4-0b1e595162b8" />


## OUTPUT WAVEFORM

<img width="1600" height="1158" alt="image" src="https://github.com/user-attachments/assets/b3cf543f-478d-4156-9446-e0c8ff578ab3" />


## MODEL GRAPH
<img width="1600" height="1046" alt="image" src="https://github.com/user-attachments/assets/dd516af4-827d-42ca-82b2-be8f8da49bd0" />


---

## DESIGN
<img width="1600" height="773" alt="image" src="https://github.com/user-attachments/assets/15df900c-a9b9-471f-881d-07f9e0279d26" />

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-27 at 7 07 23 PM](https://github.com/user-attachments/assets/90e33815-dac7-4661-b634-21de5bc79b85)


---

## OUT PUT WAVEFORM AND DISCUSSION 

]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]]
<img width="1600" height="1116" alt="image" src="https://github.com/user-attachments/assets/bee82ab9-5bbd-438d-86d3-67770aaf2f20" />


---

 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-27 at 6 53 40 PM](https://github.com/user-attachments/assets/93ec5781-bcb2-469e-983f-9cbf16ab8152)

## SIMULATION CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-27 at 7 57 16 PM](https://github.com/user-attachments/assets/881b3de0-8ada-4891-a134-d1df76d29228)

## OUTPUT WAVEFORM
![WhatsApp Image 2025-11-27 at 7 57 39 PM](https://github.com/user-attachments/assets/fbe412c1-46a8-4117-8884-1fb3cddb02dc)


## MODEL GRAPH

<img width="1005" height="382" alt="image" src="https://github.com/user-attachments/assets/22925efc-4abc-4fad-90d5-94f3348c3c0b" />

---

## DESIGN
<img width="1600" height="773" alt="image" src="https://github.com/user-attachments/assets/632c3318-eca3-4d7c-92d2-b2f48e97a743" />

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-27 at 7 07 37 PM](https://github.com/user-attachments/assets/7eb07895-e3cb-4409-b983-4d801c7b9964)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-27 at 7 02 47 PM](https://github.com/user-attachments/assets/0d5c59ef-8925-437b-89cd-7107894a27a4)

---

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-27 at 6 54 04 PM](https://github.com/user-attachments/assets/1627d2c5-17e2-43b0-9580-bf981af5a47d)

## SIMULATION CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-27 at 7 59 21 PM](https://github.com/user-attachments/assets/a813d45c-5591-484e-8d86-fc0b83825f26)

## OUTPUT WAVEFORM

![WhatsApp Image 2025-11-27 at 7 59 35 PM](https://github.com/user-attachments/assets/9f169376-74cd-45e5-93d5-2d2554c76742)

## MODEL GRAPH

<img width="1055" height="537" alt="image" src="https://github.com/user-attachments/assets/f5eec55a-c00c-4eaf-a680-81ba95f66490" />


---

## DESIGN

<img width="1551" height="1600" alt="image" src="https://github.com/user-attachments/assets/8176eebc-d1e8-424c-97d5-678bf2cb55f8" />

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
![WhatsApp Image 2025-11-27 at 7 07 54 PM](https://github.com/user-attachments/assets/7ffb9c79-45d5-4320-9f2a-3b8aba9adf42)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-27 at 7 02 58 PM](https://github.com/user-attachments/assets/55dda86e-c3ce-4477-98e7-f44f856774da)

---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
