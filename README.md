# SMA-Home-Automation
Read SMA values (PV, Battery, EM) via Node Red

This code can be used as flow in Node Red.  The code will read data from the Sunny Home Manager (Energy Meter), the PV inverter (Sunny Tripower) and the battery inverter (Sunny Boy Storage).  

To calculate the Power consumption at home, we use the different components (and split the PV Power evenly over the 3 phases).  This inputs could be used for load balancing (e.g. charging EV), or switch on/off certain devices.

This flow has been based on several inputs from different forums.


You will have to adapt the code with correct multicast IP (Sunny Home Manager), device IP-address (inverter and battery) and login and username for inverter and battery as per comments in the flow.
You can change the values you wish to read in the codes.
Importantly, you might have to adapt the code for correct array values in the Inverter Decoding and Storage Decoding function nodes.
