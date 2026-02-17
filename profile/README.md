# TinyMPC - Accelerated and Compressed Model-Predictive Control

TinyMPC is an optimization solver designed for convex model-predictive control, 
offering high speed and a minimal memory footprint. 
Implemented in pure C/C++, it carries the MIT license and can be compiled into an embedded solver,
making it particularly well-suited for control and robotics applications. 
Additionally, TinyMPC provides interactive interfaces for seamless integration with high-level languages such as Python, Julia, and Matlab.

[**Visit the documentation**](https://tinympc.org) to learn how to use TinyMPC.

[**Visit our GitHub Discussions page**](https://github.com/orgs/TinyMPC/discussions) for any questions related to the solver!

If you use TinyMPC in an academic work, please cite the relevant papers:

```
@inproceedings{tinympc,
      title={TinyMPC: Model-Predictive Control on Resource-Constrained Microcontrollers}, 
      author={Khai Nguyen and Sam Schoedel and Anoushka Alavilli and Brian Plancher and Zachary Manchester},
      booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
      year={2024},
}
```
```
@inproceedings{tinympc-adaptive,
      title={Robust and Efficient Embedded Convex Optimization through First-Order Adaptive Caching}, 
      author={Ishaan Mahajan and Brian Plancher},
      booktitle={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
      year={2025},
}
```
```
@inproceedings{conic-tinympc,
      title={Code Generation and Conic Constraints for Model-Predictive Control on Microcontrollers with Conic-TinyMPC}, 
      author={Ishaan Mahajan and Khai Nguyen and Sam Schoedel and Elakhya Nedumaran and Moises Mata and Brian Plancher and Zachary Manchester},
      booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
      year={2026},
}
```

For more information, please see the [TinyMPC website](https://tinympc.org). 

This project was conducted within the [Robotic Exploration Lab](https://roboticexplorationlab.org/), at Carnegie Mellon University.

## Installing

### C/C++

The TinyMPC C/C++ code can be found in the main [TinyMPC repository](https://github.com/TinyMPC/TinyMPC), and build instructions
can be found in the documentation.

### Python

The Python interactive interface with examples is available at [tinympc-python](https://github.com/TinyMPC/tinympc-python).

### MATLAB

The MATLAB interactive interface with examples is available at [tinympc-matlab](https://github.com/TinyMPC/tinympc-matlab). 

### Julia 

The Julia interactive interface with examples is available at [tinympc-julia](https://github.com/TinyMPC/tinympc-julia). 

### Running on MCUs

Numerical benchmarks against other solvers on MCUs are available [here](https://github.com/RoboticExplorationLab/mcu-solver-benchmarks).

### TinyMPC on the Crazyflie

TinyMPC-integrated firmware on the Crazyflie nano-quadrotor is available [here](https://github.com/RoboticExplorationLab/tinympc-crazyflie-firmware).

