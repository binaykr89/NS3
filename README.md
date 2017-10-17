# NS3


For simulation, we need to write a simulation script which is a C++ program. To this program the ns-3 library is linked to build our simulation executable.  API calls are used in the program to do the necessary simulation. The waf build system is used to build the simulation.

Steps in writing script :
● Include necessary files 
● Use appropriate name space 
● Set simulation time resolution(Optional) 
● Enable logging for different modules(Optional) 
● Create nodes 
● Create net devices 
● Attach Net devices to nodes and set interconnections
 ● Install protocol stack in nodes 
● Set network address for interfaces 
● Setup routing 
● Install applications in nodes 
● Setup tracing 
● Set application start and stop time 
● Set simulation start time 
● Run simulation 
● Release resources at end of simulation
