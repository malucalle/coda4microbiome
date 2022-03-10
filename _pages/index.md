---
title: "coda4microbiome"
permalink: index.html
author_profile: true
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/about.jpg
  caption: "Photo by Malu Calle (c) 2021"  
excerpt: "Compositional Analysis for Microbiome Studies"
---

<img src="/assets/images/coda4microbiome.jpg" width=300 />

# Presentation 

 Understanding the role of the microbiome in human health and how it can be modulated is becoming increasingly relevant for preventive medicine and for the medical management of chronic diseases (Calle 2019). High-throughput sequencing technologies has boosted microbiome research but the compositional nature of microbiome data is a major challenge for their analysis.

 Microbiome count data is compositional since their total are constrained by the sequencing depth. Relative abundances (proportions) are obviously constraint by a sum equal to one. This total constraint induces strong dependencies among the observed abundances of the different taxa. In fact, nor the absolute abundance (read counts) nor the relative abundance (proportion) of one taxon alone are informative of the real abundance of the taxon in the environment. Instead, they provide information on the relative measure of abundance when compared to the abundance of other taxa in the same sample.

 We introduce a new package, coda4microbiome, that aims to bridge the gap between microbiome research and compositional data analysis (CoDA).
<p align="center">
  <img src="/assets/images/fillgap.png" width=600px />
</p>
