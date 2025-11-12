==============================
BEATS Beamtime User Checklist
==============================

This quick reference checklist is intended for visiting scientists and users preparing for beamtime at the **BEATS beamline**.
It summarizes the most important steps before, during, and after your experiment.

.. note::
   This page complements the detailed sections in:
   :doc:`prepare` — Preparation for beamtime  
   :doc:`quickstart` — Running your experiment  
   :doc:`reconstruction` — Data reconstruction and visualization

-------------------------------------
Before Your Beamtime (Preparation)
-------------------------------------

✅ **Travel and Accommodation**
   - Confirm your beamtime schedule and proposal ID.
   - Book travel and accommodation via SESAME User Office.
   - If staying at the SESAME guesthouse, check in at least **one day before** your session.

✅ **User Registration and Safety**
   - Complete SESAME user registration and safety training.
   - Bring your valid **ID/passport** and **safety badge** to access the facility.
   - Familiarize yourself with the :doc:`safety` page and emergency contacts.

✅ **Data and Storage**
   - Bring **sufficient storage** (≥2 TB recommended) formatted in a Linux-compatible filesystem.
   - Verify available space on the BEATS data server or provide external drives.
   - Label all storage devices with your proposal number and name.

✅ **Samples and Experiment Setup**
   - Prepare samples according to beamline requirements (size, mounting, containment).
   - Label all samples clearly.
   - Consult with your local contact about the best way to prepare your samples.
   - Notify beamline staff if your experiment involves **hazardous materials** or **cryogenic systems**.

-------------------------------------
During Your Beamtime
-------------------------------------

✅ **Arrival and Check-In**
   - Arrive **30 minutes before** your scheduled start.
   - Meet with BEATS beamline staff for a short introduction.
   - Verify access credentials for data storage and beamline PCs.

✅ **Beamline Startup**
   - Confirm vacuum status via the **Beamline Vacuum GUI** (:doc:`quickstart`).
   - Load your sample using the alignment and mounting tools.
   - Verify beam position and energy settings.

✅ **Data Acquisition**
   - Configure the **BEATS Dashboard** (:doc:`data_acquisition_user`) for your scan type:
     - *Single image*, *SSCAN*, or *TomoScan*.
   - Test a short preview scan before full acquisition.
   - Monitor data streams in real time; check for saturation or misalignment.

✅ **Data Management**
   - Confirm data are written to your proposal folder:
     ``/data/raw/<proposal_id>/``
   - Backup important files to your external storage before the end of beamtime.
   - Avoid deleting or renaming data during active acquisition.

-------------------------------------
After Your Beamtime
-------------------------------------

✅ **Beamline Shutdown**
   - Notify beamline staff when finished.
   - Follow local procedures for sample removal and cleanup.
   - Confirm the beam shutter and vacuum status before leaving the hutch.

✅ **Data Backup and Transfer**
   - Copy all relevant data and logs to your drive.
   - Verify the integrity of reconstructed datasets.

✅ **Reconstruction and Analysis**
   - Use the :doc:`reconstruction` pipeline to process your tomography data.
   - Visualize 3D volumes using **napari** or other supported tools.
   - Record reconstruction parameters for reproducibility.

✅ **Reporting and Feedback**
   - Acknowledge BEATS and SESAME in your publications.
   - Report any issues or suggestions to beamline staff.
   - Submit your **experiment feedback form** to help improve user support.

-------------------------------------
Quick Contacts
-------------------------------------

- **Beamline Scientist:** See :doc:`contacts`
- **Data & Analysis Support:** data@sesame.org.jo
- **Control Room:** internal extension 1234
- **Emergency:** dial 3333 from any SESAME phone

-------------------------------------
Version History
-------------------------------------
- v1.0 — Initial draft (2025-11-07) for inclusion in User Manual
