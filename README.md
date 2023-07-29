# Computational Design and Analysis of Mechanical Properties of 2D Materials & Heterostructures

Welcome to our computational research project repository, where our focus lies in deciphering the elastic and mechanical properties of 2D materials and their heterostructures. We achieve this by analyzing the mechanical properties under different conditions: at zero temperatures employing density functional theory (DFT) and at finite temperatures using ab-initio molecular dynamics (AIMD).

## Importance of Mechanical Properties in Material Design & Selection

The mechanical properties of a material are fundamental to its performance, durability, and utility in various applications. As such, they play a pivotal role in the design and selection of materials for any engineering application. For instance, the yield strength, toughness, and fatigue limit of a material can determine its suitability for construction or aeronautical engineering. Similarly, the elastic modulus and hardness of a material may be key factors when designing electronic devices or protective equipment. 

Specifically, in the context of 2D materials and their heterostructures, understanding their mechanical properties is critical. These materials, often only a few atoms thick, exhibit unique mechanical characteristics due to their low dimensionality. These include exceptional strength and flexibility, as well as unusual deformation mechanisms. Therefore, the mechanical properties can directly impact the material's performance in applications like nanoelectronics, optoelectronics, and energy storage devices.

Our project, therefore, seeks to provide comprehensive computational insights into the elastic and mechanical properties of 2D materials and their heterostructures. The ability to accurately predict these properties at different temperatures is essential for the design of new materials and for choosing the right material for a given application. 

We use density functional theory to perform our zero-temperature calculations. This quantum mechanical modeling method is ideal for investigating the electronic structure (ground state) of many-body systems. For finite temperatures, we employ ab-initio molecular dynamics. This first-principles approach allows us to simulate the real-time, temperature-dependent evolution of systems, making it particularly valuable for capturing the dynamics and mechanical properties of 2D materials at finite temperatures. We leverage the capabilities of **ElasTool**, a specialized toolkit developed in our group for high-throughput mechanical properties calculations, and **VASP** electronic structure code as the calculator. 


By providing this detailed understanding, our work aims to facilitate and advance the design and selection of new 2D materials for a wide array of practical applications.

## ElasTool

**ElasTool** is an integral part of this project. Available on [ElastoolOnGitHub](https://github.com/zhongliliu/elastool), it provides the necessary tools and functions to conduct the computations using VASP as the calculator.

## Project Objectives

Our primary objective is to characterize the elastic behavior of 2D materials, delivering critical insights into their mechanical properties. As a secondary aim, we've developed a machine learning model to discern the role of various structural attributes in defining the lattice constants of different 2D-based architectures.

To ensure the project's efficacy, we've implemented several optimization strategies:
- We have carefully chosen a set of 2D materials and heterostructures, concentrating on those with significant practical relevance. This approach maximizes computational efficiency and enhances the practical applicability of the results.
- We employ parallel computing methods to speed up the computations, effectively distributing the computational workload across multiple processors or nodes.
- We have developed and utilized machine learning models to gain deeper insight into the data and identify key design parameters, thereby boosting the project's overall capabilities.
  
This research project seeks to fulfill two primary objectives:

1. To determine the elastic and mechanical properties of various 2D materials and their heterostructures using first-principles computations. These calculations consider two conditions: zero temperature and finite temperatures (specifically, 300 K and 600 K). We employ density functional theory for zero-temperature calculations and ab-initio molecular dynamics for finite-temperature simulations.

2. To establish a machine learning model that correlates the calculated properties with the materials' crystal structures. This model leverages information derived from first-principles computations to shed light on the relationship between structural features and the elastic and mechanical properties of 2D materials and their heterostructures.

## Publication

The outcomes of this project have been published in Nature Scientific Reports. You can access the publication via the following link: [DOI: 10.1038/s41598-022-07819-8](https://www.nature.com/articles/s41598-022-07819-8). Kindly reference any research output that utilizes the ElasTool and the associated data in your research and related activities.

In conclusion, this repository presents a valuable resource for researchers interested in examining the mechanical properties of 2D materials and utilizing the provided tools and methodologies.
