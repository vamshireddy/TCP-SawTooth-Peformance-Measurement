TCP-SawTooth-Peformance-Measurement
===================================
* This project creates a parking lot topology like this
![Image of Parking Lot Topo](https://lh4.ggpht.com/E3nKjzOK9-joV1ZK_bixJ88d2xk4JpPA08_ZydL_ULkShBJBj4jkU-BGipY-b54L9xyvO08LTfF5bj33MFA=s500)
* It monitors the TCP flows between all the hosts and the receiver
* It uses utility functions to plot congestion window, and rate of the senders to the lone reciever.
* All the plots and stats are stored in folder with timestamp as the name.
* In this experiment, all the hosts try to perform iperf to the reciever at the same time.
* Hosts N = 1,2,3,4,5 have been tested.
