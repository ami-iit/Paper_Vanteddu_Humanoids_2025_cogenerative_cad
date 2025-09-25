<h1 align="center">
 CAD-Driven Co-Design for Flight-Ready Jet-Powered Humanoids
</h1>

<div align="center">
Punith Reddy Vanteddu, Davide Gorbani, Giuseppe L'Erario, Hosameldin Awadalla Omer Mohamed, Fabio Bergonti, Daniele Pucci
</div>

<p align="center">




https://github.com/user-attachments/assets/cc03c986-4a7a-4ec2-a6cf-fcf51d004f84






</p>
<div align="center">
  <a href="#Installation"><b>Installation</b></a> |
  <a href="https://arxiv.org/pdf/2509.14935"><b>Paper</b></a> |
  <a href="https://youtu.be/2AHclnjdIwM"><b>Video</b></a>
</div>

## Abstract

This paper presents a CAD-driven co-design framework for optimizing jet-powered aerial humanoid robots to execute dynamically constrained trajectories. Starting from the iRonCub-Mk3 model, a Design of Experiments (DoE) approach is used to generate 5,000 geometrically varied and mechanically feasible designs by modifying limb dimensions, jet interface geometry (e.g., angle and offset), and overall mass distribution. Each model is constructed through CAD assemblies to ensure structural validity and compatibility with simulation tools. To reduce computational cost and enable parameter sensitivity analysis, the models are clustered using K-means, with representative centroids selected for evaluation. A minimum-jerk trajectory is used to assess flight performance, providing position and velocity references for a momentum-based linearized Model Predictive Control (MPC) strategy. A multi-objective optimization is then conducted using the NSGA-II algorithm, jointly exploring the space of design centroids and MPC gain parameters. The objectives are to minimize trajectory tracking error and mechanical energy expenditure. The framework outputs a set of flight-ready humanoid configurations with validated control parameters, offering a structured method for selecting and implementing feasible aerial humanoid designs.

## Installation

1. Clone the repository:
  ```bash
  git clone https://github.com/ami-iit/Paper_Vanteddu_Humanoids_2025_cogenerative_cad.git
  ```



### Maintainer

This repository is maintained by:

| | |
|:---:|:---:|
| [<img src="https://github.com/vpunithreddy.png" width="40">](https://github.com/vpunithreddy) | [@vpunithreddy](https://github.com/vpunithreddy) |

<p align="left">
   <a href="https://github.com/ami-iit/Paper_Vanteddu_Humanoids_2025_cogenerative_cad/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ami-iit/Paper_Vanteddu_Humanoids_2025_cogenerative_cad" alt="Size" class="center"/></a>
</p>

