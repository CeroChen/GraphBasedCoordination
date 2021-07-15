# Conflict-free Cooperation Method for Connected and Automated Vehicles at Unsignalized Intersections: Graph-based Modeling and Optimality Analysis
Connected and automated vehicles have shown great potential in improving traffic mobility and reducing emissions, especially at unsignalized intersections. Previous research has shown that vehicle passing order is the key influencing factor in improving intersection traffic mobility. In this paper, we propose a graph-based cooperation method to formalize the conflict-free scheduling problem at an unsignalized intersection. Based on graphical analysis, a vehicle's trajectory conflict relationship is modeled as a conflict directed graph and a coexisting undirected graph. Then, two graph-based methods are proposed to find the vehicle passing order. The first is an improved depth-first spanning tree algorithm, which aims to find the local optimal passing order vehicle by vehicle. The other novel method is a minimum clique cover algorithm, which identifies the global optimal solution. Finally, a distributed control framework and communication topology are presented to realize the conflict-free cooperation of vehicles. Extensive numerical simulations are conducted for various numbers of vehicles and traffic volumes, and the simulation results prove the effectiveness of the proposed algorithms.

## Case study

<img src="https://github.com/CeroChen/GraphBashedCoordination/blob/main/DFST.gif" width="800" />

<img src="https://github.com/CeroChen/GraphBashedCoordination/blob/main/iDFST.gif" width="800" />

<img src="https://github.com/CeroChen/GraphBashedCoordination/blob/main/MCC.gif" width="800" />


<!-- For further details, please refer to:

Cai, M., Xu, Q., Chen, C., Wang, J., Li, K., Wang, J., & Zhu, Q. (2021). Formation Control for Multiple Connected and Automated Vehicles on Multi-lane Roads. arXiv preprint arXiv:2103.10287. (https://arxiv.org/abs/2103.10287) -->

