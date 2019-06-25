# Calibration

While general values for the number of steps per millimeter will give you decent accuracy, it is necessary to calibrate and change the steps per millimeter for the best accuracy. There are many online guides for calibrating the steps/mm for 3D printers, such as this one found here at [All3DP](https://all3dp.com/2/extruder-calibration-6-easy-steps-2/). The general procedure is found below.
# Supplies Needed

- Calipers

# Steps

1. Turn on the printer
1. Mark the location of the nut shuttle
1. Go to Prepare > Move Axis > Extruder > Move 10mm
1. Move the nut shuttle 100mm
1. Use the calipers to measure how far the nut shuttle actually moved and record
1. Repeat 2-3 more times
1. Take the average of all your measurements
1. Use the equation below to calculate the new steps/mm value

  [Original Steps/mm] x [Distance that was supposed to be traveled] / [Actual distance] = [New steps/mm value]

The new steps/mm value can then be changed by going to Control > Movement > Steps/mm, and then twisting the control knob until the desired value is set. It can also be changed by changing the appropriate value in the firmware.  

NOTE: If the new steps/mm value is not saved by going Control > Store Settings the new steps/mm value will have to be entered every time that the pump is turned on.

It may be necessary to perform this calibration multiple times to ensure that the calibration is correct.
