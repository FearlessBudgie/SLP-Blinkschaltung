# How to design a PCB in Autodesk Fusion 360
<img src="/resources/00_00.gif" style="width: 600px;" />
<ol>
    <h2>Schematic</h2>
    <h3>Preperation</h3>
    <li>
        Under <b>File</b> choose <b>New Electronics Design</b>:<br />
        <img src="/resources/01_00.png" style="width: 350px;" />
    </li><br />
    <li>
        Fusion will switch to the <b>Electronics Design</b> workspace where you’ll need to create a new schematic (<b>Common</b> tab):<br />
        <img src="/resources/02_00.png" style="width: 350px;" />
    </li><br />
    <li>
        Fusion will switch to the <b>Schematic</b> workspace. Placement snaps to the grid by default, press and hold <b>Alt</b> for finer control.<br />
        You may adjust the <b>Grid Settings</b> to your desire (<b>Design</b> tab, hotkey <b>G</b>):<br />
        <img src="/resources/03_00.png" style="height: 300px;" />
        <img src="/resources/03_01.png" style="height: 300px;" />
    </li><br />
    <li>
        Activate the <b>Place Components</b> panel inside the information panel if it’s not already activated:<br />
        <img src="/resources/04_00.png" style="width: 450px;" />
    </li><br />
    <h4>Libraries</h4>
    <li>
        Before placing any components, make sure you have the required component libraries enabled.
        <ol>
            <li>
                Open the <b>Library Manager</b>:<br />
                <img src="/resources/05.1_00.png" style="width: 450px;" />
            </li>
            <li>
                There are hundreds of component libraries to choose from. To get a preview of the included components and packages, you can either view them on <b>Library.io</b> or download them to see a preview directly from the <b>Library
                Manager</b>.<br />
                However, in this example we will be importing a local library (file extension <b>.lbr</b>):<br />
                <img src="/resources/05.2_00.png" style="width: 600px;" />
            </li>
            <li>
                You may filter the active component libraries to hide components you won’t need:<br />
                <img src="/resources/05.3_00.png" style="width: 450px;" />
            </li>
            <li>
                Some components have multiple variants/packages (indicated by a downwards facing arrowhead in the <b>Variant</b> column).<br />
                Clicking the Variant field opens a drop-down list which also shows both a preview of the footprint and the 3D model.<br />
                Before placing a component, make sure to select the correct variant to prevent hassle later:<br />
                <img src="/resources/05.4_00.png" style="width: 450px;" />
            </li>
        </ol>
    </li><br />
    <h3>Placing and Modifying Components</h3>
    <h4>Placing</h4>
    <li>
        To place a component, double-click it within the <b>Place Component</b> panel to enter the component placement mode.
        <ol>
            <li>
                Left-click inside the canvas to position a component where desired:<br />
                <img src="/resources/06.1_00.gif" style="width: 600px;" />
            </li>
            <li>
                You can rotate components by right-clicking and mirror them using the middle mouse button (alternatively, use the corresponding buttons of the <b>Add</b> dialog):<br />
                <img src="/resources/06.2_00.gif" style="width: 400px;" />
                <img src="/resources/06.2_01.gif" style="width: 400px;" />
            </li>
            <li>
                To move already placed objects, left-click and hold the cross of the corresponding object.<br />
                Coordinates of the mouse cursor are also shown on the toolbar:<br />
                <img src="/resources/06.3_00.gif" style="width: 600px;" />
            </li>
        </ol>
    </li><br />
    <h4>Modifying</h4>
    <li>
        To change the value of a placed component, activate the <b>Value</b> tool (<b>Design</b> tab, hotkey <b>V</b>):<br />
        <img src="/resources/07_00.png" style="height: 250px;" />
        <img src="/resources/07_01.gif" style="height: 250px;" />
    </li><br />
    <li>
        You can change the package of placed components by right-clicking it and selecting <b>Package</b> from the context menu:<br />
        <img src="/resources/08_00.gif" style="height: 600px;" />
    </li><br />
    <li>
        You can also replace a placed component with one from a different component library by right-clicking it and selecting <b>Replace</b> from the context menu:<br />
        <img src="/resources/09_00.gif" style="height: 600px;" />
    </li><br />
    <h3>Draw Net</h3>
    <li>
        To connect components, activate the <b>Net</b> tool (<b>Design</b> tab, hotkey <b>R</b>):<br />
        <img src="/resources/10_00.png" style="width: 600px;" /><br />
        A circle highlights available endpoints, a junction point indicates that the lines are part of the same connection:<br />
        <img src="/resources/10_01.gif" style="width: 600px;" />
    </li><br />
    <h2>PCB</h2>
    <li>
        Once you are ready to design your PCB, switch to the <b>PCB document</b> workspace (<b>Design</b> tab):<br />
        <img src="/resources/11_00.png" style="width: 400px;" />
        <img src="/resources/11_01.png" style="width: 600px;" />
    </li><br />
    <h3>Preparation</h3>
    <h4>PCB Outline</h4>
    <li>
        In most cases you will probably want to alter or define the dimensions of your PCB before placing components.<br />
        There are multiple ways to do so:<br /><br />
