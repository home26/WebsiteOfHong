---

---
### Description
It is a platform simulating UAV flight based on AirSim. The structure can be illustrated in the following grapg.
{{< figure src="structure.png" title="System Structure" >}}
In this system, you can control a drone in control panel, such as takeoff, land and move. The drone can move in the simulation platform backed by AirSim according to the operations in control panel. The real-time position data of drone can be sent to MATLAB by UDP protocol and the 3D trajectory of drone can be drawn. 
The simulation and control panel are shown in the following picture.
_________________________________________________________
{{< figure src="uav.jpg" title="UAV Simulation" >}}
_________________________________________________________
{{< figure src="trajectory.jpg" title="UAV Trajectory" >}}
_________________________________________________________
### My Contribution
I was responsible to develop the simulation platform based on AirSim including QT GUI, communication with MATLAB. C++ language was mainly used in this project.
