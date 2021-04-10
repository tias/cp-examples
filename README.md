# CP-examples

This repository contains example problems and **visualizations** of different main flavors in constraint programming and discrete optimization, in general.

Its goal is to show the applicability for *classes of problems* such as scheduling-like, packing-like, etc. in analogy to what has been successfully done 
for machine learning (supervised, unsupervised, reinforcement).

## Requirements

* [MiniZinc](http://www.minizinc.org/)
* [MiniZinc-Python](https://minizinc-python.readthedocs.io/en/latest/)
* [PILlow](https://pillow.readthedocs.io/en/stable/)

## Example Problems

Each example has an associated `.mzn` file (and maybe some `.dzn` data files) and can be executed using the respective `run_xyz.py` Python file.

### [Scheduling](scheduling)

Assign tasks without overlaps and precedence requirements.

![An example solution to a scheduling problem.](scheduling/scheduling.png)

### [Packing](packing)
Fit as many rectangles within a square as possible. 

![An example solution to a packing problem.](packing/rect_packing.png)

### [Car-Sequencing](car-sequencing)
Put cars with several options in order such that consecutive capacity constraints are respected on an assembly line.

![An example solution to a scheduling problem.](car-sequencing/car-seq.png)
