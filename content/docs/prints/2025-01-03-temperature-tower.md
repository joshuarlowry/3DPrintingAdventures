---
title: "Temperature Tower"
date: 2025-01-03
type: docs
weight: 1
# Print Settings
printer: "Sovol SV06 Plus"  # Based on common settings for this type of print
gcode_file: "prints/2025-01-03-temperature-tower.gcode"  # Path to the GCode file relative to static/gcode/
slicer: "OrcaSlicer 2.2.0"      # Extracted from GCode
filament: 
  type: "PLA"   # Common for temperature towers
  brand: "Overture"  # Not found in GCode
  color: "Black"  # Not found in GCode
print_settings:
  nozzle_temp: "230-190"    # °C - Temperature range for tower
  bed_temp: "60"       # °C - From GCode
  layer_height: "0.2"   # mm - Standard for temp towers
  infill: "100"         # percentage - For temperature towers
  supports: false    # true/false
  adhesion: "none"       # none, brim, raft
print_time: "02:11:11"       # Duration - Not found in GCode
model_source: "https://www.printables.com/model/202778-temperature-tower-200-190-degrees"     # Common temp tower model
tags: ["calibration", "temperature-tower", "PLA"]
---

## Print Details
This is a temperature tower calibration print used to determine the optimal printing temperature for PLA filament. The tower starts at 230°C at the bottom and decreases by 5°C every 10mm up to 190°C at the top.

## Print Settings Notes
<!-- Any specific settings adjustments or special considerations -->

{{< gcode >}}

## Results
The temperature tower turned out better than expected and provided valuable insights into temperature-dependent behavior. The bridging tests were particularly informative, showing clear differences across temperatures. As the temperature decreased in 5°C increments from 230°C to 190°C, there were noticeable changes in stringing behavior, with less stringing occurring at higher temperatures.

## Issues and Solutions
<!-- Any problems encountered and how they were resolved -->

## Lessons Learned
<!-- What would you do differently next time? -->

## Gallery
<!-- Additional images of the print -->
