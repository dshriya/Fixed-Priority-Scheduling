# Fixed-Priority-Scheduling on Multiprocessors

**Team members:**
Shriya Dullur

Abhinav Siddharth

## Summary

This project is an implementation of the semi-partitioned fixed-priority scheduling algorithm on multiprocessors. The algorithm is described in the paper [Semi-Partitioned Fixed-Priority Scheduling on Multiprocessors](https://ieeexplore.ieee.org/document/7780005). The algorithm is implemented in Python and tested on a simulator. The simulator is also implemented in Python.
This project compares semi-partitioned fixed priority algorithm with other partitioned fixed-Priority Scheduling algorithms like PDM, FBB-FDD etc
## Summary of 'Code' folder

- `main.ipynb` contains the utility functions used in the above files.
- `partitioned_algos.py` contains the implementation of the partitioned algorithms.
- `semi_partitioned_algos.py` contains the implementation of the semi-partitioned algorithms.
- `simulators.py` contains the implementation of the simulator used to test the above algorithms.
- `task_generator.py` contains the code for generating tasks. Source code used by SimSo, free software under GPL license. Link: [Github](https://github.com/MaximeCheramy/simso/blob/master/simso/generator/task_generator.py).
- `utils.py` contains the utility functions used in the above files.
