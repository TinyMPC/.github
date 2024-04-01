# TinyMPC - Accelerated and Compressed Model-Predictive Control

TinyMPC is an optimization solver designed for convex model-predictive control, 
offering high speed and a minimal memory footprint. 
Implemented in pure C/C++, it carries the MIT license and can be compiled into an embedded solver,
making it particularly well-suited for control and robotics applications. 
Additionally, TinyMPC provides interactive interfaces for seamless integration with high-level languages such as Python, Julia, and Matlab.

[**Visit the documentation**](https://tinympc.org) to learn how to use TinyMPC.

[**Visit our GitHub Discussions page**](https://github.com/TinyMPC/discussions) for any questions related to the solver!

If you use TinyMPC in an academic work, please cite the relevant papers:
```
@inproceedings{tinympc,
      title={TinyMPC: Model-Predictive Control on Resource-Constrained Microcontrollers}, 
      author={Khai Nguyen and Sam Schoedel and Anoushka Alavilli and Brian Plancher and Zachary Manchester},
      booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
      year = {2024}
}
```
```
@misc{tinympc2,
      title={Code Generation for Conic Model-Predictive Control on Microcontrollers with TinyMPC}, 
      author={Sam Schoedel and Khai Nguyen and Elakhya Nedumaran and Brian Plancher and Zachary Manchester},
      year={2024},
      eprint={2403.18149},
      archivePrefix={arXiv},
}


For more information, please see the [TinyMPC website](https://tinympc.org). 

This project was conducted within the [Robotic Exploration Lab](http://rexlab.ri.cmu.edu/), at Carnegie Mellon University.

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

