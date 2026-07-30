# AC to DC Regulated Power Supply

## Overview

This project presents the design, simulation, and practical implementation of a regulated AC-to-DC power supply. The system converts a 220 V AC mains supply into a stable +15 V DC output suitable for powering electronic circuits such as sensors, microcontrollers, and laboratory equipment.

The project was completed as part of the Electrical Engineering and Electronics course and includes both simulation using LTspice and practical hardware implementation.

---

## Objectives

- Convert 220 V AC to regulated 15 V DC.
- Design and simulate the circuit using LTspice.
- Build and test the circuit on a breadboard.
- Analyze waveforms at every stage of the power conversion process.
- Implement an adjustable DC power supply using the LM117 voltage regulator.

---

## Features

- 220 V AC input
- Step-down transformer (220 V → 24 V)
- Full-wave bridge rectifier
- Capacitor filtering
- LM7815 linear voltage regulation
- Stable +15 V DC output
- Adjustable output using LM117 (Task 2)

---

## Components Used

| Component | Purpose |
|-----------|----------|
| 220V/24V Transformer | Voltage step-down |
| Bridge Rectifier | AC to DC conversion |
| 1000 µF Capacitor | Ripple filtering |
| 100 µF Capacitor | Output smoothing |
| 0.1 µF Capacitor | Noise suppression |
| LM7815 | Fixed +15 V regulator |
| LM117 | Adjustable voltage regulator |
| Potentiometer | Output voltage adjustment |
| Fuse | Overcurrent protection |
| Heat Sink | Regulator cooling |

---

## System Block Diagram

AC Input (220V)

↓

Step-Down Transformer

↓

Bridge Rectifier

↓

Filter Capacitor

↓

Voltage Regulator

↓

Regulated DC Output (+15V)

---

## Circuit Operation

### 1. Step-Down Transformer

The transformer reduces the mains voltage from 220 V AC to approximately 24 V AC while providing electrical isolation.

### 2. Bridge Rectifier

A full-wave bridge rectifier converts the AC signal into pulsating DC by utilizing four diodes.

### 3. Filtering

A 1000 µF capacitor smooths the pulsating DC and significantly reduces ripple voltage.

### 4. Voltage Regulation

The LM7815 linear regulator provides a stable and constant +15 V DC output.

### 5. Adjustable Output

The LM117 regulator and potentiometer allow the output voltage to be adjusted over a wide range.

---

## Simulation

The complete circuit was simulated using **LTspice** before hardware implementation.

Simulation verified:

- AC input waveform
- Transformer output
- Full-wave rectification
- Ripple reduction
- Stable regulated output

---

## Practical Implementation

The circuit was assembled on a breadboard and tested using laboratory equipment.

Measurements confirmed:

- Correct transformer output
- Proper bridge rectification
- Reduced ripple after filtering
- Stable +15 V regulated output
- Adjustable output using LM117

---

## Results

The practical implementation closely matched the LTspice simulation results.

The final power supply successfully delivered:

- Stable +15 V DC output
- Low ripple voltage
- Reliable operation
- Adjustable output for Task 2

---

## Project Files

```
Documentation/
Images/
LTspice/
Videos/
Hardware/
```

---

## Future Improvements

- PCB implementation
- Higher current capability
- Short-circuit protection
- Over-temperature protection
- Switching regulator version for higher efficiency

---

## Author

**Aliaa **
German International University (GIU)
Electrical Engineering and Electronics Project
