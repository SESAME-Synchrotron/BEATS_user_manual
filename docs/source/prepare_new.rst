====================
Prepare for Beamtime
====================

.. note::
      Good preparation is essential for efficient and productive measurements.
      Read the points below before your visit to ensure a smooth start of your beamtime at BEATS.

---------------------------------------
Travel and Guesthouse Arrangements
---------------------------------------

The `SESAME User Office <https://www.sesame.org.jo/for-users/sesame-user-office>`_ will contact you to organize your visit, including:

- Guesthouse reservation  
- Access card and site entry  
- Safety training coordination  

---------------------------------------
General Preparations Before Arrival
---------------------------------------

Before your arrival, make sure to:

- Communicate to `SESAME User Office <https://www.sesame.org.jo/for-users/sesame-user-office>`_ information about all members of your experiment team.  
- Perform the **safety training**.
- If your experiment involves hazardous or biological materials, contact the local staff and user office.

.. warning::
      Failure to comply with safety or access requirements may lead to delays or denied access.


Bring Enough Storage
~~~~~~~~~~~~~~~~~~~~

Following the `SESAME data policy <https://www.sesame.org.jo/for-users/user-guide/sesame-experimental-data-management-policy>`_, BEATS will archive your data for at least **5 years** after the experiment.

.. warning::
   Due to the large size of tomography datasets, **downloading your data is not possible** after the beamtime.  

- You are responsible for taking a copy of all data before leaving SESAME.  
- Bring **external drives with at least 4 TB of free space**.

---------------------------------------
Safety Guidelines and Beamline Orientation
---------------------------------------

All users must comply with SESAME’s safety rules and regulations.  
The **main proposer** is responsible for ensuring all team members have completed safety training and understand the relevant procedures.

If any safety-related aspect of your experiment has changed since the proposal submission, notify the **beamline staff** immediately.

We recommend all our users to:

- Bring enough people and always work **in pairs**, especially for long or complex measurements.  
- Get sufficient rest and plan **shift rotations** for multi-day experiments.  

---------------------------------------
Contact The Beamline Scientists
---------------------------------------

Each user experiment is supported by a **BEATS beamline scientist**, who will be your main point of contact before, during, and after the beamtime.

- Reach out **well before** your beamtime to discuss your experiment setup.  
- If specific sample environments must be installed, this must be communicated before your arrival.

---------------------------------------
During The Beamtime
---------------------------------------

- Beamline setup and post-experiment cleanup are part of your allocated beamtime.  
- Plan sufficient time at the end of your experiment to copy your data!

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


Before your arrival, review these BEATS user checklist:

- :doc:`user_checklist` — Quick reference for visiting users
