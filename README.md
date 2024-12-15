# Open-Smart-Mission-Planner

### Abstract 

Search and Rescue (SAR) operations are time-critical missions often carried out in complex, unpredictable environments. Despite the growing availability of small Uncrewed Aerial Systems (sUAS), current practices remain constrained by time-consuming, manually driven mission planning and limited situational awareness. In this paper, we present a Smart Mission Planner (SMP) implemented using a System of Systems (SoS) MAPE-K framework to autonomously coordinate and adapt a team of sUAS in SAR missions. Our approach integrates real-time computer vision (CV) for scene reconstruction, incorporating geo-spatial environmental features directly into the mission’s knowledge base. This enables dynamically prioritized search strategies that leverage terrain-specific best practices and operator-defined constraints. We introduce a new System Resilience Score (SRS) to quantitatively evaluate how well the system sustains coverage, workload balance, and rapid response to high-priority tasks amidst drone faults, prioritized task reassignment, and other stochastic adaptation events. We validate our approach through extensive simulations and real-world deployments using multi-level MAPE-K loops that govern both top-level mission planning and individual sUAS behavior. The results demonstrate that SMP effectively adapts to stochastic events, scales seamlessly to over 120 drones, and operates robustly in real-world conditions. 


### Demo

The video below demonstrates a sample Search and Rescue (SAR) mission featuring 5 drones simulated using the high-fidelity Gazebo physics engine, with PX4 as the Flight Controller Unit (FCU) and a custom-built GUI developed in Angular. The video has been sped up for convinience. 

https://github.com/user-attachments/assets/d1782828-f84f-47d9-841c-98aabe75c2f7

