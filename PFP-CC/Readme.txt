README
======

Thank you for visiting this repository.

This repository contains part of the code, input data, and computational results from our research on electric vehicle platoon formation with charging capacity constraints.

The research focuses on developing optimization and math-heuristic approaches for scheduling electric commercial vehicles (ECVs) traveling on a tree-shaped highway network while considering:
- platoon formation,
- charging points capacities,
- time window deadlines, and
- energy consumption differences between leaders and followers.

The repository includes:
- selected source codes,
- case study input data,
- selected reoptimization outputs, and
- computational results.


RELATED PUBLICATION
===================

@article{NUGRAHA2026107360,
title = {A math-heuristic for the platoon formation problem with charging capacities},
journal = {Computers & Operations Research},
volume = {188},
pages = {107360},
year = {2026},
issn = {0305-0548},
doi = {https://doi.org/10.1016/j.cor.2025.107360},
url = {https://www.sciencedirect.com/science/article/pii/S0305054825003892},
author = {Muhammad Ridwan Reza Nugraha and Mouna Kchaou-Boujelben and Young-Ji Byon and Adriana F. Gabor},
keywords = {Platooning, Electric vehicles, Scheduling, Charging capacity, Math-heuristic},
abstract = {With the emergence of electric connected and autonomous vehicles, there is an opportunity to utilize them to deliver commodities to destinations in a sustainable manner by grouping them in platoons. This study focuses on deriving close to optimal schedules for platoons of electric commercial vehicles (ECVs) traveling on a tree-shaped highway, with the objective of reducing overall energy consumption and travel time while complying with charging capacities and delivery deadlines. The model differentiates between leading and following vehicles by incorporating different energy consumptions. For this problem, we first propose an efficient Mixed-Integer Linear Programming (MILP) formulation based on the set of feasible charging schedules. To tackle large instances, we design a two-phase math-heuristic that solves successively reduced versions of the MILP on paths in the tree. These reduced MILPs use clusters of vehicles to reduce the number of potential platoon members or leaders of platoons based on specific vehicle characteristics and restrictions. Through numerical experiments, we show that the proposed MILP outperforms a recent MILP in the literature and the developed math-heuristic is able to obtain close to optimal solutions for small instances and is scalable to larger instances of up to 256 vehicles.}
}


CITATION
========

If you use this repository or reference this work in your research, please cite the paper above.


NOTES
=====

- This repository contains only part of the complete implementation used in the paper.
- Some datasets, preprocessing scripts, or experimental settings may not be included.
- The provided materials are intended for research and academic purposes.