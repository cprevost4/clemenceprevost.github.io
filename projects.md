---
layout: page
title: Projects
---

## Super-resolution and unmixing in remote sensing

In remote sensing, the problem of super-resolution aims at reconstructing a high-resolution data cube from a hyperspectral and a multispectral image of the same scene. The hyperspectral image is spatially-degraded but has as high spectral resolution, while the multispectral image has high spatial resolution, at the cost of a low spectral resolution.
The super-resolution image of interest can then be used to extract materials and corresponding abundances, in a process termed unmixing.
<br/>
This project provides tensor-based algorithms for the super-resolution and unmixing tasks. Proposed models are assorted with recovery guarantees. The performance of the methods are assessed on real datasets in a variety of cases, for instance when several degradation operators are unknown or when the acquisitions are subject to some inter-image variability.

---

## Cramér-Rao bounds for coupled tensor models

In estimation theory, the Cramér-Rao bound is perhaps one of the most widely used tools for assessing the performance of an estimator. For coupled models, the literature refers to the so-called Constrained Cramér-Rao bound (CCRB), that is able to model the interactions between the various sources of information.
Due to the emergence of coupled tensor models in a variety of applications (e.g., remote sensing, medical imaging, spectrum cartography, chemometry), the 
CCRB for such models is of great interest.
<br/>
In this project, I provide closed-form of the CCRB for coupled tensor models used in remote sensing super-resolution and unmixing.
I assessed the performance of the estimators designed in the said project, showing that they reach the bounds.
I also designed a new bound subject to random equality constraints, and showed that is is usually tighter than the standard tool. 

---

## Multi-frame super-resolution in medical imaging

MRI is a very versatile imaging device that is able to provide 2D or 3D images of an organ of interest.
However, the acquisition of the latter suffer from a long acquisition time. Furthermore, patient motion can highly degrade the quality of the acquisition.
Finally, the machine limitation is often reached for very precise brain details.
<br/>
This project, in collaboration with INSERM and Nancy University Hospital, aims at reconstruction a 3D image of a brain using various acquisitions.
The observations are downsampled and interpolated in arbitrary orientations.
The aim is to reconstruct a high-quality image in a reduced computation time, using tensor low-rank modelling.



