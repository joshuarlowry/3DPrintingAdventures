---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
type: docs
weight: 1
draft: true
# Print Settings
printer: ""  # Your 3D printer model
gcode_file: ""  # Path to the GCode file relative to static/gcode/
slicer: ""      # Slicer used (e.g., PrusaSlicer, Cura, etc.)
filament: 
  type: ""   # PLA, PETG, ABS, etc.
  brand: ""  # Manufacturer
  color: ""  # Color of the filament
print_settings:
  nozzle_temp: ""    # °C
  bed_temp: ""       # °C
  layer_height: ""   # mm
  infill: ""         # percentage
  supports: false    # true/false
  adhesion: ""       # none, brim, raft
print_time: ""       # Duration
model_source: ""     # URL or creator attribution
tags: []
---

## Print Details
<!-- Brief description of what you're printing and why -->

## Print Settings Notes
<!-- Any specific settings adjustments or special considerations -->

## Results
<!-- How did it turn out? Include images if possible -->

## Issues and Solutions
<!-- Any problems encountered and how they were resolved -->

## Lessons Learned
<!-- What would you do differently next time? -->

## Gallery
<!-- Additional images of the print --> 