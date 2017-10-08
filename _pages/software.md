---
title: "Software"
permalink: /software/
author_profile: true
---

## GRecoMan

The ***G****raphical* ***Reco****nstruction* ***Man****ager* is a PyQT application for launching CT reconstructions on the computing cluster at the [TOMCAT beamline](http://www.psi.ch/sls/tomcat/). One can (i) interactively tweak all kinds of CT reconstruction (and filtering) settings and (ii) save/load those settings in order to reproduce full 3D volumetric data from raw tomographic projections. It works w/o problems in the SLS/TOMCAT computer infrastructure,  but the next goal is to add the possibility of using the [TomoPy backend](https://github.com/tomopy/tomopy). A very similar (and probably more mature) project is [Xi-cam](https://github.com/gnudo/Xi-cam), which is developed at [ALS](https://als.lbl.gov/).

[View on Github](https://github.com/gnudo/grecoman){: .notice}

## Misc

This repository should soon include most of the scripts I've developed and/or have been using recently. Currently those are scattered around different machines (at home/work) and accounts, but they should all eventually end up here. Below are just two links for now.

[LaTeX stuff](https://github.com/gnudo/latex){: .notice} [Python scripts](https://github.com/gnudo/python-scripts){: .notice}

## Quant3dlung

The quantitative 3D lung image tools originate form Lovric _et al._ [PLoS ONE 12 (9), e0183979 (2017), [http://doi.org/cddm](http://doi.org/cddm)] and can be used for a unique morphological and topological characterization of high-resolution lung image datasets. The package contains both the tools to reproduce the paper's results as well as some scripts to verify the performance of the algorithms.

[View on Github](https://github.com/gnudo/Quant3Dlung){: .notice}

## Source size calculator

The following package contains the source size calculation tools introduced in Lovric _et al._ [Opt. Express 22, 2745 (2014), [http://doi.org/q9m](http://doi.org/q9m)]. Those can be used to do all sorts of wave-optical simulations within the *Fresnel optical regime*, as for instance the simulation of the *Talbot effect* or use of a common grating interferometer.

[View on Github](https://github.com/gnudo/source-size-calculator){: .notice}
