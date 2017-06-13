---
layout: post
title:  "Phillip Keller"
date:   2017-06-13 14:30:00 -0400
categories: "JaneliaCrustaceanMeeting2017"
---

# Topic
**Whole animal imaging at high spacio temporal res**

# Notes
* Imaging at high res Drosophila embryo and Zebrafish brain Ca
* Lightsheet is actually super old (been around since 1903 !)
* Lightsheet minimize PhotoDamage
* problems for Z axis resolution
  * Anisotropy of light is a solution to overcome resolution (similar to the super rez microscope at ENS ULM where they look at TF movement in XYZ at nanometer scale rez)
  * Multiview imaging and deconvolve to get a near isotropic resolution
* Built a 4 objective Lightsheet
  * Why? To get at the highest temporal and spacial rez possible
  * But then orthogonal Lightsheet becomes a problem (bleaching etc)
  * instead made a pencil beam that moves in a line scanning movement.
* **Able to image Calcium in whole drosophila embryo at 2Hz**
* Isotropic Multiview imaging brings true single cell rez.
* beautiful imaging of the developpement on the nervous system in drosophila
  * You can see that neurons gets patterned as they go.
* Changes in lightpath in embryos are complex
  * Relfractive index of embryo is deferent from media, thus the light bends as it travels inside the embryo
  * Loss of spacial resolution because of 1) out of focus light 2) less excitation in focus
  * Solution: **Adaptative Light Sheet Microscopy**
    * Measure the light bending by rotation the embryos in many angles
    * Compute a model
    * Inform the microscope and image

# Softwares    
janelia keller lab software

* [CUDA-LR](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwj1yuPOwLvUAhVKOT4KHRh3DvAQFggnMAA&url=https%3A%2F%2Fwww.janelia.org%2Fsites%2Fdefault%2Ffiles%2FLabs%2FKeller%2520Lab%2FStegmaier%25202016.pdf&usg=AFQjCNHchWsDaQuwReDT3kAl8HMODe1hqw&sig2=BziuPdUPzcuKWjyEdj1uTA) Multiview rec
* [KLB](https://bitbucket.org/fernandoamat/keller-lab-block-filetype)
* [TGMM](https://www.janelia.org/lab/keller-lab/software/fast-accurate-reconstruction-cell-lineages-large-scale-fluorescence) Cell tracking
* [RACE](https://www.janelia.org/publication/real-time-three-dimensional-cell-segmentation-large-scale-microscopy-data-developing) Segmentation
