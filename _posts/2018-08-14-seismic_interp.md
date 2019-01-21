---
title: "Relaxation algorithms for matrix completion, with applications to seismic travel-time data interpolation"
excerpt: "We developed a fast, amenable low-rank interpolation technique for travel time tomography data."
header:
  image: /assets/images/helen/msthelen.jpg
  teaser: assets/images/helen/msthelen.jpg
sidebar:
  - title: "Journal:"
    image: /assets/images/helen/doe.png
    image_alt: "logo"
    text: "Inverse Problems"
gallery:
  - url: /assets/images/helen/obs_res_single1.jpg
    image_path: assets/images/helen/obs_res_single1.jpg
    alt: "Variable Relaxation"
  - url: /assets/images/helen/interpolated_vr_single1.jpg
    image_path: assets/images/helen/interpolated_vr_single1.jpg
    alt: "Variable Relaxation"
  - url: /assets/images/helen/interpolated_vrs0_single1.jpg
    image_path: assets/images/helen/interpolated_vrs0_single1.jpg
    alt: "Variable Relaxation with exact data fitting."
  - url: /assets/images/helen/interpolated_fista_single1.jpg
    image_path: assets/images/helen/interpolated_fista_single1.jpg
    alt: "FISTA"
  - url: /assets/images/helen/interpolated_lbfgs_single1.jpg
    image_path: assets/images/helen/interpolated_lbfgs_single1.jpg
    alt: "L-BFGS"
  - url: /assets/images/helen/interpolated_model_single1.jpg
    image_path: assets/images/helen/interpolated_model_single1.jpg
    alt: "'True' Model"
  - url: /assets/images/helen/obj_total.jpg
    image_path: assets/images/helen/obj_total.jpg
    alt: "Objective Value Decay"
tags: [low-rank, nonsmooth, nonconvex, relaxation, interpolation, travel time tomography]
---
This was a project that we developed while working with [Kenneth Creager](https://www.ess.washington.edu/people/profile.php?pid=creager--ken), [Carl Ulberg](https://www.ess.washington.edu/people/profile.php?pid=ulberg--carl), and [Rajiv Kumar](https://ca.linkedin.com/in/rajiv-kumar-63031a9). It was submitted to Inverse problems in August of 2018 and accepted in December 2018. You can find the ArXiv preprint [here](https://arxiv.org/pdf/1808.04515.pdf).


Travel time tomography is used to infer the underlying three-dimensional
wavespeed structure of the Earth by fitting seismic travel time data collected at surface
stations. Data interpolation and denoising techniques are important pre-processing
steps that use prior knowledge about the data, including parsimony in the frequency
and wavelet domains, low-rank structure of matricizations, and local smoothness.
We show how local smoothness structure can be combined with low rank constraints
using level-set optimization formulations, and develop a new relaxation algorithm that
can efficiently solve these joint problems. In the seismology setting, we use the approach
to interpolate missing stations and de-noise observed stations. The new approach is
competitive with alternative algorithms, and offers new functionality to interpolate
observed data using both smoothness and low rank structure in the presence of data
fitting constraints.

{% include gallery caption="Here are some of the fitting results with our algorithm, and some other competing methods." %}
Poster presentation from the DOE CSGF Annual Conference in Arlington, Virginia: 
<iframe src="https://drive.google.com/file/d/1jxGqbSEpEKQ-_hV96lo78kDnfuS-qDi5/preview" width="640" height="480"></iframe>