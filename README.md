# TCP Congestion Control
Congestion control in the computer network means preventing excessive accumulation of transmission data in the waiting queue and as a result packets are lost. Congestion occurs when the amount of data entering the data bus exceeds the capacity of that bus. One of the most important features of TCP is congestion control, which implements it with the help of several stages of slow start, congestion avoidance, fast restransmit and fast recovery.  Different algorithms have been created to implement these steps and control congestion, here I implemented TCP Reno, YeAH and Cubic.

## Network Topology
In [this](https://github.com/davoudifatemeh/TCP-Congestion-Control/blob/main/Topology.jpg) topology, the bandwidth of each link has been displayed along with the delay of each link:

## Simulation of congestion control methods in NS2
