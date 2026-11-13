# Liver SBRT: Regional Functional Analysis Using SPECT/CT

## Overview

This repository contains the final Python scripts developed for my 2026 Physics Honours research project, *Evaluation of Dose-Related Functional Changes in Patients with Liver Cancer Treated with Radiation Therapy*.

The project investigated changes in regional liver function following stereotactic body radiation therapy (SBRT), using longitudinal technetium-99m mebrofenin SPECT/CT imaging and radiotherapy planning data.

## Computational workflow

The analysis pipeline was developed to perform:

1. **Data preparation:** Processing radiotherapy planning data, including RTDOSE and RTSTRUCT files.
2. **Anatomical segmentation:** Generation of whole-liver, Couinaud segment and radiation dose-defined masks.
3. **Image registration:** Structure-guided rigid and boundary-guided B-spline deformable registration.
4. **Functional quantification:** Scaling SPECT measurements using clinically reported total liver function.
5. **Dose–function analysis:** Evaluation of regional functional changes using anatomical segments, discrete dose bands and voxel-wise measurements.
6. **Statistical analysis:** Assessment of regional functional changes and dose–response relationships.

## Software

The pipeline was implemented primarily in Python using SimpleITK, PlatiPy, NumPy, pandas and pydicom, alongside TotalSegmentator and 3D Slicer.

## Notes

The scripts were developed, adapted, debugged and evaluated for this research project using existing computational libraries. They are intended to document the study




