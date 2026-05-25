# GCode Visualizer
I built a tool that reads a 3D printer gcode file and 
analyses what is inside it.

## What it does
- Reads the gcode file and extracts all movements into a table
- Calculates statistics like object size, filament used and print time
- Uses machine learning to predict filament for future layers
- Shows the 3D toolpath in a plot with each layer in different color
- Has a GUI window that shows everything together

## Files in this repo
- gcode_visualizer.ipynb — the main code
- desk.gcode — the gcode file I used for testing
- plot_3d.png — the 3D toolpath plot
- plot_ml.png — the machine learning result plot

## How to run
Open the notebook in Jupyter and run each block one by one.
Make sure desk.gcode is in the same folder as the notebook.
For the GUI window run the last block as a separate .py file.

## Libraries used
pandas, numpy, matplotlib, sklearn, tkinter, re

## Note on AI use
I used AI assistance for the regex part of the parser 
since regex was not covered in the course.
