---
title: "Open microscopy"
shortd: "Single-molecule localization microscopy (SMLM) helped to reveal nanoscale molecular structures and their dynamics. However, it requires state-of-the-art scientific-grade equipment. We developed fully open-source cost-effective super-resolution microscope solution (approx. 50K Euro) that can perform dual-channel widefield, confocal and TIRF imaging. This project includes also robustly working dedicated open-source Python package for microscopes' hardware control, data acquisition, and analysis. It showed very low sample drift and allowed us to achieve  'ground truth' axial resolution of ~ 16 nm for DNA PAINT and ~ 26 nm for dSTORM. This project is standing on a base of miCube microscope (approx. 110K Euro). " 
type: open_microscopy
collection: research
date: 2022-02-06
author_profile: true
header:
  teaser: open_microscopy_image_MT.jpg
layout: archive
---

<div style="text-align: left">

The miEye: Bench-top super-resolution microscope with cost-effective equipment. This project is dedicated for super-resolution studies of biomolecule structures and dynamics in vitro and in living cells (bacteria and eukaryotes). We based the project on the open-source miCube platform developed by Dr. Johannes Hohlbein (<a href="https://hohlbeinlab.github.io/miCube/index.html"><span style="color:blue">miCube</span></a>). Our microscopy system performs dual-channel widefield, confocal and TIRF imaging. It leverages two types of excitation schemes: 1) single-mode (SM) fiber objective-based TIRF, and 2) multi-mode (MM) fiber output formation on the sample plane.<br>

<br>

The TIRF system is well suited to imaging molecules near the coverslip surface (like those in cell membranes or those bound to surface-immobilised DNA molecules) in the presence of a fluorescent background from other fluorescent molecules diffusing in solution. The TIRF system increases sensitivity and lowers noise by reducing background signal from fluorescently labelled molecules in solution. The MM fiber output formation on the sample plane combined with a home-made speckle-reducer reduces the risk of objective damage (in contrast to TIRF laser beam here is not focused on the back focal plane of the objective) and decreases laser power loss to create a homogeneous flat illumination profile. Both excitation schemes work well for STORM- and PALM-type super-resolution imaging, whether in vitro, in cells (living or fixed) or while tracking fluorescently labelled biomolecules as they diffuse inside living cells.<br>

<br>

In our system, we employ inexpensive but highly capable CMOS cameras. We pair high-frame-rate industrial-grade CMOS cameras with homemade cooling, simultaneous dual channel imaging, and illumination via a diode laser combiner (405, 488, 520, 638 nm) to maximize their utility. Similar commercial equipment would cost > 150 thousand Euro, while our system price is approximately 50 thousand Euro. These attractive solutions required us to develop Python-based microscope control, data acquisition and data analysis packages. Our microEye Python package controls hardware components and performs piezo-tracked autofocus to counter sample drift in the Z-axis. It also performs data processing, such as filtering of acquired images, cropping, Fourier ring correlation (FRC) to estimate systems resolution, thresholding, blob detection and similar. Based on recent discussions and citations (in Nature Methods), we believe that open-microscopy and open-source Python-based data analysis interests and can benefit the wider scientific community. Our work will help bring the latest microscopy technology to more laboratories, including those with limited capital, so that their research is limited by their imaginations rather than their access.

<br>

<figure style="width: 80%" class="align-center">
<img src='/images/open_microscopy_image_MT.jpg'>
<figcaption>miEye system.</figcaption>
</figure>

<br>

<a href="https://github.com/samhitech/microEye"><span style="color:blue">Here you can find our gitHub repository for the microEye Python package</span></a>

<br>

<a href="https://osf.io/j2fqy/"><span style="color:blue">Here you can find our OSF repository for the miEye hardware and software package</span></a>

<br>

{% include theme-team-members.html %}
{% include publication-list-theme.html %}




