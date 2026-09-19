# DistributedEdgeNetwork
*this repository is in progress*
---
Evaluating  a distributed edge network for In-flight data processing and transfer

# Overview
Transferring data to and from airplanes presents significant challenges, particularly due to the intermittent availability of internet connections during flight. Satellite connections can be costly and slow, while cellular networks are only accessible when the airplane is on the ground. This project proposes to evaluate the feasibility of using multiple cabin crew devices as a distributed edge network to preprocess data from onboard sources and services, facilitating data transfer when connected to high-speed terrestrial networks, such as Wi-Fi, upon landing. 

# Objectives: 

- Edge Feasibility: Validate cabin crew devices as distributed compute nodes for localized in-flight data processing.

- Onboard Integration: Map interactions between crew devices and aircraft data systems.

- Terrestrial Offloading: Streamline secure, high-throughput data sync to backend infrastructure upon connecting to ground networks.

- Backend Governance: Outline essential administrative and data management workflows.

- Tech Benchmarking: Contrast this lightweight mobile edge network with heavy-duty orchestrators like Kubernetes.

- Production Blueprint: Deliver an end-to-end system design and functional specification for real-world deployment.
   

# Exploration: 
 We analyze the potential of cabin crew devices to preprocess data collected from various onboard sources, such as passenger service systems, in-flight entertainment systems, and operational data. We have taken the DTN sdk to validate the prototype. Then, what's next? We investigate the communication protocols and data formats required for effective data sharing among devices and with onboard services. The cabin crew devices are treated as nodes or data endpoints, and we evaluate how mobile edge nodes will interact with these endpoints to aggregate, filter, and analyze data in real-time. 

Finally,  we assess the process of transferring preprocessed data from cabin crew devices to backend servers once a high-speed terrestrial network is available, and then we analyze the reliability and efficiency of data transfer methods, including potential challenges in data integrity and synchronization. 


# System Design:
We develop a detailed system design that outlines the architecture, components, and interactions of the distributed edge network, including mobile edge nodes and data endpoints. 


