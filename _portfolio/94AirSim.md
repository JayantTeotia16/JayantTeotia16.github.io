---
title: "Search and Monitor, Artpark"
excerpt: "<br/>"
collection: portfolio

---

Due to climate change, forest fires, floods and other natural calamities are happening more frequently. Often, it is not possible for humans to immediately access the area for monitoring and providing relief. A swarm of UAVs would be very useful to survey the affected area, search for missing people or provide relief autonomously. This was the main motivation of the project- 'Searh and Monitor'.

'All the simulations were conducted on AirSim in 'Africa' environment. A rectangular boundary was marked in the environment on which 'n' drones were kept. The objective of the experiment was to search for the 'target drone' parked within the boundary and monitor(follow if the object is dynamic) it. 

The Vornoi algorithm was adopted to divide the areas for the individual UAVs within the swarms to cover and the minimum spanning tree algorithm was used to generate path in the divided area.

All the drones had forward-down facing camera and the simulation was runing Yolov3 for object detection. Yolov3 was trained from scratch for the detection of drones.

A gRPC program was also developed to bidirectionally stream the video and other information(coordinates, velocity) to and from client and server. Using this program, we were able to perform image processing and object detection using models with higher number of parameters on a static server and send back the processed information back to the swarm of UAVs.


