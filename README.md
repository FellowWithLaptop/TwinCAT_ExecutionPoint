# TwinCAT_ExecutionPoint
In TwinCAT there are some functions available for debugging. The best known is probably the breakpoint. But this is used with caution, because it stops a running machine immediately. Therefore it is often avoided by programmers by using counters or flags to check the sequence of a control.  In addition to the breakpoint, there is also the execution point, which does **not stop** the machine.  I suspect that many are not aware of this feature and so I would like to share it briefly. 


The breakpoint is normally added with the F9 key or via the context menu.
The breakpoint is red and an arrow appears when the code is stopped.

![alt text](https://github.com/FellowWithLaptop/TwinCAT_ExecutionPoint/blob/0f8f10a880d5b4fa254364d59b9c45067c95bae0/Breakpoint.png?raw=true)

The execution point is added via the Debug tab, New Breakpoint.
![alt text](https://github.com/FellowWithLaptop/TwinCAT_ExecutionPoint/blob/0f8f10a880d5b4fa254364d59b9c45067c95bae0/New_Breakpoint.png?raw=true)

In the dialog that opens, select the "Execution point settings" tab and click on the "Execution Point".
With the "Activate breakpoint immediately" option, the execution point is activated automatically. 
![alt text](https://github.com/FellowWithLaptop/TwinCAT_ExecutionPoint/blob/0f8f10a880d5b4fa254364d59b9c45067c95bae0/New_ExecutionPoint.png?raw=true)

Unlike the breakpoint, the execution point is green and the code is not stopped.
![alt text](https://github.com/FellowWithLaptop/TwinCAT_ExecutionPoint/blob/0f8f10a880d5b4fa254364d59b9c45067c95bae0/ExecutionPoint.png?raw=true)

Whether and how often the execution point has already been called, you can see in the Breakpoints window.
You can find the window under the tab PLC->Windows->Breakpoints. 
![alt text](https://github.com/FellowWithLaptop/TwinCAT_ExecutionPoint/blob/0f8f10a880d5b4fa254364d59b9c45067c95bae0/OpenBreakpoints.png?raw=true)

![alt text](https://github.com/FellowWithLaptop/TwinCAT_ExecutionPoint/blob/0f8f10a880d5b4fa254364d59b9c45067c95bae0/Breakpoints.png?raw=true)

In the Breakpoint Properties window you can find some other useful functions, which I will not go into here.
If you are looking for the documentation of this function from Beckhoff you will find it [here.](https://infosys.beckhoff.com/content/1033/tc3_plc_intro/2527568011.html?id=5008915087046204059 "Beckhoff")
