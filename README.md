# EVConversion
EV Conversion Schematic for the conversion of my 1983 FIAT BERTONE X1/9 as an QElectroTech.org project.

#This schematic is work-in-progress.

Actual focus is on a general overview on page one and the two battery boxes for five Tesla Model S modules in total on page two an three. 
I'm using the original Tesla cables to wire the BMS boards inside the boxes and use a SimpBMS system as a controller. The SimpBMS will be located in the dashboard, right behind its display.
Each box is equipped with two main contactors. One for positive and one for negative output. You might find this oversized, but because both boxes are located in different parts of the car, one in front and one in back, I thought it increases safety. 
Because of the separate locations, each box will be equipped with a MSD Maintenance Service Disconnect device and a plugable HV connector. Both devices have HVIL High Voltage Interlock contacts that are connected in series to form a line. This HV-Interlock signal provides the power supply for all four HV contactors. If the line fails, all contactors in each box will shut off immediately. 
This HV-Interlock signal can be added with an emergency stop switch, a rollover switch or similar safety devices that you prefer. I will add at least a rollover switch. 
