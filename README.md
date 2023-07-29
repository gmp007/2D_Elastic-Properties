# First-Principles Design and Calculation of Elastic and Mechanical Properties of 2D Materials and Their Heterostructures

This repository hosts a computational research project centered on determining the elastic and mechanical properties of 2D materials and their heterostructures, both at zero and finite temperatures. We leverage the capabilities of **ElasTool**, a specialized toolkit we developed, in conjunction with **VASP**, for computation. 

Our primary objective is to characterize the elastic behavior of 2D materials, delivering critical insights into their mechanical properties. As a secondary aim, we've developed a machine learning model to discern the role of various structural attributes in defining the lattice constants of different 2D-based architectures.

To ensure the project's efficacy, we've implemented several optimization strategies:
- We have carefully chosen a set of 2D materials and heterostructures, concentrating on those with significant practical relevance. This approach maximizes computational efficiency and enhances the practical applicability of the results.
- We employ parallel computing methods to speed up the computations, effectively distributing the computational workload across multiple processors or nodes.
- We have developed and utilized machine learning models to gain deeper insight into the data and identify key design parameters, thereby boosting the project's overall capabilities.

## ElasTool

**ElasTool** is an integral part of this project. Available on GitHub, it provides the necessary tools and functions to conduct the computations using VASP as the calculator.

## Project Objectives

This research project seeks to fulfill two primary objectives:

1. To determine the elastic and mechanical properties of various 2D materials and their heterostructures using first-principles computations. These calculations consider two conditions: zero temperature and finite temperatures (specifically, 300 K and 600 K). We employ density functional theory for zero-temperature calculations and ab-initio molecular dynamics for finite-temperature simulations.

2. To establish a machine learning model that correlates the calculated properties with the materials' crystal structures. This model leverages information derived from first-principles computations to shed light on the relationship between structural features and the elastic and mechanical properties of 2D materials and their heterostructures.

## Publication

The outcomes of this project have been published in Nature Scientific Reports. You can access the publication via the following link: [DOI: 10.1038/s41598-022-07819-8](https://www.nature.com/articles/s41598-022-07819-8). Kindly reference any research output that utilizes the ElasTool and the associated data in your research and related activities.

In conclusion, this repository presents a valuable resource for researchers interested in examining the mechanical properties of 2D materials and utilizing the provided tools and methodologies.
