# SMTS-Smart Traffic Management System

SMTS is Smart Traffic Management System using Cognitive Recognition based on Internet Of Things.
## Proposed System
* The System can be deployed in City to manage and reduce traffic.
* The System considers all the intersections of city as nodes. A dedicated network of Raspberry PI is installed for each traffic intesection. These RaspberryPI are directly interfaced with each traffic control signal at junction.
* Each RaspPI controls the traffic control signal timer of each junction and changes it accordingly to data recieved from main server (which is running a real time traffic optimisation algorithm, which takes real time traffic density at the   junction as inpute).
* The Traffic density is calculated using image processing of real time feed from IPcamera installed at junction.
* A network of such RaspPI are connected to a Main server where the RaspPI forwards the calculated Traffic Density. Using our self defined algorithm, the main server finds optimal traffic signal timer value for each signal and then forward to each RaspberryPI. These RaspberryPI then further forward the data to each signal.





