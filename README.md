# VSD-SoC-Design_Oct
Learning-Program-VSD-SoC-Design
Day 1 Theory
Unit 1: Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK Chapter 1. SKY130_D1_SK1 - How to talk to computers SKY_L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs
![image](https://github.com/user-attachments/assets/ec9fda13-74c4-412e-ac85-f9922e3bb6d3)  ![image](https://github.com/user-attachments/assets/dc26dae2-74a6-4d64-beca-5913d480b990)


Interface files from foundry: to communicate for the final chip

SKY_L3 - From Software Applications to Hardware image image image

SKY130_D1_SK2 - SoC design and OpenLANE

SKY_L1 - Introduction to all components of open-source digital asic design image
PDK interface bw the FAB lab and the designers image image image image image image image image image image

image

image image image

Routing – to connect the cells. Hori/vert metal straps, Min IR drop, to address electromigration. High level metal is thick for reducing the Resistance. Matal layers are defined in PDK , thickness, height etc.

image image

RTL-GS flow

Spec: application spec IC, Cost of chip , constraints, functionality , area, clock
Arch design: Block diag. eg ALU, memory, cost ect. 3.RTL Eng: wite functional or behavioural code in VHDl or Verilog
Logic synthesis: a) translate: High level RTL to logic gate level without changing the functionality, b) Tech mapping: 28nm,14nm, c) optimization: in terms of power, afrea best QOR. 5 Logic verification and testing (DFT): logic validation, if not pass it to step 4
PHSICAL Design: ICC2 synopsys, ANOS cadence. It takes the gate level net list + SCD constraints file as an input . works on transistors level, CMOS etc. Now transistor level GDS format file sent to verification and sign off. 7 Phsical verification and sign off: DRC, LVS; CROSS TALK; POWER; TIMING: ETC:
Fabrication : GDS to fab lab 9: Packaging: testing the IC , bug free and packaging
IC : to matket.
SKY_L3 - Introduction to OpenLANE and Strive chipsets ASIC FLOW in OPEN LANE
image

image

SCL: stand cell lib SRAM block gen by open RAM compiler. image image image

Harden means: to generate the final layout Automation: Puch button -write flow and then execute Interaction: Steo by step.

SKY_L4 - Introduction to OpenLANE detailed ASIC design flow RTL to Gds2 with using functionality of PDK image

OPEN LAN CONSIST OF FOLLOWING: image image

image image image

image

image

Yosys Translates RTL to logic ck tusking the generated components. Ckt also gets optimized using the abc script with synthesized strategies for getting best timing . Design exp utility to design the config. in best way to result in clean layout.

image

If metal wiring long enough, it acts as antenna, aborb charges, then it problem comes under picture. It is a job of router to handle the wiring length etc. if routers fails to predict the problem then following solutions are there:

image image image image
