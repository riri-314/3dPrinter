# Vertex K8400
## Intro
Using Prusaslicer on the computer. The printer is runing marlin.

## Prusa Slicer
Plater menu is used to place the part on the plater and simple settings like support and infill. Print settings is unique to each print. Filament settings is unique to each filament. Printer settings is unique to each printer. 

## 3mf file
3mf is a archive file containing the 3D modele and some print propreties. 3mf is a replacement to stl files.

## How to print
-Start the printer and connect to Octopie via the web interface. Preheat the bed and extruder.
-Prepare the plater. Check if the axis need oil.
-Open the 3D model in PrusaSlicer and place it on the plater.
-In the tab "Print settings", set the fill density, skirt and supports. 20% infill is often enough. More option for the supports are available in the "Plater" tab.
-In the "Filament Settings" tab Choose the appropriate filament preset or creat a new one based on the information given by the filament manufacturer. 
  ProTips: start with FilamentSettings/ExtrusionMultiplier below 1 and incrase if necessary. You will need to toggle the advanced settings to acces it.
-Update the printer settings in the "Printer settings" tab if necessary.
-Hit the slice button and upload to Octopie, you should be able to upload the gcode file to octipie directly via Prusa Slicer.
-Start the printjob via Octopie
-Wait and hope for the best.

## Printing Tips
- FilamentSettings/ExtrusionMultiplier is used to reduce/raise the flow of material of the extruder, can be changed for each filament
- PrinterSettings/MachineLimits/MaximumFeedRateE is used to reduce/raise the maximum flow of material out of the extruder
- Do not forget to regulary oil the axis, specially the X axis
