# How to design a PCB in Autodesk Fusion 360
<ol>
<li>
Under **File** choose **New Electronics Design**:<br>
<img src="/resources/01_00.png" style="width:400px"/>
</li><li>
Fusion will switch to the **Electronics Design** workspace where you’ll need to create a new schematic (**Common** tab):<br>
<img src="/resources/02_00.png" style="width:400px"/>
</li><li>
Fusion will switch to the **Schematic** workspace.
Placement snaps to the grid by default, press and hold **Alt** for finer control.
You may adjust the **Grid Settings** to your desire (**Design** tab, hotkey **G**):<br>
<img src="/resources/03_00.png" style="width:400px"/>
<img src="/resources/03_01.png" style="width:400px"/>
</li><li>
Activate the **Place Components** panel inside the information panels if it’s not already activated:<br>
<img src="/resources/04_00.png" style="width:400px"/>
</li><li>
Before placing any components, make sure you have the required component libraries enabled.
<ol>
<li>
Open the **Library Manager**:<br>
<img src="/resources/05.1_00.png" style="width:400px"/>
</li><li>
There are hundreds of component libraries to choose from. 
To get a preview of the included components and packages, you can either view them on **Library.io** or download them to see a preview directly from the **Library Manager**. 
However, in this example we will be importing a local library (file extension **.lbr**):<br>
<img src="/resources/05.2_00.png" style="width:400px"/>
</li><li>
You may filter the active component libraries to hide components you won’t need:<br>
<img src="/resources/05.3_00.png" style="width:400px"/>
</li><li>
Some components have multiple variants/packages (indicated by a downwards facing arrowhead in the **Variant** column).
Clicking the Variant field opens a drop-down list which also shows both a preview of the footprint and the 3D model.
Before placing a component, make sure to select the correct variant to prevent hassle later:<br>
<img src="/resources/05.4_00.png" style="width:400px"/>
</li>
</ol>
</li><li>
To place a component, double-click it within the **Place Component** panel to enter the component placement mode.
<ol>
<li>
Left click inside the canvas to position a component where desired:<br>
<img src="/resources/06.1_00.gif" style="width:400px"/>
</li><li>
You can rotate components by right-clicking (or using the corresponding buttons from the **Add** dialog):<br>
<img src="/resources/06.2_00.gif" style="width:400px"/>
</li><li>
You can mirror components by pressing the middle mouse button (or using the corresponding buttons from the **Add** dialog):<br>
<img src="/resources/06.3_00.gif" style="width:400px"/>
</li><li>
To move already placed objects, left click and hold the cross of the corresponding object.
Coordinates of the mouse cursor are also shown on the toolbar:<br>
<img src="/resources/06.4_00.gif" style="width:400px"/>
</li>
</ol>
</li><li>
To change the value of a component, activate the Value tool (Design tab, hotkey V):<br>
<img src="/resources/07_00.png" style="width:400px"/>
<img src="/resources/07_01.gif" style="width:400px"/>
</li><li>
You can change the package of components by right-clicking it and selecting Package from the context menu:<br>
<img src="/resources/08_00.gif" style="width:400px"/>
</li><li>
You can also replace a component with one from a different component library by right-clicking it and selecting Replace from the context menu:<br>
<img src="/resources/09_00.gif" style="width:400px"/>
</li><li>
To connect components, activate the Net tool (Design tab, hotkey R).
A circle highlights available endpoints, a junction point indicates that the lines are part of the same connection:<br>
<img src="/resources/10_00.png" style="width:400px"/>
<img src="/resources/10_01.gif" style="width:400px"/>
</li><li>
Once you are ready to design your PCB, switch to the PCB document workspace (Design tab):<br>
<img src="/resources/11_00.png" style="width:400px"/>
<img src="/resources/11_01.png" style="width:400px"/>
</li><li>
You will probably want  to resize the PCB, to do so you may choose one of the following approaches:
<ul>
<li>
a)	For quick and easy adjustments, simply drag and drop the outlines of the PCB to alter its shape:<br>
<img src="/resources/12.a_00.gif" style="width:400px"/>
</li><li>
b)	For more precise or complex PCB outlines, edit the sketch of the PCB.
<ul>
<li>
Firstly, Push to 3D PCB (Design tab):<br>
<img src="/resources/12.b.1_00.png" style="width:400px"/>
<img src="/resources/12.b.1_01.png" style="width:400px"/>
</li><li>
Fusion will switch to the 3D PCB workspace where you’ll need to edit the sketch Outline:<br>
<img src="/resources/12.b.2_00.png" style="width:400px"/>
<img src="/resources/12.b.2_01.gif" style="width:400px"/>
</li><li>
Once you are done editing the sketch, push the 3D PCB back to the 2D PCB so they’re in sync again (3D PCB tab):<br>
<img src="/resources/12.b.3_00.gif" style="width:400px"/>
</li>
</ul>
</li>
</ul>
</li><li>
Back in the PCB document workspace, you may choose to create a GND plane.
<ol>
<li>
Select the outlines of the PCB, right click on one of the outlines and under Convert To Polygon choose Copy.
In the Layer dialog, select layer #16 Bottom:<br>
<img src="/resources/13.1_00.gif" style="width:400px"/>
</li><li>
From the Modify section of the Modify tab, select the Name tool (hotkey N) and left click the PCB outline.
Finally, in the Name dialog, input “GND”:<br>
<img src="/resources/13.2_00.gif" style="width:400px"/>
</li>
</ol>
</li><li>
Before placing components, make sure the correct layer is activated (in this case #1 Top).
Controls for placing components is similar to the Schematic workspace:<br>
<img src="/resources/14_00.gif" style="width:400px"/>
</li><li>
Once you placed all your components, you will need to route the traces.
Once again, there are multiple options to choose from.
<ol>
<li>
For complete control, you can route all traces manually:<br>
<img src="/resources/15.1_00.gif" style="width:400px"/>
</li><li>
However, a way more time efficient way is using the Autorouter:<br>
<img src="/resources/15.2_00.gif" style="width:400px"/> 	 
</li>
</ol>

Further resources:
•	Fusion Help | Tour the interface
•	Fusion Help | Workspaces
•	Fusion Help | Electronics overview
