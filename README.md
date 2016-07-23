# ar-drone-detection

Goal:
A node.js module allowing ar-drones to communicate with an express server over http.

This detection system is to allow drones to transmit location data to a server over a local wifi network, this location data will be flooded back into the network allowing all other drones communicating with this server to see where this drone is located.

Ar-drone nav-data is also plotted on a google map running at localhost to allow users to see a real time view of all the drones connected to this server.
