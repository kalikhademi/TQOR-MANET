# TQOR-MANET

We simulate the performance of TQOR [] which is a recently proposed Trust-based QoS-Oriented Routing protocol (TQOR) in cognitive MANETs. 

The simulation has been implemented in the discrete event simulator OMNeT++ (version 4.4.1). We simulate TQOR in INET framework (version 2.3) of OMNeT++, under AODV protocol.

Once you donwloaded INET framework, replace the following folders in the project for both protocols TQR and TQOR separately:

1) replace folders "manetrouting" and "ipv4" in the "networklayer" folder in the "src" folder.
2) replace folders "application" in the "src" folder.

The simulation setup can be set in omnetpp.ini and params.h files in each project.

For experiments, simply run the omnetpp.ini file and choose AODV-UU protocol. All the results are recorded in INET framework log flies, or in "AODV-UU" folder in "examples" folder of the project.
