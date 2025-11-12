====================
Prepare for Beamtime
====================

This page provides practical guidance for preparing your beamtime at the **BEATS beamline**.  
Good preparation is essential for efficient and productive measurements.

It combines general best practices from other tomography facilities (e.g. PSI–TOMCAT) with BEATS-specific requirements.

---------------------------------------
Travel and Guesthouse Arrangements
---------------------------------------

The `SESAME User Office <https://www.sesame.org.jo/for-users/sesame-user-office>`_ will contact you to organize your visit, including:

- Guesthouse reservation  
- Access card and site entry  
- Safety training coordination  

Read the points below before your visit to ensure a smooth start of your beamtime at BEATS.

---------------------------------------
General Preparations Before Arrival
---------------------------------------

Before your arrival, make sure to:

- Register as a **SESAME user** via the DUO system.  
- Request a **badge** and **dosimeter** in advance (required for site access).  
- Verify that all members of your experiment team are registered.  
- Review the **SESAME safety regulations** and beamline safety rules.  
- If your experiment involves hazardous materials, contact your local scientist for prior approval.

Failure to comply with safety or access requirements may lead to delays or denied access.

---------------------------------------
Safety Guidelines and Beamline Orientation
---------------------------------------

All users must comply with SESAME’s safety rules and regulations.  
The **main proposer** is responsible for ensuring all team members have completed safety training and understand the relevant procedures.

If any safety-related aspect of your experiment has changed since the proposal submission, notify your **beamline scientist** immediately so that a safety assessment can be completed in advance.

Users are reminded to:

- Always work **in pairs**, especially for long or complex measurements.  
- Get sufficient rest and plan **shift rotations** for multi-day experiments.  
- Follow the :ref:`Hutch Search Procedure` carefully before each data acquisition session.

---------------------------------------
Contact Your Local Scientist
---------------------------------------

Each user experiment is supported by a **BEATS beamline scientist**, who will be your main point of contact before, during, and after the beamtime.

- You can find your assigned contact in the DUO schedule for BEATS.  
- Reach out **well before** your beamtime to discuss equipment setup, calibration needs, or special configurations.  
- If specific sample environments or detectors must be installed, they should be reserved and tested before your arrival.

---------------------------------------
Beamline Setup and Logistics
---------------------------------------

### Detector setup

BEATS supports high-resolution tomography using several detectors and optics configurations.  
Changing between configurations may require **installation and calibration time**—coordinate this with your local contact.

### Setup and cleanup time

Beamline setup and post-experiment cleanup are part of your allocated beamtime.  
Plan sufficient time at the beginning and end of your experiment to ensure smooth transition between user groups.

### Technical support

Technical staff are available during working hours to assist with complex setups.  
Notify your beamline scientist **in advance** if you expect to need technical support.

---------------------------------------
Sample Preparation
---------------------------------------

### Sample shape and size

The **optimal geometry** for tomography is a **cylinder**.  
Prepare your samples as close as possible to this shape to achieve uniform rotation and consistent projections.

Pay attention to **sample absorption**:  
highly absorbing materials should be made **as small and thin as feasible** to ensure good transmission and image quality.

### Sample holders

Samples should ideally be mounted on pins fitting the **3.15 mm BEATS sample holder**.  
Contact beamline technicians if you require adapters or custom mounts.

### Sample stability

Samples must remain stable throughout the entire measurement.  
Instability (e.g. from vibration, drying, or beam-induced motion) can seriously degrade reconstruction quality.  
Consult your beamline scientist for recommendations on fixation methods and radiation protection strategies.

---------------------------------------
Visualize and Inspect Your 3D Data
---------------------------------------

To make efficient use of beamtime, be prepared to **inspect your reconstructed data**.

- You are expected to know basic operations in **ImageJ**.  
- See :ref:`Load reconstructed volume with ImageJ` for installation and usage instructions.  
- ImageJ can also be used for post-beamtime image processing and analysis.  
- Additional tools are listed under :ref:`Data analysis software`.

---------------------------------------
Bring Enough Storage
---------------------------------------

Following the `SESAME data policy <https://www.sesame.org.jo/for-users/user-guide/sesame-experimental-data-management-policy>`_, BEATS will archive your data for at least **5 years** after the experiment.

.. warning::
   Due to the large size of tomography datasets, **remote access is not possible** after the beamtime.  
   You are responsible for taking a copy of all data before leaving SESAME.  
   Bring **external drives with at least 4 TB of free space** (preferably formatted in Linux-compatible file systems).

---------------------------------------
Data Management and Transfer
---------------------------------------

### On-site storage

Raw data will be stored temporarily on the BEATS server under:
``/data/raw/<proposal_id>/``

Data are maintained for **60 days** after beamtime and then automatically removed.  
You will be notified two weeks before deletion. Always verify and back up your data promptly.

### Backup policy

Users are fully responsible for the **backup and long-term safety** of their data.  
While SESAME archives selected datasets, there is **no guaranteed backup** of all experimental data.

### Data transfer options

- **External drives:** USB3 or eSATA recommended. Avoid drives formatted only for macOS.  
- **Network transfer:** Can be arranged in advance; contact your beamline scientist.  
- **NAS systems:** Recommended for data exceeding 6–10 TB per session.

---------------------------------------
Shipping and Customs
---------------------------------------

If you plan to import instruments or samples into Jordan:

- Follow SESAME’s **import and customs procedures**.  
- Notify the **SESAME Import/Export Office** in advance to avoid delays.  
- Even samples carried personally must be declared properly.

Contact:
``import@sesame.org.jo`` for sample shipment guidance.

---------------------------------------
Beamline Essentials
---------------------------------------

Before your arrival, review these BEATS documentation sections:

- :ref:`Hutch Search Procedure`  
- :doc:`reconstruction` — Tomographic reconstruction workflow  
- :doc:`safety` — Beamline and lab safety information  
- :doc:`user_checklist` — Quick reference for visiting users

---------------------------------------
Version History
---------------------------------------
- v1.0 — Merged PSI–TOMCAT reference with BEATS-specific information (2025-11-07)
