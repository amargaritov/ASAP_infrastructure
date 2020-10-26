# ASAP_infrastructure
This repository contains simulator infrastructure for Prefetched address translation (ASAP) paper. 

Currently, it consists of two components: 

1. Trace generator
2. Simulator for native case 

There is no simulator for virtualized scenario yet (work in progress). The simulator outputs a file containing a histogram of page walk trajectories where a trajectory shows from where in the memory hierarchy each page node was fetched. 
