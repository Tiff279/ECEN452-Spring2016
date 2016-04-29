# Lab 8 Report
Joshua Ruff

## Background
The Hybrid coupler and Rat Rase couplers are four port divices in which the power input into one port is divided between two output ports and isolated from the fourth. The Hybrid coupler provides 90 degrees of phase shift in the out of phase port, while the Rat Race coupler provides 180 degrees in the out of phase port. The phase difference on the rat-race allows it to be used to output the sum and difference of input signals. 

## Design
###Hybrid Coupler
All interconnections of the hybrid coupler are quarter-wave. In the diagram, the vertical strips match the feedline impedance (50-Ohms), while the horizontal strips are scaled down to 35-Ohms. A microstrip line calculator was used to determine the physical lengths and widths. The 50 Ohm lines had a width of 3.13 mm and a length of 16.88 mm. The 35 Ohm lines had a width of 5.27 mm and a physical length of 16.47 mm. 


###Rat-Race Coupler
To achieve an equal power split, the interconnections in the Rat-Race coupler are all equally set to root 2 times the feed line impedance, or 71 Ohms. The three smaller interconnections are all quarter wave in length, while the longer interconnection is three-quarters of a wavelength long. Using the microstrip calculator, the feedline is determined ot have a width of 1.71 mm, and a length of 17.7 mm. The feedline had a width of 3.13 mm. 

## Procedure
Provide a step-by-step decription of the activities you performed during the lab.

## Results and Discussion
Include measured/simulated Plots here. All plots are to be made in Python by modifying the csv plotter code. Explain how you can tell the device is working by examining the data (S-parameters). Comment on any differences between the measured and simulated results and sources of error.

To embed graphs or diagrams in your README.md file, commit and push the graphs to your LabX folder (I prefer to save them as .png files) and then get the URL link to the file on github. Then use: <br>
`![Plot_Name](https://link_to_image_on_github)` <br>
See the raw text of the tutorials for an example.

## Conclusion
Summarize the key points in the design and results. Also mention unexpected challenges (if any) in the design and how you overcame them. 

## Hindsight
Comment on anything you know now, having completed the lab, that you wish you knew at the beginning of the lab.

## Reflection
Breifly describe the most challenging parts of the lab and the most rewarding parts of the lab.