&nbsp&nbsp&nbsp&nbsp
          a) For quick and easy adjustments, simply drag and drop the outlines of the PCB to alter its shape:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            <img src="/resources/12.a_00.gif" style="width: 600px;" /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
            You may also alter the board outline further with the <b>Board Shape</b> tools.<br /><br />
&nbsp&nbsp&nbsp&nbsp
          b) However, in most cases you will probably want to define the dimensions of your PCB more precisely:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              1. Firstly, <b>Push to 3D PCB</b> (<b>Design</b> tab):<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                <img src="/resources/12.b.1_00.png" style="height: 300px;" />
                <img src="/resources/12.b.1_01.png" style="height: 300px;" /><br /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              2. Fusion will switch to the <b>3D PCB</b> workspace where you’ll need to edit the sketch <b>Outline</b>:<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                <img src="/resources/12.b.2_00.png" style="height: 400px;" />
                <img src="/resources/12.b.2_01.gif" style="height: 400px;" /><br /><br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
              3. Once you are done editing the sketch, <b>Push to 2D PCB</b> to sync both workspaces again (<b>3D PCB</b> tab):<br />
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
                <img src="/resources/12.b.3_00.png" style="width: 350px;" />
    </li><br />
    <h4>GND Plane</h3>
    <li>
        Back in the PCB document workspace, you can choose to create a GND plane.
        <ol>
            <li>
                Select the outlines of the PCB, right-click on one of the outlines and under <b>Convert To Polygon</b> choose <b>Copy.</b> In the <b>Layer</b> dialog, select layer <b>#16 Bottom</b>:<br />
                <img src="/resources/13.1_00.gif" style="width: 1000px;" />
            </li>
            <li>
                From the <b>Modify</b> section of the <b>Modify</b> tab, select the <b>Name</b> tool (hotkey <b>N</b>) and left-click the PCB outline. Finally, in the <b>Name</b> dialog, input “GND”:<br />
                <img src="/resources/13.2_00.gif" style="width: 1000px;" />
            </li>
        </ol>
    </li><br />
    <h4>Layers</h4>
    <li>
        Before placing any components, make sure the correct layer is activated (in this case <b>#1 Top</b>):<br />
        <img src="/resources/14_00.png" style="width: 600px;" /><br />
        <ol>
            <li>
                For more complex PCBs you might want to make use of the <b>Layer Stack Manager</b> (<b>Design</b> tab):<br />
                <img src="/resources/14.1_00.png" style="width: 400px;" />
                <img src="/resources/14.1_01.png" style="width: 600px;" />
            </li>
        </ol>
    </li><br />
    <h3>Placing and Modifying Components</h3>
    <li>
        Controls for placing and modifying components is similar to the <b>Schematic</b> workspace:<br />
        <img src="/resources/14.2_00.gif" style="width: 1000px;" />
    </li>
    <h3>Routing</h3>
    <li>
        Once you placed all your components, you will need to route the connections Once again, there are multiple options to choose from.
        <ol>
            <li>
                For complete control, you can route all conncetions manually (<b>Design</b> tab, hotkey <b>R</b>):<br />
                <img src="/resources/15.1_00.png" style="width: 400px;" />
                <img src="/resources/15.1_01.gif" style="width: 1000px;" />
            </li>
            <li>
                However, a way more time efficient way is using the Autorouter (<b>Design</b> tab):<br />
                <img src="/resources/15.2_00.png" style="width: 400px;" />
                <img src="/resources/15.2_01.gif" style="width: 1000px;" />
            </li>
        </ol>
    </li>
    <h2>3D PCB</h2>
    <li>
        To have a look at your finished PCB in 3D, <b>Push to 3D</b> again.<br />
        You may notice that components without 3D models are shown as rectangles:<br />
        <img src="/resources/16_00.png" style="width: 1000px;" /><br />
        Hide <b>Packages</b> to hide all components and get a view of the bare PCB:<br />
        <img src="/resources/16_01.png" style="width: 1000px;" /><br />
    </li>
    <h2>Export</h2>
    <li>
        Lastly, if you wish to export your PCB (e.g. to order it from a PCB Fabrication Manufacturer), switch back to the <b>PCB document</b> workspace, activate the <b>Manufacturing</b> tab and <b>Export Gerber, NC Drill, Assembly and Drawing Outputs</b>:<br />
        <img src="/resources/17_00.png" style="height: 350px;" />
        <img src="/resources/17_01.png" style="height: 350px;" /><br />
        <img src="/resources/17_02.png" style="width: 800px;" />
    </li>
</ol>
