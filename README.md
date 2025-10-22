# Real-Life-Street-Light-Control-System-

I have built a Real Life Street Light Control System🚦.

How it works:


1. A solar panel (6 volts) ☀️ charges the battery (4V Lead acid) during the day and stores energy.

2. At night, an LDR (photoresistor) detects darkness and triggers the NMOSFET(which acts like a switch), switches ON the LED 💡 of the streetlight.

3. In case the solar panel cannot charge (due to absence of sunlight 🌥️), an external power supply of 9 Volts (line supply) is used as backup. A relay🔄(It isolates the CKT) ensures smooth switching between 4 Volts Lead acid battery and external sources.

4. But without an LM393 IC, the Relay can’t trip . This IC compares 2 different voltage level and give the O/P from the higher ones.

5. Its important to set the Threshold Voltage level, which can be adjusted using a Potentiometer.(Here I set it to 1.5 Volt)


here is the Simulation👇
https://lnkd.in/egB_uMZa.
