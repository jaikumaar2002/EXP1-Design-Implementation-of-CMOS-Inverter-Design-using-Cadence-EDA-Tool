Aim:

To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.

Tools Required:

• Personal Computer

• Cadence Virtuoso Software

Circuit Diagram :

![387327524-3e30bd50-665e-4f9c-8a6d-93d564266e73](https://github.com/user-attachments/assets/1490259a-749b-4b23-a060-b7ab4a7ddf4b)


Schematic Simulation :

    PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

    1.Right Click and open the terminal window
    
    2.Type the following commands as follows and press enter. • csh • source /cadence/install/cshrc • virtuoso

Procedure for Schematic simulation using Cadence

  1.  Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”
 
  2.  Close the 2nd window
  
  3.  Use 1st window i.e virtuoso window (CIW) for further processing. i. Create a New Library ii. Create Schematic Cell view. iii. Create the Symbol for schematic Cell view. iv. Create the test Cell view. v. Analog simulation by spectre

i) Procedure for Creating New Library.


• File –New – Library

• Name: Give name for ur library Ex: VLSILAB_EXP_1

• Enable Attach to an existing technology library, Click OK

• Attach the library to the technology library gpdk045.Click OK

ii) Create Schematic Cell view.


• Go to 1st window i.e virtuoso (CIW)

• File-New-Cell view

• Setup the new file form

• Library: Select the one you created.

• Cell: Give the experiment name Ex: Inverter ViewSchematic

• Type: Schematic press OK

• Add the required components from the libraries and make the connections.

• Go to instance fixed menu or use shortcut key “I” from keypad to go instances

• Click on browse. This opens the library browser

• Now select the appropriate library for components like

• Gpdk45 ------------------------nmos1v, pmos1v

• Create Input and Output pins

• Make the connections by using fixed narrow wire key

• Click Check and Save button 

![362169200-5afce444-518f-4a9a-a480-332aba34319c](https://github.com/user-attachments/assets/e1369c4f-f53d-4700-956b-b9047190e291)

iii) Creating the Symbol for schematic Cell view

• In the schematic window, execute

• Create – Cell view – From Cell view

• The cell view from cell view window appears

• Check Lib Name, Cell Name, From View name must be schematic Press ok

• Now Symbol generation form appears. Click Ok If No changes required

• A new window with with default symbol is created.

• Edit the symbol if you want to give actual symbol shape else continue.

• Execute Create-Cell view-from cell view

• Library Name and Cell Name must be same which you have used for schematic. Press OK

• Check for the position of pin side.Prss OK

• Edit for the shape by Create-Shape-Choose required options to edit.

![358526104-e947dcda-b023-4668-a955-a5faf0949702](https://github.com/user-attachments/assets/4e949d32-79aa-48f4-87d9-eea32cc777f5)

iv) Creating the new test cell view

• Go to CIW window, Execute File-New-Cell view

• Setup the new file form

• Library: Select the one you created.

• Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test

• View: Schematic

• Type: Schematic press OK

• Follow the step 3(ii) d to make the required connections 

![362169330-96411f83-8434-48ef-a717-29dba554a7ae](https://github.com/user-attachments/assets/8ff6c26e-6ddc-4f12-b18c-d3992f545d19)

Analog simulation by SPECTRE.

• In test cell view window

• Launch – ADE L(Analog Design Environment)

• Execute Setup—Simulation/directory/Host A new window opens

• Set the simulation window to spectre and click ok

• Execute Analysis – Choose. A window opens.

• Select the type and set the specifications and press OK

• Execute Output s—to be plotted – Select on Schematic

• Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse

• Execute Simulation -- Net list and Run

![358526539-3aac50ec-bc0f-406e-be2e-a504b8afa8c9](https://github.com/user-attachments/assets/17c2da7c-6826-4bc1-9b8d-8ab94062b52b)


For Transient Analysis Settings and Output

![358526650-92d14f32-8ba5-4fed-978a-38c360b8e305](https://github.com/user-attachments/assets/6a71716f-6e84-4c8a-a8c7-febdb969e1c6)

![362169484-9cb795ab-6f1c-44a9-bb57-ef6152a05124](https://github.com/user-attachments/assets/aecf15f7-c66c-4591-8205-1eb0e2c9b5d0)


For DC Analysis Settings and Output

![358526794-0ee74107-e03a-4204-b685-83ced611c993](https://github.com/user-attachments/assets/2b28153b-6929-419f-bbb0-c480af2cae12)


![362169611-9cd1e72b-a23f-4d70-aabe-0bc8ef64599a](https://github.com/user-attachments/assets/3bd062db-ab8d-49d6-bc8c-db7299ec68f9)

Results:

   1. Successfully designed the CMOS inverter schematic using Cadence EDA tools.
 
   2. The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
   
   3. The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.
