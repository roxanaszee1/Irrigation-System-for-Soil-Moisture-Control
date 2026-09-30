Soil Moisture Irrigation Circuit 

An automatic irrigation setup that keeps soil moisture between 15% and 30%. Designed and simulated using OrCAD.
Author: Szell, Roxana-Daniela
Budget: around 109 RON

---
How It Works

1. Sensor & Divider: Converts changing soil moisture (950k dry down to 55k wet) into a readable voltage.
2. Buffers (LM358): Keeps the voltage signal stable without overloading the circuit. Chosen over the L272 to drop idle power loss from 130mW down to 9.1mW.
3. Schmitt Trigger: Creates a small voltage window (around 30% humidity so the circuit doesn't flicker on and off constantly.
4. Relay & LED: A 2SC454 BJT drives a 13V relay coil to trigger watering, with a blue LED turning on while it waters.

---
Key Parts

Op-Amps: 3x LM358
Sensor: FC-28
Transistor:2SC454 (NPN)
Power Supply:13V DC
Other:Blue LED, 13V/400Ω relay, assorted resistors (0.1\% to 10% tolerance)
