---
permalink: /technology/
title: "Technology"
author_profile: true
toc: true
toc_icon: "terminal"
#classes: wide
---

Some software packages I have authored...

## `Anime`
<p style="text-align:justify;"> <code>Anime</code> - Atmospheric aNd Instrumental models in the Measurement Equation - is an instrument modelling framework for radio interferometry written in Julia, an open source, high performance language for scientific computing. Anime aims to support efficient handling of various data formats commonly used in <a href="https://en.wikipedia.org/wiki/Very-long-baseline_interferometry">very long baseline interferometry</a> (VLBI), provide seamless conversion between these formats and a variety of data products as output by a VLBI network, and integrate with other Julia-based software packages for VLBI data analysis.

[Code](https://github.com/iniyannatarajan/Anime.jl) [Docs](https://iniyannatarajan.github.io/Anime.jl/stable/)

## `MeqSilhouette`

<p style="text-align:justify;"> I am the current lead developer of the VLBI observation simulator <code>MeqSilhouette</code>. It has been used in peer-reviewed publications
for generating synthetic obervations of black holes with the EHT, including the <a href="https://iopscience.iop.org/journal/2041-8205/page/Focus_on_EHT">six letters</a> 
published on April 10, 2019, presenting the first ever images of a black hole.</p>

[Code](https://github.com/rdeane/MeqSilhouette/) [Docs](https://meqsilhouette.readthedocs.io/)

## `zagros`

<p style="text-align:justify;"> <code>zagros</code> is a parametric Bayesian inference tool written in <code>python</code> for analysing radio interferometric data.
Earlier versions of the same framework have been used to analyse VLBI obervations with the <a href="https://www.evlbi.org/">European VLBI Network</a> (EVN). The current version has been used to calibrate synthetic EHT observations 
in the presence of atmospheric effects that affect the quality of radio observations (<a href='https://arxiv.org/abs/2005.12655'>Natarajan et al. 2020</a>).</p>

[Code](https://github.com/iniyannatarajan/zagros) [Docs](https://zagros.readthedocs.io/en/latest/)

## Other software

* `uvcovplot` - standalone script with bells and whistles to plot the *uv*-coverage of an interferometric array ([code](https://github.com/iniyannatarajan/uvcovplot)).

* `startrail` - create composite images of star trails from multiple snapshots and optionally perform dark frame correction ([code](https://github.com/iniyannatarajan/startrail)).

* In addition, I also work on calibration software and pipelines for the analysis of Event Horizon Telescope (EHT) observations.
