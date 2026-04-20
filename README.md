# Proiect-InkTime-TSC-

This project focuses on the development of a low-power, high-versatility smartwatch platform. Built around the nRF52840 SoC, the device combines a high-contrast E-paper display with advanced motion tracking and efficient power management, all integrated into a compact PCB form factor designed for wearable applications.

## Block diagram 
<img width="2131" height="1126" alt="Screenshot (1077)" src="https://github.com/user-attachments/assets/e07a1e33-20fc-4ca3-8726-7ea12e3ea11a" />

##Bill of Materials (BOM)
## Bill of Materials

| Reference Designators | Quantity | Description | Package | Value | Manufacturer | MPN |
|---|---|---|---|---|---|---|
| ANT1 | 1 | Antennas 2.45GHz ANTENNA | 2450AT18B100E_ANTC3216X140N | 2450AT18B100E | Johanson Technology | 2450AT18B100E |
| C1, C2, C17, C18 | 4 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 12pF | | |
| C1-EP-DR, C39 | 2 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 10uF | | |
| C2-EP-DR | 1 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 4.7uF/25V | | |
| C3, C4 | 2 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 1pF | | |
| C5, C7, C8, C12 | 4 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 100nF | | |
| C6, C14, C20, C21, C43 | 5 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 4.7µF | | |
| C9 | 1 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 820pF | | |
| C10, C13, C22 | 3 | Generic chip capacitor (N.C.) | NORDIC_NRF_3_RESC0201_L | N.C. | | |
| C11 | 1 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 100pF | | |
| C15 | 1 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 1.0µF | | |
| C16 | 1 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 47nF | | |
| C19, C24 | 2 | Generic chip capacitor | PERFECT_0402_0402 | 100nF / 10uF | | |
| C23 | 1 | SMD Capacitor X5R, 1500pF, 10%, 6.3V | GRM011R60J152KE01L_1_0201 | 1500pF | Murata | GRM011R60J152KE01L |
| C25, C33 | 2 | Generic chip capacitor | PERFECT_0402_0402 | 22uF | | |
| C27, C34, C42 | 3 | SMD Capacitor X5R, 6.3V | GRM011R60J152KE01L_2_CAPC0201X13N | 0.1uF | Murata | GRM011R60J152KE01L |
| C29, C30, C31, C32, C38 | 5 | SMD Capacitor X5R, 6.3V | GRM011R60J152KE01L_2_CAPC0201X13N | 1uF | Murata | GRM011R60J152KE01L |
| C37 | 1 | SMD Capacitor X5R, 6.3V | GRM011R60J152KE01L_2_CAPC0201X13N | 1500pF | Murata | GRM011R60J152KE01L |
| EPD_C1, EPD_C2, EPD_C6, EPD_C7, EPD_C8, EPD_C9, EPD_C10, EPD_C11, EPD_C12 | 9 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 1uF/50V | | |
| EPD_C5 | 1 | Generic chip capacitor | NORDIC_NRF_3_RESC0201_L | 0.1uF/50V | | |
| D2, D4, D5 | 3 | Diode Schottky 30V 500mA | SOD-123 | MBR0530 | ON Semiconductor | MBR0530 |
| D3 | 1 | ESD Protection TVS Diode Array | SOT-23-6 | USBLC6-2SC6Y | STMicroelectronics | USBLC6-2SC6Y |
| IC1 | 1 | Li-Ion/LiFePO4 Battery Charger IC | 8-DSBGA (1.6x1.1) | BQ25180YBGR | Texas Instruments | BQ25180YBGR |
| IC2 | 1 | Haptic Driver ERM/LRA | 9-BGA (1.44x1.44) | DRV2605YZFR | Texas Instruments | DRV2605YZFR |
| IC3 | 1 | Triaxial Low-g 12-bit Accelerometer | BMA423 | BMA423 | Bosch Sensortec | BMA423 |
| IC9 | 1 | Buck-Boost DC-DC Regulator I2C | 15-WL-CSP (1.4x2.3) | RT6160AWSC | Richtek | RT6160AWSC |
| J1 | 1 | FPC Connector 0.5mm 24-pin SMT | 503480-2400 | 503480-2400 | Molex | 503480-2400 |
| J2 | 1 | Tag-Connect Debug Adapter 6-pin | TC2030IDC | TC2030-IDC | Tag-Connect | TC2030-IDC |
| J4 | 1 | USB Type-C Connector 16P | KH-TYPE-C-16P | KH-TYPE-C-16P | Kinghelm | KH-TYPE-C-16P |
| L1 | 1 | Generic chip inductor | NORDIC_NRF_2_RESC0402_L | 3.9nH | | |
| L2 | 1 | Generic chip inductor | NORDIC_NRF_2_RESC0402_L | 10uH | | |
| L3 | 1 | Generic chip inductor | NORDIC_NRF_2_RESC0402_L | 15nH | | |
| L5 | 1 | Generic chip inductor | NORDIC_NRF_2_RESC0402_L | 68uH | | |
| L7 | 1 | SMD Inductor | INDC2016X100N | 0.47µH | TDK | FTC252012SR47MBCA |
| Q1 | 1 | P-Channel MOSFET | SOT-23 | 20V/4.2A/52mΩ | | DMG2305UX |
| Q3 | 1 | N-Channel MOSFET 30V 1.5A | SOT-323 (SC-70) | SI1308EDL-T1-GE3 | Vishay Siliconix | SI1308EDL-T1-GE3 |
| R1, R7, R8, R9, R2_EP_DR, R_PWR_EPD | 6 | Thin Film Resistor 0201 | 0201 | 10k | | |
| R1_EP_DR | 1 | Thin Film Resistor 0201 | 0201 | 0.47Ω | | |
| R1_USB, R2_USB | 2 | Thin Film Resistor 0201 | 0201 | 5.1k | | |
| R3, R4, R17, R18 | 4 | Thin Film Resistor 0201 | 0201 | 7.68k | | |
| R5 | 1 | Thin Film Resistor 0201 (Zero Ohm Jumper) | 0201 | 0Ω | | |
| R_TYPE_SEL | 1 | Thin Film Resistor 0201 | 0201 | 2.2Ω | | |
| SJ1 | 1 | SMD Solder Jumper | JUMPER_SJ | - | | |
| SW_DN, SW_ENT, SW_UP | 3 | Tactile Switch SMD | SW_EVP-AKE31A | EVP-AKE31A | Panasonic | EVP-AKE31A |
| TP3, TP4, TP5, TP6, TP_3.3V, TP_3V3, TP_BAT_GND, TP_GND, TP_ON, TP_OP, TP_SCL, TP_SDA, TP_VBAT, TP_VREG | 14 | Test Pad | TP20R | - | | |
| U1 | 1 | nRF52840 Bluetooth SoC | AQFN50P700X700X85 | NRF52840_QF | Nordic Semiconductor | NRF52840-QIAA |
| U3 | 1 | 1-Cell/2-Cell Fuel Gauge with ModelGauge | TDFN-8 (2x2) | MAX17048G+T10 | Analog Devices / Maxim | MAX17048G+T10 |
| X1 | 1 | Crystal Oscillator | 2016 | 32MHz | | |
| X2 | 1 | Crystal Oscillator RTC | 3215 | 32.768kHz | | |

