# Description

The KTS1900GXAA-TA is an "ideal diode" type, low voltage drop, fast response power regulator device. It is designed to replace traditional Schottky diodes with low loss, fast response, and high efficiency. It is suitable for power switching, current control, and power OR-ing applications. The Raspberry Pi 5 is increasingly being used in low-power servers, such as: server as a web or database server, in automation or home server solutions, in remote monitoring systems, ... . In the case of a continuously operating device, it is particularly important that it does not stop due to a possible power failure. The KTS1900GXAA-TA enables intelligent merging of two different power sources so that the appropriate (more available or stable) source always supplies power to the device, without any backflow into the other supply. "Power OR-ing" means that the device automatically selects the appropriate power source and seamlessly switches from one source to another. When an input supply failure happens, the KTS1900 quickly detects the reverse current and quickly pulls down the MOSFET gate, leaving the body diode of the MOSFET to block the reverse current flow. Redundant power supplies can then service the load.

---

## Brochure

![](/img/1.jpg)

## Botton side

![](/img/3.jpg)

## Top side

![](/img/2.jpg)

---

## Functions

| Notation          | Description                                                                                                       |
|:------------------|:------------------------------------------------------------------------------------------------------------------|
| Input_Power_1     | Input power from Raspberry Pi 5 PSU adapter 1                                                                     |
| Input_Power_2     | Input power from Raspberry Pi 5 PSU adapter 2                                                                     |
| Output_Power      | Output Power to the Raspberry Pi 5                                                                                |
| LCD Display       | LCD Display PSU interface (2.54mm pin header)[^1]                                                                 |
| Controller        | Controlls the buzzer, fan, and logically measures the input power 1 and power 2 (voltage) (2.54mm pin header)[^1] |
| Console           | CP-NHCB-V1 PSU interface (2.54mm pin header)[^1]                                                                  |

[^1]: !!!Caution: pay attention to voltage polarity!!!

---

## KTS1900 Ideal Diode Features

- It does so with a very small voltage drop (20–30 mV) – much better than a traditional diode (e.g. 300–500 mV)
- Ideal Diode and Load Switch Controller with Reverse Input Protection
- With fast response time, which reduces the chance of downtime
- There is no heat generation problem because the loss is minimal
- Does not require external control as it works automatically

---

## Specifications

- Power leds indicator
- Based on KTS1900 ideal diode
- Switchable input power
- Controllable buzzer and fan
- Logically measures the input power 1 and power 2 interface with PC817C photocoupler (voltage)
- Provides power supply to the LCD display and CP-NHCB-V1
- USB-C interface
- Number of PCB layer: 2 layers
- PCB Compliant: ROHS
- 4x M2.5 mounting hole

---

## Applications

- The CP-NHPSU-V1 PCB is responsible for the power supply, it will always ensure that it is powered. Compatible with Raspberry Pi 5
- Always pay attention to the polarity before connecting them, make sure that you have connected them correctly before turning them on.
- Controller connection pinout: RPI-5 GPIO12 <---> CP-NHPSU-V1 BU; RPI-5 GPIO13 <---> CP-NHPSU-V1 FA; RPI-5 GPIO18 <---> CP-NHPSU-V1 P1; RPI-5 GPIO19 <---> CP-NHPSU-V1 P2
- No data connection, just power to the Raspberry Pi 5

---

## Release: V1.0
- [x] Initial release
- [ ] Problems

---

## Dimension

![](/img/4.jpg)

---

## Schematic

![](/img/5.jpg)

---

## BOM (Bill Of Materials)

[View](https://htmlpreview.github.io/?https://github.com/drcyberg/Leder_Station_Lamp_V1/blob/main/bom/l_s_l_b.html "View")

---

## Created by DrCyberg

[drcyberg@gmail.com](mailto:drcyberg@gmail.com)
