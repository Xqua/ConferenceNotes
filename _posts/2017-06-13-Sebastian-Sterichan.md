---
layout: post
title:  "Sebastian Streichan"
date:   2017-06-13 15:00:00 -0400
categories: "Janelia Crustacean meeting"
---

# Topic
**Tissue flows ini morphogenesis**

# Notes
* Using lightsheet microscopy to study morphogenesis
* Take 3D images and map it back with a projection on a plane
* Use the plane as a basis for algorithm
* Map back to the 3D and do force and physics measures
* **Bellow notes published:** [paper](https://arxiv.org/abs/1701.07100)
* Integrate Mechanical Stress and how it drives the flow in gastrulation of Dmel.
  * Use Myosin II (spaguety squash) and H2B to map flow fields.
  * Automated myosin anisotropy detection
    * Using Radon Transform to detect lines on subset of the picture.
    * Gives you partial mapping but it works pretty well.
    * Then estimate the anisotropy of myosin WITHOUT completing the cells.
  * Trying to find a function that describe the flow of cells
    * Made a model that consist of fluid dynamic liquid flow
    * Two side of equation,
      * first is compressible fluid.
      * second, B(t) is the incompressible fluid term.
  * Almost works only needed to add one parameter, the midline of the embryo.
  * With that one parameter then the model of liquid flow explains morphogenesis deformation of ventral furrow formation (90% prediction)
* Looked then a Twist mutant
  * Reduced kinetic in the embryo due to First reduced anisotropy then reduce asymmetry
