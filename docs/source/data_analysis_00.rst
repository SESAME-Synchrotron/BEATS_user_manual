====================
Data Analysis
====================

----------------------
Data analysis software
----------------------

The following software can be used to inspect and process microtomography data from SESAME BEATS.

+-----------+-------------------------------------------------+-------------+------------------------------------------------------------+
| Name      | URL                                             | Open source | Features                                                   |
+===========+=================================================+=============+============================================================+
| ImageJ    | https://fiji.sc/                                | yes         | Essential for data collection and reconstruction           |
+-----------+-------------------------------------------------+-------------+------------------------------------------------------------+
| Dragonfly | https://www.theobjects.com/dragonfly/index.html | no          | 3D image analysis and visualization                        |
+-----------+-------------------------------------------------+-------------+------------------------------------------------------------+
| 3D Slicer | https://www.slicer.org/                         | yes         | 3D image analysis and visualization                        |
+-----------+-------------------------------------------------+-------------+------------------------------------------------------------+
| Paraview  | https://www.paraview.org/                       | yes         | 3D image rendering for advanced users                      |
+-----------+-------------------------------------------------+-------------+------------------------------------------------------------+

Inspect data with ImageJ
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Reconstructions at SESAME BEATS are saved as a stack of ``.TIFF`` images contained in a reconstruction folder. To load a reconstruction in ImageJ use the command ``File › Import › Image Sequence``. You can follow `this video <https://www.youtube.com/watch?v=rmQwHGap2ko>`_ for a detailed explanation on how to import image sequences.

.. figure:: /img/imagej_image_sequence.png
   :align: center
   :alt: Import image sequence in ImageJ

.. note::
   Always select the option ``Use Virtual Stack`` when you import large image stacks in ImageJ!


------------------------------
Image Processing Video Library
------------------------------

This page provides a curated list of tutorial videos for several widely used
image-processing platforms, including ImageJ/Fiji, 3D Slicer, and Dragonfly.

ImageJ / Fiji
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **Basic Image Processing Using ImageJ – PSI**  
  https://www.youtube.com/watch?v=QQQ7RGn3-8E&list=PLcDfeQH_rVdb1x_b_40IFFcCTrgpa1yHa

- **CT Data Analysis Techniques Using ImageJ – Rigaku**  
  https://www.youtube.com/watch?v=FcRQY1PzMJ8

- **ImageJ Getting Started Guide – Rigaku**  
  https://www.youtube.com/watch?v=i2psSGyOyrg

- **X-ray Computed Tomography for Materials & Life Sciences – Rigaku**  
  https://rigaku.com/products/imaging-ndt/x-ray-ct/learning/x-ray-ct-webinars-and-workshops/x-ray-ct-webinar-series

- **ImageJ/Fiji SEM 3D Image Analysis Playlist**  
  https://www.youtube.com/playlist?list=PLROw8eoOoRBMqVY5_owK8zjLOqaeN9242

- **Using ImageJ (FIJI) and 3D Slicer to visualize microCT image stack**  
  https://www.youtube.com/watch?v=9Ike3_MOIEw

3D Slicer
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **3D Slicer Tutorial Playlist**  
  https://www.youtube.com/playlist?list=PLeaIM0zUlEqswa6Pskg9uMq15LiWWYP39

- **3D Slicer Tutorial #2: Manual Segmentation and Thresholding**  
  https://www.youtube.com/watch?v=ZRYMItzwg8g

- **CT Segmentation in 3D Slicer**  
  https://www.youtube.com/watch?v=0l-vXTfFtGw

Dragonfly
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **Dragonfly User Tutorials**  
  https://dragonfly.comet.tech/en/resources/user-tutorials

- **Dragonfly YouTube Video Gallery**  
  https://www.youtube.com/@dragonfly_software

General Videos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- **Synchrotron X ray imaging and computed tomography - Paul Tafforeau (ESRF)**
  https://www.youtube.com/watch?v=nYxCyJZlP1A

- **Tomography Beamline Tour - BMIT (Canadian Light Source)**
  https://www.youtube.com/watch?v=tX2hbRLNn_0&pp=ygUWc3luY2hyb3Ryb24gdG9tb2dyYXBoeQ%3D%3D

- **Using synchrotron X-ray micro-computed tomography in natural and cultural heritage - V. Fernandez & C. Berruyer (Cambridge Uni Biological Anthropology Society)**
  https://www.youtube.com/watch?v=tJB1yIarNdA

------------------------------
Open Datasets
------------------------------

Open tomography datasets that can be used for testing and training image processing workflows.

- **SESAME BEATS CT reconstructions**  
  https://zenodo.org/records/15182529

- **SESAME BEATS sinogram**
  https://zenodo.org/records/10075277

- **The TomoBank Repository**  
  https://tomobank.readthedocs.io/en/latest/