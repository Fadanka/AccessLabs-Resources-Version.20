# AccessLabs Incubator Shaker

<p align="center">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Tray_Main%20Platform.jpg" alt="Tray main platform" width="47%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Motion%20Mechanism%20parts.jpg" alt="Motion mechanism parts" width="47%">
</p>

<p align="center">
  <strong>3D-printed incubator shaker</strong><br>
  ESP32-S3 controlled, motor-driven, modular, and designed for interchangeable lab vessel adapters.
</p>

<p align="center">
  <em>Status: prototype documented for replication and improvement.</em>
</p>

---

## Overview

This project is a compact shaker designed for incubator use, built around:

- a **3D-printed mechanical assembly**
- an **ESP32-S3 DevKitC-1** controller
- a **DC gear motor**
- a **DRV8871 motor driver**
- interchangeable adapters for **flasks**, **tubes**, and **plates**

The goal of this build is to provide a reproducible open hardware shaker that is easy to print, assemble, modify, and document.

---

## Features

- Modular 3D-printed design
- Interchangeable tray adapters
- ESP32-S3 based control
- PWM motor speed control
- Potentiometer-based user input
- LCD and RGB LED feedback
- Open documentation for replication and customization

---

## Bill of Materials

### 3D-printed parts

| Part name | Qty |
|---|---:|
| `Tray_Main Platform` | 1 |
| `Tray_Screws and nuts` | 2 |
| `Flask adapter_Lid` | 2 |
| `Flask adapter_Lid retainer` | 2 |
| `Plate adapter` | 1 |
| `Tube adapter_15 mL and 50 mL` | 1 |
| `Motion Mechanism_Tray Support Bracket` | 1 |
| `Motion Mechanism_Motor motion linker (6mm Shaft)` | 1 |
| `Motion Mechanism_Connecting Link` | 2 |
| `Motion Mechanism_Nut holders` | 2 |
| `Motion Mechanism_Screw holders` | 1 set |
| `Enclosure_Main Housing` | 1 |
| `Enclosure_Gear Motor Mount` | 1 |
| `Enclosure_Top Cover` | 1 |
| `Enclosure_Base Cover` | 1 |
| `Enclosure_Feet` | 1 set |

### Electronics

- ESP32-S3 DevKitC-1 microcontroller
- DRV8871 DC motor driver board
- 10K rotary potentiometer
- DC motor / gear motor
- DC barrel jack power connector
- 12V power cable
- LM2596 DC-DC buck converter
- Wiring, headers, and connectors as required by your build

### Tools and additional materials

- Strong instant glue
- M3 screws, nuts, and washers kit
- 608ZZ bearings (`8 mm x 22 mm x 7 mm`)
- Screwdriver set
- Soldering station

---

## Printing recommendations

For the **critical structural and motion parts**, use **PETG** or a similar durable filament.

### Recommended for PETG printing
- **Infill:** at least **50%**
- **Supports:** use where needed
- **Brim:** use where needed for better adhesion
- Remove supports and brims carefully before assembly

### Critical parts
- `Enclosure_Main Housing`
- `Enclosure_Feet`
- all motion mechanism parts
- `Tray_Main Platform`
- `Tray_Screws and nuts`

---

## Part gallery

<details>
<summary><strong>Show 3D part images</strong></summary>

<br>

### Tray and adapters

<p align="center">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Tray_Main%20Platform.jpg" alt="Tray main platform" width="30%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Plate%20adapter.jpg" alt="Plate adapter" width="30%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Tube%20adapter_15%20mL%20and%2050%20mL.jpg" alt="Tube adapter 15 mL and 50 mL" width="30%">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Flask%20adapter_Lids%20.jpg" alt="Flask adapter lids" width="30%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Flask%20adapter_Lid%20retainers.jpg" alt="Flask adapter lid retainers" width="30%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Tray_Screws%20and%20nuts.jpg" alt="Tray screws and nuts" width="30%">
</p>

### Motion mechanism

<p align="center">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Motion%20Mechanism%20parts.jpg" alt="Motion mechanism parts" width="60%">
</p>

### Enclosure

<p align="center">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Enclosure_Main%20Housing.jpg" alt="Enclosure main housing" width="30%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Enclosure_Top%20Cover.jpg" alt="Enclosure top cover" width="30%">
  <img src="https://raw.githubusercontent.com/Fadanka/AccessLabs-Resources-Version.20/baf2fe9cfbb54dcbefb2e4a2180c2807738f8826/hardware/Shaker/Images/Enclosure_Base%20Cover.jpg" alt="Enclosure base cover" width="30%">
</p>

</details>

---

## Assembly

## A. Print and sort all parts

Download the CAD/STL files and print all required parts.

After printing:
1. Remove all supports and brims.
2. Clean all holes and mating surfaces.
3. Sort the parts before starting assembly.

---

## B. Prepare the motion mechanism

