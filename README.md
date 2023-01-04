# Labview-Foot-Detect
This program will controll a Prism tread through the com cable on the LPCA. It mimics the smart card by sending a subset of the same commands the smart card would, at a higher frequency for better resolution of the lower state.

The Don P src files folder contains the labview program Don Pacaba wrote for the Precor Treadmills. We used this as the starting point and recreated it using the Peloton communication protocol so it would work with a Prism Tread.

To launch the program navigate to the Prism Controller folder and open the Prism_Controller labview project file. Read the Test Operation Instructions file in this folder for instructions on how to run the program. The cable required to control the LPCA is shown in the Equipement pictures folder

This program was often used in junction with logging from the serial port on the LPCA using the DCI serial terminal for additional data. The cable required for the serial terminal logging is shown in the Equipement pictures folder
