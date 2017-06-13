---
layout: post
title:  "Jonathan Marvin"
date:   2017-06-13 15:30:00 -0400
categories: "JaneliaCrustaceanMeeting2017"
---

# Topic
**How to make probes**

# Notes
* Worked on GCaMP and made many probes and sensors based on antobody
* GCaMP binds Ca2+ and increase the DeltaF/F.
  * Detect change in the derivative.
* History of GCaMP
  * Change made to GCaMP 3 was to remove Ubiquitilation tail on N-term allowed for cytoplasm to be overfilled by the protein (better signal)
  * Change to GCaMP 5 increased the DeltaF/F by individual mutations
  * Change to GCaMP 6 modified kinetics and affinity -> Able to respond to individual section of neurites
  * CCL: 15 years later, engineering allowed to create a sensor that allows for sub-cellular resolution of Ca imaging.
* But neurons are more than just Calcium !
  * Many metabolites and neurotransmitters
* How to make a metabolites and neurotransmitters sensor ?
  * Take a conformation changing protein family
  * Insert a GFP at the right place so that it changes fluorescent upon binding.
  * try test repeat
* They have sensors for like so many neurotransmitters and metabolites (>15)
  * Example: Glutamate (iGluSnFR)
    * seems to work looks like Ca imaging
    * Able to do sub-cellular imaging
    * Show that in visual system Glutamate is used in directionality recognition.
  * Example: Gaba
    * Does not work as well yet (deltaF/F = 6%)
    * Sensor works but for higher concentration of Gaba than physiological.
  * Example: Acetylcholine
    * does not work in vitro ... but works in vivo O.o
      * He is not sure why in vitro does not work, maybe Act is taken up by the receptor before the sensor sees it.
  * Example: ATP sensor
    * Not tight enough for sub-cellular but good enough for soma measurement.
    * Glucose starve -> ATP goes down
    * Glucose back -> ATP goes up
  * Example: Glucose Sensor
    * Dual color imaging of zebrafish larvae
      * Ca activity spikes correlate with glucose spikes
      * if starved larvea, glucose is non correlated.
* All sensor available (email loogerl@janelia.hmmi.org or marvinj@janelia.hhmi.org)
