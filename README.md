<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Circuit Theory</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  RLC Component Connections to AC Power Supply
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  Supervisor: Christos Kampouris, Laboratory Teaching Staff<br>
  Co-supervisor: Georgios Antoniou, Laboratory Teaching Staff
</p>

<p align="center">
  Athens, June 2022
</p>


## Project Overview

This laboratory project explores the behavior of **RLC components** (Resistor, Inductor, Capacitor) when connected to an **alternating current (AC) power supply**.  
The project was conducted as part of the **Circuit Theory** course at the **University of West Attica**.

The primary objective is to analyze the **theoretical**, **simulated** (using Multisim), and **experimental** behavior of **RC** and **RL** components in both **series** and **parallel** configurations under AC voltage.

---

## Table of Contents

| Section | Title          | Description                                    |
|--------:|----------------|------------------------------------------------|
| assign  | Assignment     | Contains assignments and tasks                 |
| docs    | Documentation  | Project documentation, guides, and notes       |
| multisim     | Multisim    | All souce multisim files implementing the circuits      |

## Key Modules

- **RC Component in Series**  
  Analysis of capacitor charging and discharging behaviors as frequency increases.

- **RL Component in Series**  
  Investigation of coil active resistance (**Xₗ**) and voltage fluctuations across a 3.3 mH inductor.

- **RC Component in Parallel**  
  Detailed analysis of parallel capacitor behavior.

- **RL Component in Parallel**  
  Detailed analysis of parallel inductor behavior.

---

## Laboratory Equipment Used

- **Breadboard** for circuit assembly
- **AC Power Supply** (1 Vrms, 1 Hz – 100 kHz)
- **Oscilloscope** (dual-channel) for measuring sine waves and phase differences
- **Multimeters**  
  - Digital (voltmeter)  
  - Analog (ammeter)
- **Components**  
  - Resistors: 1 kΩ, 2.2 kΩ  
  - Capacitor: 470 nF  
  - Inductor: 3.3 mH  
  - Connection cables

---

## Key Findings

### Frequency Response (RC Series)

- As **frequency (f)** increases, the capacitor's active resistance (**Xc**) decreases:

$$
X_c = \frac{1}{2\pi f C} \quad (\text{capacitive reactance})
$$

- Resulting in an **increase in current (I)** through the circuit.

### Frequency Response (RL Series)

- As frequency increases, the **current remains relatively constant**.
- The coil's active resistance (**X_L**) increases:

$$
X_L = 2\pi f L \quad (\text{inductive reactance})
$$


### Phase Difference

- Oscilloscope readings confirmed **phase differences** between source voltage and component voltage.  
  Example: **10 ms difference at 100 Hz** for the capacitor.

---
## Installation Guide

Clone this repository to your local machine. 
```bash
git clone https://github.com/Circuit-Theory/RLC-AC.git
``` 
