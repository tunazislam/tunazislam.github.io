---
title: "Analysis of Subtelomeric REXTAL Assemblies Using QUAST"
collection: publications
permalink: /publications/REXTAL_QUAST
citation: '<b>Tunazzina Islam</b>, Desh Ranjan, Eleanor Young, Ming Xiao, Mohammad Zubair, Harold Riethman. <i>Got accepted at [IEEE BIBM 2018](http://orienta.ugr.es/bibm2018/index) [Data Analytics in Metagenomics (DAM 2018) workshop](http://scm.ulster.ac.uk/~e10267487/DAM2018/index.html).</i>'
---
[[PDF]](https://tunazislam.github.io/files/REXTAL_QUAST_BIBM2018.pdf)


## Abstract
Genomic regions of high segmental duplication content and/or structural variation have led to gaps and misassemblies in the human reference sequence, and are refractory to assembly from whole-genome short-read datasets. Human subtelomere regions are highly enriched in both segmental duplication content and structural variations, and as a consequence are both impossible to assemble accurately and highly variable from individual to individual. Recently, we developed a pipeline for improved region-specific assembly called Regional Extension of Assemblies Using Linked-Reads (REXTAL) [1]. In this study, we evaluate REXTAL and genome-wide assembly (Supernova; [2]) approaches on 10X Genomics linked-reads data sets partitioned and barcoded using the Gel Bead in Emulsion(GEM) microfluidic method [3]. Our results describe the accuracy and relative performance of these two approaches using the reference-based assessment module of QUAST [4]. We show that REXTAL dramatically outperforms the Supernova whole genome assembler in subtelomeric segmental duplication regions, and results in highly accurate assemblies. Nearly all of the REXTAL “misassemblies” identified using default QUAST parameters simply pinpoint locations of tandem repeat arrays in the reference sequence where the repeat array length differs from that in the cognate REXTAL assembly by > 1000 bp.
