---
layout: post
title:  "Damian Kao"
date:   2017-06-13 17:00:00 -0400
categories: "JaneliaCrustaceanMeeting2017"
---

# Topic
**Assembly of Parhyale Genome**

# Notes
* 28K genes on 15K scaffolds (about 1/3 of the scafolds are genic)
* K-mer spectra is a good measure of diversity of sequences in your genomes
  * show freq of a given K-mer in the genome.
* For Ph 1st peak at 55 and second smaller peak at 125
* estimated size is 2.4gb, and scaffold lenght is 2.5gb
* Why do we see so much polymorphism in Parhyale, given that the genome comes from an isogenic line.
  * hybrid of two closely related specie ?
  * duplication ?
  * other ?
* Assembly : Unitig -> Contig -> scaffolds
  * unitig using De-Brujin graphs.
    * K-mer parameter of graph is critical to assemble correctly
    * lower k means more unitigs but of lower lenght and quality in general
    * Higher k means less unitig of longer lenght but higher quality
    * Thus tradeoff between both.
  * Contig Reduction
    * Removed with CDHIT the repetitive seq and merge unitig together.
    * After contiging the K-mer spectra only has one peak at 50 meaning removal of heterozygozity.
* Reassembly
  * String graph assembler instead of De-Bruijin graph.
  * performed all vs all alignement with LAST
  * unitig reduction by removing sequences that overlapped.
  * assembly improvement
    * more ORF are found N50 increase and contig number dropped.
  * SSPACE to scaffold
* review of new methods
  * Dovetail: Proximity ligation methods
    * Issue with contig orientation
  * 10x genomics:
    * Same issue
  * Nanopore
    * Interesting but the sequencing quality leads to difficulties.
    * Good for scafolding.
  
