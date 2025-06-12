# ME 331 Project 6 – TT Motor Torque-Speed Characterization

This project experimentally determines the torque-speed relationship of a TT geared DC motor by measuring rotational speed under varying loads.


## Overview
To characterize the performance of the TT motor (a DC motor with an internal gear reduction), we experimentally measured motor speed and torque using a pulley system and varied hanging weights. Using video analysis, the RPM for each weight was computed, and the corresponding torque was calculated using the formula:

T = X * r [g·cm]

Where:
- `X` = hanging mass in grams
- `r` = radius of the pulley (in cm)

## Materials Used
- TT Geared DC Motor
- Pulley/wheel
- String (e.g., dental floss)
- Small weights
- Sharpie/sticker (for marking rotation)
- Ruler (for measuring radius)
- Stopwatch or high-FPS video (used iPhone 60 FPS)
- Excel (for torque-speed plot)
- Arduino for motor control (from week 8b setup)

## Procedure
1. Wired the TT motor using the circuit from the Week 8b lab.
2. Attached the pulley and suspended different weights using a long string.
3. Recorded videos of the pulley lifting the weights to measure rotational speed.
4. Counted revolutions and time from videos to calculate RPM.
5. Calculated torque for each weight.
6. Repeated for:
   - No-load (maximum speed)
   - Stall torque (motor doesn’t spin)
   - At least 3 intermediate loads
7. Recorded all data in an Excel spreadsheet.
8. Plotted torque vs. speed to visualize performance.

## Deliverables
- 📷 Three RPM-measurement videos (No-load, Stall, Intermediate)
- 📊 Screenshot of final torque-speed plot
- 📄 Excel sheet with raw data and calculated torque/RPM

## Results Snapshot
The motor exhibited an expected linear decrease in speed as torque increased. The stall torque corresponded to 0 RPM, and no-load gave the maximum speed.

## Bonus
Bonus task was to repeat the test at 3.3V supply and compare the curves. 

## Notes
This experiment demonstrates fundamental motor characteristics and highlights the trade-off between torque and speed in geared motors.