## Hardware  Functionality

### ### 1. Central Processing Unit: nRF52840
The **nRF52840 SoC** was selected as the system's brain due to its balance between performance and energy efficiency. 
* **Key Features:** ARM Cortex-M4F processor, native USB support, and a versatile GPIO multiplexer for SPI/I2C routing.
* **Timing:** The system utilizes a **32 MHz crystal** for high-speed operations and a **32.768 kHz crystal** for maintaining accurate time in sleep modes.
* **Connectivity:** Integrated RF frontend with a **2.4 GHz ceramic chip antenna** for Bluetooth Low Energy (BLE) communication.

---

### ### 2. Power Management & Charging
To ensure reliable portable operation, the device features a sophisticated power rail architecture:
* **USB-C Interface:** Handles both 5V power input and data communication, protected against transients via the **USBLC6-2SC6Y** ESD suppressor.
* **Charger & PMIC:** The **BQ25180** manages LiPo battery charging cycles and system power path selection.
* **Regulation:** An **RT6160 DC/DC converter** provides a stable voltage rail with high efficiency, supported by a network of decoupling LC filters.
* **Fuel Gauge:** A **MAX17048** sensor monitors the battery's State of Charge (SoC) via I2C, allowing for precise percentage estimation.

---

### ### 3. E-Paper Display Subsystem
For the visual interface, a **1.54-inch E-Paper (EPD)** was implemented through a 24-pin FPC connector.
* **Drive Circuit:** A custom-designed discrete booster circuit (MOSFETs, Schottky diodes, and capacitors) generates the high voltages required for the electrophoresis process.
* **Control:** Driven via **SPI**, using dedicated lines for **Data/Command (DC)**, **Reset (RST)**, and a **Busy** signal to monitor the refresh status.
* **Rationale:** The display's ability to maintain an image without power is critical for the device's "always-on" wearable goal.

