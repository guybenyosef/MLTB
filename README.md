# Minimum Length in the Tangent Bundle (MLTB)

This repository contains the code and resources for the papers: **"Minimum length in the tangent bundle as a model for curve completion"** [CVPR 2010](https://ieeexplore.ieee.org/abstract/document/5539930) and **"A Tangent Bundle Theory for Visual Curve Completion"** [PAMI 2012](https://ieeexplore.ieee.org/abstract/document/6112765). These papers introduce a mathematical framework for curve completion using the concept of minimum length in the tangent bundle.

## Introduction

The **Minimum Length in the Tangent Bundle (MLTB)** framework provides a biologically inspired approach to visual curve completion. It models curves in the tangent bundle and computes the shortest path that satisfies constraints in a geometric manifold, abstracting the structure of the early visual cortex and drawing inspiration from biological processes in human vision. 
This repository includes implementations of the model, experiments, and visualizations to support the concepts introduced in the papers.

## Installation

To install the required dependencies, run:

```
pip install -r requirements.txt
```

## Usage

The main functionality is provided in the `mltb.py` file located in the `src` directory. You can use the functions defined in this file to perform curve completion tasks.

### Example Usage

To see example usage, check the `MLTB_Examples.ipynb` file in the `notebooks/` directory. This file demonstrates how to compute and visualize curve completions using the MLTB framework.

## Related Papers

For more details on the mathematical framework and applications, refer to the original papers: 
* [Guy Ben-Yosef, Ohad Ben-Shahar, "Minimum length in the tangent bundle as a model for curve completion", IEEE Computer Vision and Pattern Recognition (CVPR), 2010, (oral presentation)](https://ieeexplore.ieee.org/abstract/document/5539930).
* [Guy Ben-Yosef, Ohad Ben-Shahar, "A Tangent Bundle Theory for Visual Curve Completion", IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI), 2012](https://ieeexplore.ieee.org/abstract/document/6112765).

Other related papers on tangent bundle theory:
* [Ohad Ben-Shahar, Guy Ben-Yosef, "Tangent Bundle Elastica and Computer Vision", IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI), 2014](https://ieeexplore.ieee.org/abstract/document/6866207).
* [Guy Ben-Yosef, Ohad Ben-Shahar, "Tangent Bundle Curve Completion with Locally Connected Parallel Networks", Neural Computation, 2012](https://direct.mit.edu/neco/article-abstract/24/12/3277/7834/Tangent-Bundle-Curve-Completion-with-Locally).
* [Guy Ben-Yosef, Ohad Ben-Shahar, "A Biologically-Inspired Theory for Non-axiomatic Parametric Curve Completion", Asian Conference on Computer Vision (ACCV), 2010](https://link.springer.com/chapter/10.1007/978-3-642-19309-5_27).

## Citation

If you use this code in your research, please cite the papers:

```
@inproceedings{mltb_cvpr2010,
    title={Minimum length in the tangent bundle as a model for curve completion},
    author={Ben-Yosef, Guy and Ben-Shahar, Ohad},
    booktitle={IEEE Computer Vision and Pattern Recognition (CVPR)},
    pages={1--8},
    year={2010},
    organization={IEEE}
}

@article{mltb_pami2012,
    title={A Tangent Bundle Theory for Visual Curve Completion},
    author={Ben-Yosef, Guy and Ben-Shahar, Ohad},
    journal={IEEE Transactions on Pattern Analysis and Machine Intelligence},
    volume={34},
    number={7},
    pages={1263--1280},
    year={2012},
    publisher={IEEE}
}
```

## Related Repositories

For a detailed implementation of the **Elastica in the Tangent Bundle (ETB)** model, please visit the following repository:

- [Elastica in the Tangent Bundle (ETB)](https://github.com/guybenyosef/ETB): This repository provides the code and resources for the Elastica in the Tangent Bundle model, as described in the related paper: *"Tangent Bundle Elastica and Computer Vision" (PAMI 2014)*. It includes implementations of the model, experiments, and visualizations.
