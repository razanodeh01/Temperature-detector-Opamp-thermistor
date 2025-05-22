# 🌡️ Temperature Detector Using Op-Amps and Thermistor

## 🛠️ Project Summary

This project focuses on designing and analyzing a **temperature detection circuit** using:
- A **20KΩ thermistor**.
- Three **LM324 operational amplifiers** as comparators.
- **LED indicators** (or diodes) for temperature thresholds.

The circuit activates:
- 🔴 **Red LED** when the temperature exceeds the upper limit.
- 🟢 **Green LED** when it drops below the lower limit.
- No LED if within the safe range.


## 🧪 Project Components & Flow

### 🔧 Hardware Components
- LM324 Op-Amps.
- Thermistor 20K@25°C.
- D1N4002 Diodes / LEDs.
- Resistors (including Rs = 20KΩ, 22KΩ, 25KΩ).
- VPWL (Voltage Pulse Source).

### 📐 Procedure Overview
1. **Practical Testing**:
   - Constructed the circuit physically and measured outputs for various Rs values.
   - Identified LED status for each condition.
2. **Simulation Phase**:
   - Replaced LEDs with D1N4002.
   - Simulated circuit for Rs = 20K, 22K, 25K.
   - Used VPWL to simulate temperature variation.
   - Plotted Vo1(t), Vo2(t), Vo3(t).
3. **Analysis**:
   - Estimated upper and lower threshold temperatures from plots.
   - Compared simulated results with manual calculations.


## 📊 Results Summary

| Threshold | Simulated Value | Hand Calculation |
|-----------|------------------|-------------------|
| Vlt       | 4.1665 V         | 4.375 V           |
| Vut       | 4.9985 V         | 4.61 V            |
| Tl        | 20.65°C          | 23.89°C           |
| Tu        | 28.33°C          | 26.11°C           |


## 👥 Team Members
- [**Razan Abdelrahman**](https://github.com/razanodeh01)
- [**Omar Masalmah**](https://github.com/Omarmasalmah)
