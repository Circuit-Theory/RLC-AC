<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
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
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Ioannis Vogiatzis, Professor<br>
</p>

<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-voyiatzis/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/ioannis-voyiatzis-7b5a6b88/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Christos Kampouris, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.syros.aegean.gr/en/staff/research-staff/phd-candidates/christos-kampouris" target="_blank">Academic Profile</a>
</p>

<p align="center">
  Co-supervisor: Georgios Antoniou, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/georgios-antoniou/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, June 2022
</p>

---

<p align="center">
  <img src="https://dwma4bz18k1bd.cloudfront.net/textbooks/RLC-series-circuit.jpg" width="250"/>
</p>

---

# README

## RLC Component Connections to AC Power Supply

This laboratory project explores the behavior of **RLC components** (Resistor, Inductor, Capacitor) when connected to an **alternating current (AC) power supply**.  
The project was conducted as part of the **Circuit Theory** course at the **University of West Attica**.

The primary objective is to analyze the **theoretical**, **simulated** (using Multisim), and **experimental** behavior of **RC** and **RL** components in both **series** and **parallel** configurations under AC voltage.

---

## Table of Contents

| Section | Folder                                                  | Description                                                  |
| ------: | ------------------------------------------------------- | ------------------------------------------------------------ |
|       1 | `assign/`                                               | Assignment material for the Circuit Theory course            |
|     1.1 | `assign/circuit theory rev2021_EXERCISE_3rd.pdf`        | Assignment description in English                            |
|     1.2 | `assign/θεωρία κυκλωμάτων rev2021_ΑΣΚΗΣΗ_3η.pdf`        | Assignment description in Greek                              |
|       2 | `docs/`                                                 | Documentation on RLC components connected to AC power supply |
|     2.1 | `docs/RLC-Component-Connections-to-AC-Power-Supply.pdf` | English documentation                                        |
|     2.2 | `docs/Συνδεσμολογίες-Εξαρτημάτων-RLC-σε-AC-Τάση.pdf`    | Greek documentation                                          |
|       3 | `multisim/`                                             | Circuit simulation files for AC RLC systems                  |
|     3.1 | `multisim/OscilloscopeRCParallel.ms14`                  | RC parallel circuit with oscilloscope                        |
|     3.2 | `multisim/OscilloscopeRCSerial.ms14`                    | RC series circuit with oscilloscope                          |
|     3.3 | `multisim/OscilloscopeRL2Parallel.ms14`                 | RL parallel circuit with oscilloscope                        |
|     3.4 | `multisim/OscilloscopeRLSeirial.ms14`                   | RL series circuit with oscilloscope                          |
|       4 | `README.md`                                             | Repository overview                                          |
|       5 | `INSTALL.md`                                            | Usage instructions                                           |

---

## 1. Key Modules

- **RC Component in Series**  
  Analysis of capacitor charging and discharging behaviors as frequency increases.

- **RL Component in Series**  
  Investigation of coil active resistance (**Xₗ**) and voltage fluctuations across a 3.3 mH inductor.

- **RC Component in Parallel**  
  Detailed analysis of parallel capacitor behavior.

- **RL Component in Parallel**  
  Detailed analysis of parallel inductor behavior.

---

## 2. Laboratory Equipment Used

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

## 3. Key Findings

### 3.1 Frequency Response (RC Series)

- As **frequency (f)** increases, the capacitor's active resistance (**Xc**) decreases:

$$
X_c = \frac{1}{2\pi f C} \quad (\text{capacitive reactance})
$$

- Resulting in an **increase in current (I)** through the circuit.

### 3.2 Frequency Response (RL Series)

- As frequency increases, the **current remains relatively constant**.
- The coil's active resistance (**X_L**) increases:

$$
X_L = 2\pi f L \quad (\text{inductive reactance})
$$

### 3.3 Phase Difference

- Oscilloscope readings confirmed **phase differences** between source voltage and component voltage.  
  Example: **10 ms difference at 100 Hz** for the capacitor.
