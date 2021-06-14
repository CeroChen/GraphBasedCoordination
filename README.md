# A Graph-based Conflict-free Cooperation Method for Connected and Automated Vehicles at Unsignalized Intersections

Connected and automated vehicles have shown great potentials to improve traffic mobility and reduce emissions, especially at unsignalized intersections. Previous research has shown that vehicle passing order is the key influence factor in improving intersection traffic mobility. In this paper, we propose a graph-based cooperation method to formalize the conflict-free scheduling problem at an unsignalized intersection. Based on the graphic analysis, the vehicle's trajectory conflict relationship is modeled as a conflict directed graph and a coexisting undirected graph. Then, two graph-based methods are proposed to solve the vehicle passing order. One method is an improved depth-first spanning tree algorithm which aims to find the local optimal passing order for each vehicle. The other novel method is a minimum clique cover algorithm that solves the global optimal problem. These methods lead to a feasible vehicle passing order, which is also the geometry topology. Finally, a distributed control framework and the communication topology are presented to realize the conflict-free cooperation of the vehicles. Extensive numerical simulations are conducted in multiple vehicle input and traffic volumes, and simulation results verify the effectiveness of the proposed algorithms.

## Case study

<img src="https://github.com/CeroChen/GraphBashedCoordination/blob/main/DFST.gif" width="800" />

<img src="https://github.com/CeroChen/GraphBashedCoordination/blob/main/iDFST.gif" width="800" />

<img src="https://github.com/CeroChen/GraphBashedCoordination/blob/main/MCC.gif" width="800" />


<!-- For further details, please refer to:

Cai, M., Xu, Q., Chen, C., Wang, J., Li, K., Wang, J., & Zhu, Q. (2021). Formation Control for Multiple Connected and Automated Vehicles on Multi-lane Roads. arXiv preprint arXiv:2103.10287. (https://arxiv.org/abs/2103.10287) -->

