# FURNACE-CONTROL-SYSTEM
A furnace in a food processing plant is required to keep the temperature of a substrate at 20oC
± 1oC. A furnace controller is designed using an 8051 microcontroller with the following properties;
The furnace ON/OFF is controlled by a solenoid connected to P1.7 of the 8051 microcontroller. If P1.7 = 1, the solenoid is engaged and the furnace will turn on, and if P1.7 = 0, the solenoid is disengaged and the furnace will turn off. Temperature sensors are connected to 𝐼̅𝑁̅̅𝑇̅̅̅0̅ and
𝐼̅𝑁̅̅𝑇̅̅̅1̅ and provide 𝐻̅̅𝑂̅̅𝑇̅̅ and 𝐶̅̅𝑂̅̅𝐿̅̅𝐷̅̅ signals, respectively, such that 𝐻̅̅𝑂̅̅𝑇̅̅ = 0 if the temperature is greater than 21oC and 𝐶̅̅𝑂̅̅𝐿̅̅𝐷̅̅ = 0 if the temperature is less than 19oC as shown in Figure 1 (b).
The controller turns on the furnace for a temperature less than 19oC and turns it off for a temperature greater than 21oC as shown in Figure 1 (b).

Figure 1
Using interrupts, write an assembly language program for the 8051-furnace controller and simulate the circuit in Proteus software
