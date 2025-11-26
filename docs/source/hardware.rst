=================
Beamline hardware
=================

.. _Sample mount:

Sample mount
------------

* Samples can be mounted on the tomography rotation stage with M4 screws as shown below.

* The following kinematic mounts from Newport are available:
    * `M-BK-1A <https://www.newport.com/p/M-BK-1A>`_ (download -> `drawing <https://www.newport.com/medias/sys_master/images/images/h7a/h3c/8933922308126/BK-1-S.pdf>`_).
    * `M-BK-2A <https://www.newport.com/p/M-BK-2A>`_ (download -> `drawing <https://www.newport.com/medias/sys_master/npresources/h9c/hde/9954493825054/BK-2A-S/BK-2A-S.pdf>`_).

.. figure:: /img/sample_mount_endstation2.png
	:align: center
	:alt: Sample mounting at BEATS

	*(LEFT) Sample mounted on BEATS tomography endstation with M-BK-1A magnetic holder. (CENTER) Entstation tomography plate. (RIGHT) Newport M-BK-1A and M-BK-2A top plates. All M4 holes can be used for custom sample support.*

Detectors
---------

.. figure:: /img/BEATS_detectors.png
	:align: center
	:alt: BEATS detectors

	*Detectors available at the BEATS beamline.*


.. figure:: /img/BEATS_detectors_FOV.png
	:align: center
	:alt: BEATS detectors Field Of View

	*BEATS detectors Field Of View (FOV).*

Detector 1 - White beam Twin-Microscope (Optique Peter, France)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+----------+----------------+-------------+
| Magnif.  | Field of view  | Pixel size  |
+==========+================+=============+
| 5×       | 3.4 × 2.8 mm2  | 1.3 μm      |
+----------+----------------+-------------+
| 7.5×     | 2.2 × 1.9 mm2  | 0.87 μm     |
+----------+----------------+-------------+
| 10×      | 1.7 × 1.4 mm2  | 0.65 μm     |
+----------+----------------+-------------+

Detector 2 - White beam medium resolution (ESRF, France)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+----------+------------------+-------------+
| Magnif.  | Field of view    | Pixel size  |
+==========+==================+=============+
| 0.5×     | 33.2 × 28.0 mm2  | 13.0 μm     |
+----------+------------------+-------------+
| 1×       | 16.6 × 14.0 mm2  | 6.5 μm      |
+----------+------------------+-------------+
| 2×       | 8.3 × 7.0 mm2    | 3.25 μm     |
+----------+------------------+-------------+

Detector 3 - Monochromatic Microscope (Optique Peter, France)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+----------+----------------+-------------+
| Magnif.  | Field of view  | Pixel size  |
+==========+================+=============+
| 4×       | 4.2 × 3.5 mm2  | 1.6 μm      |
+----------+----------------+-------------+
| 10×      | 1.7 × 1.4 mm2  | 0.65 μm     |
+----------+----------------+-------------+
| 20×      | 0.9 × 0.7 mm2  | 0.33 μm     |
+----------+----------------+-------------+

Cameras
-------

Each detector can work in combination with one of the following cameras. The EPICS PV in the table is used to stream the detector data in ImageJ using the EPICS AD Viewer plugin (see section :ref:`EPICS AD Viewer` below).

+--------+--------------------+-----------------------------+-------------+-----------------+
| Camera | Model              | EPICS PV                    | Sensor size | Pixel size [µm] |
+========+====================+=============================+=============+=================+
| CAM 1  | PCO edge.5.5       | ``TEST-PCO:Trans1:image1:`` | 2560 × 2160 | 6.5             |
+--------+--------------------+-----------------------------+-------------+-----------------+
| CAM 2  | ORYX FLIR 7.1 GigE | ``FLIR:image1:``            | 3208 × 2200 | 4.5             |
+--------+--------------------+-----------------------------+-------------+-----------------+

