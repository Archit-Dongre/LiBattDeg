# LiBattDeg
This dataset is generated by P2D model for Li-ion battery, the out put will be the degradation of battery during charging.

# Dataset
This dataset is generated by Porous Electrode Pseudo 2-dimensional Model (P2D).
The assumption of this current model:
1. The battery opperates in 23 degree C
2. Degradation of the only happens during charging
3. initial SoC 0.2
4. initial SoH 1e-8

Dataset
1. SOC = State of charge of the battery (0% = empty; 100% = full)
2. SOH = State of Health of the battery (It is determined by the thickness of the SEI layer)
3. Power = output power (positive sign represets charging; negative sign represents discharging.)

- Possilbe applications:
Ex. Gird application

   Ideally , the grid frequency is the same everywhere on an interconnected grid, for example, 60 Hz in the USA. If power generation and demand mismatch happens to the grid, the grid frequency move away from the nominal value. To avoid this situation, Automatic Regulation Mechanism has been developed. The grid operator holds power capacity by energy producers, which can be activated any time to bring the balance to the grid. The primary reserve that stops the frequency drift in case of a grid failure event and the secondary reserve that brings the frequency back to its nominal value. Batteries are usually used as secondary reserves for  frequency control.
   “Pay for performance” scheme aims to quantify and better compensate the regulation service supplied to the grid by a given asset. Batteries (fast assets) are the good option for its fast response time under 2 second comparing to thermal power plants (slow assets). The ISOs (Independent System Operators) such as PJM or NYISO will publish the dynamic regulation (RegD) signal to ask contracted energy producers to follow. Participants will be paid by their frequency regulation capacity and their accuracy in signal following.
   However, current battery owners didn’t consider the battery degradation which happens a lot under high charging rate. The battery degradation (capacity fade) is due to solid-electrolyte interphase (SEI) growth and it can be the cost of the batteries. So, even if they receive the reward by following the RegD signal posted from ISOs, they might lose money by replacing new batteries. Therefore, establishing a new signal following strategy by considering the cost of the battery degradation is presented in this work.



