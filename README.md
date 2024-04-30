# How to design a PCB in Autodesk Fusion 360
1.	Under File choose New Electronics Design:<br>
![](/resources/01_00.png)

2.	Fusion will switch to the **Electronics Design** workspace where you’ll need to create a new schematic (**Common** tab):<br>
![](/resources/02_00.png)

3.	Fusion will switch to the **Schematic** workspace.
Placement snaps to the grid by default, press and hold **Alt** for finer control.
You may adjust the **Grid Settings** to your desire (**Design** tab, hotkey **G**):<br>
![](/resources/03_00.png)
![](/resources/03_01.png)

4.	Activate the **Place Components** panel inside the information panels if it’s not already activated:<br>
![](/resources/04_00.png)

5.	Before placing any components, make sure you have the required component libraries enabled.
5.1.	Open the **Library Manager**:<br>
![](/resources/05.1_00.png)

5.2.	There are hundreds of component libraries to choose from. 
To get a preview of the included components and packages, you can either view them on **Library.io** or download them to see a preview directly from the **Library Manager**. 
However, in this example we will be importing a local library (file extension **.lbr**):<br>
![](/resources/05.2_00.png)

5.3.	You may filter the active component libraries to hide components you won’t need:<br>
![](/resources/05.3_00.png)

5.4.	Some components have multiple variants/packages (indicated by a downwards facing arrowhead in the **Variant** column).
Clicking the Variant field opens a drop-down list which also shows both a preview of the footprint and the 3D model.
Before placing a component, make sure to select the correct variant to prevent hassle later:<br>
![](/resources/05.4_00.png)

6.	To place a component, double-click it within the **Place Component** panel to enter the component placement mode.
6.1.	Left click inside the canvas to position a component where desired:<br>
![](/resources/06.1_00.gif)

6.2.	You can rotate components by right-clicking (or using the corresponding buttons from the **Add** dialog):<br>
![](/resources/06.2_00.gif)

6.3.	You can mirror components by pressing the middle mouse button (or using the corresponding buttons from the **Add** dialog):<br>
![](/resources/06.3_00.gif)

6.4.	To move already placed objects, left click and hold the cross of the corresponding object.
Coordinates of the mouse cursor are also shown on the toolbar:<br>
![](/resources/06.4_00.gif)

7.	To change the value of a component, activate the Value tool (Design tab, hotkey V):<br>
![](/resources/07_00.png)
![](/resources/07_01.gif)

8.	You can change the package of components by right-clicking it and selecting Package from the context menu:<br>
![](/resources/08_00.gif)

9.	You can also replace a component with one from a different component library by right-clicking it and selecting Replace from the context menu:<br>
![](/resources/09_00.gif)

10.	To connect components, activate the Net tool (Design tab, hotkey R).
A circle highlights available endpoints, a junction point indicates that the lines are part of the same connection:<br>
![](/resources/10_00.png)
![](/resources/10_01.gif)

11.	Once you are ready to design your PCB, switch to the PCB document workspace (Design tab):<br>
![](/resources/11_00.png)
![](/resources/11_01.png)

12.	You will probably want  to resize the PCB, to do so you may choose one of the following approaches:
12.a	For quick and easy adjustments, simply drag and drop the outlines of the PCB to alter its shape:<br>
![](/resources/12.a_00.gif)

12.b	For more precise or complex PCB outlines, edit the sketch of the PCB.
b.1	Firstly, Push to 3D PCB (Design tab):<br>
![](/resources/12.b.1_00.png)
![](/resources/12.b.1_01.png)

b.2 	Fusion will switch to the 3D PCB workspace where you’ll need to edit the sketch Outline:<br>
![](/resources/12.b.2_00.png)
![](/resources/12.b.2_01.gif)

b.3	Once you are done editing the sketch, push the 3D PCB back to the 2D PCB so they’re in sync again (3D PCB tab):<br>
![](/resources/12.b.3_00.gif)

13.	 Back in the PCB document workspace, you may choose to create a GND plane.
13.1 	Select the outlines of the PCB, right click on one of the outlines and under Convert To Polygon choose Copy.
In the Layer dialog, select layer #16 Bottom:<br>
![](/resources/13.1_00.gif)

13.2 	From the Modify section of the Modify tab, select the Name tool (hotkey N) and left click the PCB outline.
Finally, in the Name dialog, input “GND”:<br>
![](/resources/13.2_00.gif)

14.	Before placing components, make sure the correct layer is activated (in this case #1 Top).
Controls for placing components is similar to the Schematic workspace:
![](/resources/14_00.gif)

15.	Once you placed all your components, you will need to route the traces.
Once again, there are multiple options to choose from.
15.1	For complete control, you can route all traces manually:
![](/resources/15.1_00.gif)

15.2. 	However, a way more time efficient way is using the Autorouter:
![](/resources/15.2_00.gif) 	 


Further resources:
•	Fusion Help | Tour the interface
•	Fusion Help | Workspaces
•	Fusion Help | Electronics overview