### Parts involved
- `Motion Mechanism_Motor motion linker (6mm Shaft)`
- `Motion Mechanism_Connecting Link`
- `Motion Mechanism_Nut holders`
- `Motion Mechanism_Screw holders`
- `Motion Mechanism_Tray Support Bracket`

### Preparation
Glue **M3 nuts** and **608ZZ bearings** into their dedicated spaces.

### Instructions
1. Dry-fit each nut and bearing before using glue.
2. Apply a small amount of strong liquid glue around the outer wall of the nut or bearing pocket.
3. Insert the nut or bearing carefully.
4. Do **not** let glue enter:
   - threaded areas
   - bearing inner races
   - rotating surfaces
5. Let the glue set for about **30 minutes**.
6. Add a small finishing layer at the interstices if needed.
7. Let the assembly cure fully according to the glue manufacturer's instructions.

> **Note:** On the motor linker, the nut around the shaft area should remain free if that is required for your fit and motion.

---

## C. Prepare the enclosure

### Parts involved
- `Enclosure_Main Housing`
- `Enclosure_Gear Motor Mount`
- `Enclosure_Top Cover`
- `Enclosure_Base Cover`
- `Enclosure_Feet`

### Instructions
1. Install the bearings in the dedicated holes.
2. Mount the motor in the gear motor holder.
3. Check shaft alignment before tightening hardware.
4. Fit the top and base covers only after electronics testing is complete.

---

## D. Electronics assembly

### Main electronics
- ESP32-S3 DevKitC-1
- DRV8871 motor driver
- 10K potentiometer
- LM2596 buck converter
- DC motor
- 12V DC input connector

### Suggested workflow
1. Mount the motor and controller hardware inside the enclosure.
2. Install the DC power input.
3. Wire the motor to the motor driver.
4. Wire the driver control lines to the ESP32-S3.
5. Wire the potentiometer to the ESP32-S3 analog input.
6. Add the buck converter if voltage regulation is required for your logic electronics.
7. Verify all grounds are shared properly.

> Add a wiring diagram here when available.

---

## E. Firmware

The firmware acts as the control system for the shaker.

### Firmware behavior
- scans the I2C bus at startup
- initializes the LCD
- runs a short boot animation
- reads and averages potentiometer values
- maps the input to PWM motor speed
- estimates RPM for user display
- updates the LCD with:
  - speed percentage
  - approximate RPM
  - raw potentiometer value
- periodically displays a shaker activity message
- uses RGB LED feedback for status indication

### Speed control logic
A dead zone is used so the shaker remains reliably off at low potentiometer values.

- `0` to about `1264` → motor off
- above `1264` → linearly mapped to PWM output
- display shows an approximate RPM estimate without encoder feedback

---

## F. Software installation

### Using Arduino IDE
1. Open **Arduino IDE**
2. Go to **Tools**
3. Go to **Board**
4. Select **ESP32S3 Dev Module**
5. Select the correct serial **Port**
6. Open the shaker firmware sketch
7. Click **Verify**
8. Click **Upload**

> Add the firmware path or sketch link here once it is committed in the repository.

---

## G. Testing

Before final assembly:

1. Power the system without load.
2. Confirm the ESP32-S3 starts correctly.
3. Confirm the LCD initializes.
4. Confirm the potentiometer changes the displayed value.
5. Confirm the motor responds smoothly to PWM control.
6. Check for wobble, friction, or mechanical interference.
7. Stop immediately if:
   - bearings bind
   - parts rub against the enclosure
   - the motor mount shifts
   - the tray becomes unstable

---

## H. Final assembly

1. Install the tray support and motion mechanism.
2. Attach the tray platform.
3. Fit the required vessel adapter:
   - flask adapter
   - tube adapter
   - plate adapter
4. Route and secure all wiring.
5. Close the enclosure with the top and base covers.
6. Add the feet.
7. Run a final low-speed test before regular use.

---

## I. Operation

1. Power the shaker.
2. Place the correct adapter on the tray.
3. Load vessels symmetrically.
4. Increase speed gradually using the potentiometer.
5. Monitor for:
   - vibration
   - imbalance
   - slipping vessels
   - overheating

For best results:
- balance the load evenly
- avoid overloading one side
- start at low speed after every configuration change

---

## Safety

- Use the device on a stable, level surface.
- Do not operate with loose hardware.
- Do not touch moving parts during operation.
- Keep liquids away from exposed electronics.
- Verify adapter fit before placing samples.
- Disconnect power before maintenance or rewiring.
- Inspect glued nuts, bearings, and fasteners regularly.

---

## Known limitations

- RPM is estimated, not encoder measured
- assembly photos and wiring diagrams can still be expanded
- documentation may evolve as the mechanical design is refined

---

## Contributing

Improvements are welcome.

Typical contributions include:
- better assembly photos
- wiring diagrams
- firmware improvements
- adapter variants
- test data
- print optimization notes

---

## Citation / project note

If you use or adapt this design, consider citing the repository and linking back to the original project page.

---