---

### ### 4. Inertial Measurement & Haptics
* **Motion Sensing:** The **BMA421 IMU** is utilized for activity tracking. It communicates via **I2C** and features two programmable interrupt pins (`INT1`, `INT2`) to wake the MCU upon detecting movement or gestures.
* **Vibration Feedback:** Haptic alerts are managed by the **DRV2605** driver. This I2C-controlled chip offloads complex vibration pattern generation from the MCU, driving the haptic motor with precision.

---

### ### 5. User Input & Debugging
* **Physical Interface:** Three tactile switches (**Up, Enter, Down**) are mapped to GPIOs for menu navigation and user interaction.
* **Development Access:** A **TC2030-IDC Tag-Connect** footprint provides a 6-pin SWD (Serial Wire Debug) interface for flashing firmware and real-time debugging (`SWDIO`, `SWDCLK`, `SWO`).

---

## ## Peripheral Pin Mapping

| Component | Protocol | nRF52840 Pins | Purpose |
| :--- | :---: | :--- | :--- |
| **E-Paper Display** | SPI | SCK, MOSI, CS, DC | Graphics and UI updates |
| **BMA421 IMU** | I2C | SDA, SCL, INT1/2 | Step counting and wake-up |
| **MAX17048 Gauge** | I2C | SDA, SCL, ALERT | Battery health monitoring |
| **DRV2605 Haptic** | I2C | SDA, SCL, EN | Haptic alerts/vibration |
| **Buttons** | GPIO | P0.xx, P0.xx, P0.xx | User navigation |
| **Debug Port** | SWD | SWDIO, SWDCLK, RST | Programming and Debug |

## ## Design Challenges & Debugging Log

During the PCB layout phase, several technical challenges were encountered and addressed to ensure the manufacturability and reliability of the smartwatch.

### ### 1. Copper Width Violations (Net Class: Power)
A significant number of DRC (Design Rule Check) errors were related to **Copper Width** within the `trasee-de-alimentare` (power traces) net class. 
* **The Issue:** The design rules initially required a 0.3 mm width for all power traces to handle current capacity. However, many SMD components (such as the BMA421 IMU and the nRF52840 itself) have ultra-fine pads that cannot physically accommodate a 0.3 mm trace without causing short circuits.
* **The Solution:** The rules were adjusted to allow a minimum width of 0.15 mm at the entry point of the pads (neck-down technique), while maintaining the preferred 0.3 mm width for the main distribution lines to ensure low impedance.

### ### 2. Complex Routing & Unrouted Airwires
Despite migrating to a **4-layer PCB stack-up**, approximately 10 airwires remained unrouted in the final manual pass. 
* **The Challenge:** Routing these specific signals on the Top or Bottom layers created critical violations, such as **Overlap (wire-on-wire)** or **Via-to-Via clearance errors**. 
* **Decision Rationale:** To prioritize signal integrity and avoid manufacturing defects (like drill breakouts or short circuits caused by overcrowded vias), these traces were left for a final optimized iteration. Forced routing in these congested areas would have compromised the solid Ground Plane (Layer 2) or created parasitic capacitance issues.

### ### 3. Mechanical Constraints & Clearance
As shown in the board dimensions (**46.00 mm x 35.00 mm**), the compact wearable form factor forced a high component density. Several **Smd-Hole** and **Board Outline Clearance** errors were resolved by manually shifting components and adjusting the copper-to-edge distance to meet JLCPCB's manufacturing tolerances.
