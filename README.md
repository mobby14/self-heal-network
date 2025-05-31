# 📄 Project Report: Self-Healing Networks (SHN)

## 1. Introduction

In modern communication systems, network reliability is a crucial aspect. Failures in nodes or links can lead to serious communication breakdowns. Traditional networks rely on manual detection and recovery, which can be time-consuming and error-prone. This project explores the concept of **Self-Healing Networks (SHNs)** using AI-based solutions to automatically detect faults and recover from them, ensuring minimum disruption.

## 2. Objectives

- To simulate a computer network environment using Python.
- To implement AI-driven algorithms for fault detection and recovery.
- To visualize network states before and after fault resolution.
- To demonstrate the effectiveness of SHN in maintaining network connectivity and performance.

## 3. Tools and Libraries

This project was implemented using the following technologies:

- **Python 3.x** – Programming language used for implementation
- **NetworkX** – For graph-based network simulation
- **Matplotlib** – For network visualization
- **(Optional)** Scikit-learn – If any ML models are integrated for decision-making

## 4. Methodology

### 4.1 Network Modeling

The network is modeled as a graph where:
- **Nodes** represent computers, routers, or switches.
- **Edges** represent communication links.

### 4.2 Fault Simulation

Node or edge failures are artificially introduced into the network to simulate real-world disruptions. Faults are chosen randomly or based on predefined conditions.

### 4.3 Fault Detection

The system uses rule-based or AI-based checks to detect disconnected nodes, unreachable paths, or dropped packets. Visualization shows changes in connectivity.

### 4.4 Recovery Mechanism

Once a fault is detected:
- Redundant paths are activated.
- Nodes are rerouted to bypass faulty links.
- AI algorithms may suggest the most efficient path or repair strategy.

### 4.5 Visualization

Before and after states of the network are visualized to compare network health, highlighting failures and successful recoveries.

## 5. Results

- The simulation successfully demonstrated how self-healing mechanisms can detect and recover from network faults.
- Visualization clearly showed the difference in network topologies before and after recovery.
- The system ensured minimal loss in connectivity and robustness against node/link failures.

## 6. Conclusion

The Self-Healing Network simulation showcases the potential of integrating AI techniques in network management. By enabling real-time fault detection and automated recovery, network downtime can be significantly reduced. This project proves to be a foundational step toward building intelligent, resilient networks.

## 7. Future Work

- Integration of real machine learning models for adaptive recovery
- Testing on larger and dynamic network topologies
- Real-time simulations using packet flow analysis
- Deployment in edge computing and IoT networks

## 8. Authors

- **Charan U** – CB.EN.U4ECE22111  
- **Daejuswaram G** – CB.EN.U4ECE22115  
- **Mohan Kumar D** – CB.EN.U4ECE22132

## 9. References

1. NetworkX Documentation: https://networkx.org/
2. Matplotlib: https://matplotlib.org/
3. IEEE Journals on Self-Healing Networks and AI in Networking
