# Simple Distributed System
Repository for work done in CS_425 distributed system at UIUC
* MP1: Build a basic distributed system which machines in the system are able to detect other member machine's join/leave/crash and change their own machine list correspondingly
* MP2: In addition to MP1, a shared file system is implimented where machines in the system all get access to:\
              1. The file system tolerate up to 3 simultaneous machine crashes (without losing any information)\
              2. The file system allow simultaneous reads, while only one write at a time
* MP3: In addtion to previous MPs, added a cloud computing framework similar to MapReduce using a monitor-worker node orientation\
              the monitor node distributes work for each stage and monitor completion and worker nodes execute application on data given by monitor node
