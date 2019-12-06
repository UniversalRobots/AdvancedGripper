# AdvancedGripper
Demonstrates how to create a gripper driver contribution for a more advanced gripper

Advanced Gripper demonstrates how to create a gripper driver contribution for a more advanced gripper that supports some of the optional gripper capabilities and controls the Output Voltage setting of the Tool I/O Interface resource. The URCap shows how to: 

* Configure gripper capabilities for, e.g. width, speed, force and vacuum
* Request exclusive control of the Tool I/O Interface resource
* Configure the Output Voltage I/O setting of the Tool I/O Interface

Note:
* Feedback capabilities of the gripper is only available from URCap API version 1.9.0 (released with PolyScope version 3.12.0/5.6.0)

Information:
* Available from:
  * URCap API version 1.8.0.
  * PolyScope version 3.11.0/5.5.0.

Main API interfaces: GripperContribution, GripperCapabilities, SystemConfiguration, GripActionParameters, ReleaseActionParameters.
