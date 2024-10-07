
Learning-Program-VSD-SoC-Design
# Day 1 Theory
Unit 1: Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
Chapter 1.  SKY130_D1_SK1 - How to talk to computers
SKY_L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs
      
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/c2996e99-3214-42c4-af27-d037078aec07)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/4bc36b65-c459-4db1-a0ae-d715c24259fe)

Interface files from foundry: to communicate for the final chip 

SKY_L3 - From Software Applications to Hardware
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/e5d7b097-5f73-45c1-bb1e-6e9d44b04a5e)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/54eeef03-b9ba-4d68-9d4e-6449902f90f3)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/14fe1a01-5d6d-4440-8d26-9e64843907c3)

SKY130_D1_SK2 - SoC design and OpenLANE
1.	SKY_L1 - Introduction to all components of open-source digital asic design
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/c7288d42-d30d-4465-ab14-c663e31521e9)

PDK interface bw the FAB lab and the designers
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/8dd8dea2-d918-4a2e-941e-1b6db67e13b7)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/7d06c100-deb8-4350-b822-baeb2deddf27)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/faddc31d-e77e-4206-b271-1b877cb31dce)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/1036c77e-5216-446a-8a72-a863af436003)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/5a4db5a8-8247-4301-b9f7-250a2df3d2ef)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/fb00afa0-8b1b-48d7-8893-ba543a2cd34b)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/524baae5-ef56-4026-abb2-f848a9b1df73)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/056fddb7-6298-46c3-95ed-7a28b8190cea)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/941c027d-c362-4c29-9080-7c3926171bcb)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/c45168dd-8956-4e0f-992a-3d5e0fdfd292)

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/770167cb-07e3-42c2-bcf9-354e53b6ae00)

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/a0e048f3-548c-44ac-81c3-6885f514b8ec)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/d7fb0979-a4df-4ec5-a1e6-cc1f28e99a9a)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/262a2038-aa4b-4505-a6eb-76f0b167c13b)
 
Routing – to connect the cells. Hori/vert metal straps, Min IR drop, to address electromigration. High level metal is thick for reducing the Resistance. Matal layers are defined in PDK , thickness, height etc.
 
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/3564626e-d9a9-4dcc-8651-50609cd19390)
 ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/a4fd413f-401b-4b16-99b8-d08d2ced82c5)

RTL-GS flow
1. Spec: application spec IC, Cost of chip  , constraints, functionality , area, clock
2. Arch design: Block diag. eg ALU, memory, cost ect.
3.RTL Eng: wite functional or behavioural code in VHDl or Verilog
4. Logic synthesis: a) translate: High level RTL to logic gate level without changing the functionality, b) Tech mapping: 28nm,14nm, c) optimization: in terms of power, afrea best QOR.
5 Logic verification and testing (DFT): logic validation, if not pass it to step 4 
6. PHSICAL Design: ICC2 synopsys, ANOS cadence. It takes the gate level net list + SCD constraints file as an input . works on transistors level, CMOS etc. Now transistor level GDS format file sent to verification and sign off.
7 Phsical verification and sign off: DRC, LVS; CROSS TALK; POWER; TIMING: ETC:
8. Fabrication : GDS to fab lab
9: Packaging: testing the IC , bug free and packaging
10. IC : to matket.

SKY_L3 - Introduction to OpenLANE and Strive chipsets
ASIC FLOW in OPEN LANE       
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/45772034-86e6-4a43-be8e-5e3e1d69fd0e)

 ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/80659bfb-1c93-450f-9b86-eb604f58890d)


SCL: stand cell lib
SRAM block gen by open RAM compiler.
  ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/8b603ab5-9833-4634-a2a8-15ef12e48f1a)     ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/6b4bd9e1-2777-4f17-9d9e-f235a132afbe)    ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/da9d911a-d8d3-418f-8e5c-87477d8002eb)


 
Harden means: to generate the final layout
Automation: Puch button -write flow and then execute
Interaction: Steo by step.

SKY_L4 - Introduction to OpenLANE detailed ASIC design flow
RTL to Gds2 with using functionality of PDK
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/95235228-21c1-4ca0-9736-339a848c19a7)   


OPEN LAN CONSIST OF FOLLOWING:
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/e1f1e340-55cf-473e-8369-56ed290a4ecc)    ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/86a21074-550b-4b52-9587-46a8c6b98145)

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/458f99a5-22b3-432a-8455-d97962ce597c)    ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/4193e493-f4e2-48e5-8639-1b93e713d88f)     ![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/a2374baa-9cb1-456d-a510-834f2387c43f)

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/b5f79904-25ed-4c1c-8702-4f4d233e3e5f)

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/1bccd0e9-7da4-422c-9049-1de8376e7309)

Yosys Translates RTL to logic ck tusking the generated components.
Ckt also gets optimized using the abc script with synthesized strategies for getting best timing .
Design exp utility to design the config.  in best way to result in clean layout.

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/acf30467-a991-497a-80dc-9b462a2b808e)

If metal wiring long enough, it acts as antenna, aborb charges, then it problem comes under picture. It is a job of router to handle the wiring length etc. if routers fails to predict the problem then following solutions are there:

![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/53bcd02b-ac54-4dd8-bf28-d35b456db833)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/728d2f4d-faa7-4f42-9526-93e1c98da22a)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/50ce07c4-c131-4a15-8a73-5f0b0d561b00)
![image](https://github.com/Deepakkumar18207/VSD-SoC-Design/assets/170551774/231de33c-63a7-4a6c-abf9-284ddf2df3d0)

