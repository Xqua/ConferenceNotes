---
layout: post
title:  "Eric Edsinger"
date:   2017-06-13 17:00:00 -0400
categories: "JaneliaCrustaceanMeeting2017"
---

# Topic
**Establishing a zebrafish for Cephalopods**

# Notes
* Was looking for a model cephalopod, went to Okinawa, realized the diversity was insane their, tried a lot and sampled the tree.
* Decided on Pygmy squid because
  * Direct developpers
  * Transparents
  * Already have most of their organs.
  * Happy to chill, relax and not stressed in an aquarium, large number per aquarium
  * Large number of eggs everyday
* Main problem is the close the life cycle of the cephalopods.
* Lavis lab janelia Fluor
* Can do imaging (very transparent O.o)
* Can do CrispR KO
* but not much more.
* Trinotate
* Transcriptome Browser:
  * http://34.204.16.114/  user: squid0 / pass: 0squid
* Pipeline for Transcriptome assembly:
  * Sequening: Illumina
  * Quality filter: Illumina utils
  * Error Correct: Rcorrector
  * Normalize (remove duplicate seq): Khmer
  * Contamination filter: Kraken
  * Assemble: Trinity / CLC / idba_
  * Merge: EvidentialGene
  * Filter Size Cut-Off
  * Quality Filter: EvidentialGene vs Transrate
  * Completness: BUSCO
  * Annotate: InterProScan and blastp
  * Cluster: MMseqs2, OrthoMCL
  * Map: CLC
  * Explore: TBro, smartBlast
* Dovetail
  * Hi-C sequencing to assemble the chromosomes.
