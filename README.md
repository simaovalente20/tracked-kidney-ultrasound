# Tracked Kidney Ultrasound Acquisition Framework and Multi-Device Dataset

This repository accompanies the manuscript:

**A Unified Tracked Kidney Ultrasound Acquisition Framework and Multi-Device Dataset for Image-Guided Research**

## Status

The associated manuscript is currently in preparation.

The acquisition software and associated renal ultrasound dataset are planned to be made available for research purposes following publication of the associated manuscript.

Access will be provided upon request and will be subject to applicable institutional, ethical, and privacy requirements.

## Dataset overview

The dataset comprises renal ultrasound acquisitions from **50 adult participants (100 kidneys)**.

Each kidney is represented by:

- **1 handheld 2D US sweep**
- **1 cart-based 2D US sweep**
- **1 cart-based 3D US volumetric sequence**

This corresponds to **300 retained acquisition instances** across the three imaging modalities.

The acquisition setup combines:

- **Clarius C3 HD** handheld 2D ultrasound
- **GE Vivid E95 with 4VC-D probe** for cart-based 2D and 3D ultrasound
- **Polaris optical tracking**
- **Aurora electromagnetic tracking**
- Optional inertial sensing when available

Spatial tracking information is available according to acquisition phase and modality. Cross-system calibration between the Polaris and Aurora tracking systems enables spatial information from different tracking configurations to be related within a common reference framework.

Further dataset documentation, including acquisition configurations, spatial-data availability, and access conditions, will be provided upon publication.

## Acquisition software

The acquisition software provides a unified workflow for:

- ultrasound acquisition
- optical and electromagnetic tracking
- spatial calibration and coordinate mapping
- acquisition control and device-status monitoring
- structured data organization
- storage of image, tracking, and associated metadata

Software documentation and access instructions will be provided upon publication.

## Availability and access

The acquisition software and associated dataset will be available for research purposes following publication of the associated manuscript.

Access will be provided **upon request**, subject to applicable institutional, ethical, privacy, and data-sharing requirements.

Detailed access instructions will be made available through this repository upon publication.

## Contact

For enquiries before publication, please contact:

**Simão Valente**  
2Ai – Applied Artificial Intelligence Laboratory  
Polytechnic University of Cávado and Ave (IPCA)  
Email: spvalente@ipca.pt

## Citation

Citation information will be added upon publication of the associated manuscript.
