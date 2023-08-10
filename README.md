# Vsdworkshop
Starting with the Picorv32a Design example

Physical Design or PnR (Place and Route) is the core of any IC design cycle. From an RTL netlist to a final tape-out, each phase of PnR brings its own challenges and surprises. “What are these challenges?” “What is the process?” “Can I build a chip of my own?”- If you have these questions and if you are eager to delve into the world of ASIC design flow. Wait no more!

With the announcement of Google-SkyWater’s first manufacturable open-source 130nm process design kit (pdk), open source EDA world is no longer limited in scope to academic research and small-scale projects only. This along with the conception of Openlane flow, a fully-automated RTL2GDSII flow, has made the dream of “an IC for all” a near reality.
So here’s announcing the ultimate workshop on SoC design planning in Openlane flow using the latest Google-SkyWater 130nm process node.
So if you want to –

Design and characterize your own standard cell.
Have hands-on in the Physical Design domain.
Generate a full GDSII from an RTL netlist.
Explore and contribute to the open-source EDA world.

This is the opportunity for you!!

[Advanced Physical Design using OpenLANE/Sky130] 
Reference:(https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/?awt_a=5L_6&awt_l=N.ihx&awt_m=3kvzIx6lNaoFA_6)

# Workshop Day-wise Content :

  # Day1 – Inception of open-source EDA, OpenLANE, and Sky130 PDK

1. How to talk to computers
   a. SKY_L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs
     ![image](https://github.com/Shivaprasads99/Vsdworkshop/assets/141851024/42cfa39d-7a45-49bc-bd5c-3baa9a5c691b)
   b. SKY_L2 - Introduction to RISC-V
     ![image](https://github.com/Shivaprasads99/Vsdworkshop/assets/141851024/be0db45f-5995-423a-9b17-f469a3aa4fc7)
   c. SKY_L3 - From Software Applications to Hardware
     ![image](https://github.com/Shivaprasads99/Vsdworkshop/assets/141851024/d8af322b-bb68-466e-8226-bb1db986419c)
     ![image](https://github.com/Shivaprasads99/Vsdworkshop/assets/141851024/ddd69c70-0da8-4c58-883d-5486ba3bb942)
     ![image](https://github.com/Shivaprasads99/Vsdworkshop/assets/141851024/6cfde4dd-29d7-471a-befd-e42a6cd3f696)

2. SoC design and OpenLANE
    a. SKY_L1 - Introduction to all components of open-source digital ASIC design

3. Starting RISC-V SoC Reference design
4.. Get familiar to open-source EDA tools


  # Day 2 - Understand the importance of good floorplan vs bad floorplan and introduction to library cells

1. Chip Floor planning considerations
2. Library Binding and Placement
3. Cell design and characterization flows
4. General timing characterization parameters

   # Day 3 - Design and characterize one library cell using the Magic Layout tool and ngspice

1. Labs for CMOS inverter ngspice simulations
2. The inception of the Layout – CMOS fabrication process
3. Sky130 Tech File Labs

   # Day 4 - Pre-layout timing analysis and importance of good clock tree

1. Timing modeling using delay tables
2. Timing analysis with ideal clocks using openSTA
3. Clock tree synthesis TritonCTS and signal integrity
4. Timing analysis with real clocks using openSTA

   # Day 5 - Final steps for RTL2GDS

1. Routing and design rule check (DRC)
2. PNR interactive flow tutorial
