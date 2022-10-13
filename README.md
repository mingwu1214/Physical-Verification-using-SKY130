# PHYSICAL VERIFICATION USING SKYWATER 130NM TECHNOLOGY
 5-day workshop for physical verification using sky130
 
 - If you want to do following lab in your local machine, you can prompt the following script. 
Clone the repository git clone https://github.com/RTimothyEdwards/open_pdks\
Run cd open_pdks\
Run ./configure --enable-sky130-pdk\
Run make\
Run sudo make install

# Day 1 - Introduction to SkyWater SKY130

## Tool installations and basic DRC/LVS design flow
- Check Tool Installations

Following is the procedure to ensure the environment is ready or not.
You can just follow the detailed snapshot to checkit 
![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_40_09-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_41_26-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_41_51-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_42_13-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_43_34-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_44_03-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_44_14-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_45_10-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_45_31-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_45_53-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_46_17-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_46_44-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_47_32-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_48_02-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_48_13-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2011_59_25-.png)


![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_00_38-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_00_50-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_01_19-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_03_16-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_03_28-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_03_59-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_07_02-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_18_23-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_20_18-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_20_31-Window.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L1%20-%20Check%20Tool%20Installations/raw/2022-10-10%2012_21_37-Window.png)


- Creating Sky130 Device Layout In Magic
![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10-22-01.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-02.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-02.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-03.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-04.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-05.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-06.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-07.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-08.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-09.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-10.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-11.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-12.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-13.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-14.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-15.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-16.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-17.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2022-18.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2023-19.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2023-20.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2023-22.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L2-Creating_Sky130_Device_Layout_In_Magic/raw/2022-10-10%2023-23.png)

- Creating Simple Schematic In Xschem
  
  Create the first inverter schematic in Xschem
![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L3-Creating_Simple_Schematic_In_Xschem/raw/2022-10-13-00-000017.png)

- Creating Symbol And Exporting Schematic In Xschem

prompt xschem
Open the inverter.sch and press "symbol" -> "make symbol from schematic" to generate inverter.sym

XSCHEM EDITOR COMMAND CHEATSHEET\
This list is available in XSCHEM in the Help menu\
\
Shift-i to insert instance\
Hover+m to move the object\
Hover+w for add wire to connect the nodes\
Right mouse button to the properties form

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/0.png)

draw inverter_tb.sch
After drawing the inverter_tb.sch, press netlist to generate inverter_tb.spice

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/1.png)

After generating the netlist, press simulate to simulate the inverter_tb.spice

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/2.png)

Messages during the simulation

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/3.png)

Simulation result

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/4.png)
![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/5.png)

Open inverter.sch and Generate inverter.spice with option "Top level is a .subckt"

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L4-Creating_Symbol_And_Exporting_Schematic_In_Xschem/6.png)


- Importing Schematic To Layout And Inverter Layout Steps

magic -d XR\
"File" -> "Import SPICE

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/0.png)

Press i to select the cell, M to move the cell.\
Press s to select the port, M to move the port.

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/1.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/2.png)

Press i to select the cell, P to configure the cell.\
Set "Top guard ring via coverage" to 100%\
Set "Source via coverage" to 40%\
Set "Drain via coverage" to -40%

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/3.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/4.png)

Use rectangle and path mode to connect the nodes; you can change the mode by press space key.\
Use center mouse button to pick the layer.

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/5.png)

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/6.png)

After connecting the nodes, you will see drc=0

![image](https://github.com/mingwu1214/Physical-Verification-using-SKY130/blob/main/screenshot/PV_D1SK2_L5-Importing_Schematic_To_Layout_And_Inverter_Layout_Steps/7.png)

- Final DRC/LVS Checks And Post Layout Simulations

# Day 2 -DRC/LVS Theory and labs

## Labs for GDS read/write, extraction, DRC, LVS and XOR setup
- GDS Read

- Ports

- Abstract Views

- Basic Extraction

- Setup For DRC

- Setup For LVS

- Setup For XOR
