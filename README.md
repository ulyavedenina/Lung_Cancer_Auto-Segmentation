# Lung Cancer Auto-Segmentation

## Overview

The project involves:

- **Extraction of subvolumes**: Generating smaller 3D patches on the base of original 3D data which include at least 1% of the tumor
- **Generating a new dataset**: Creating a standardized dataset by generating 10,000 examples of subvolumes.
- **Initializing a 3D U-Net architecture**: This architecture allows capturing spatial context 
- **Model Evaluation**: Using dice coefficient as an evaluation metric

On the test set, the dice coefficient reaches 0.7959, the soft dice loss is 0.1663.

## References

This code is inspired by the assignment **'Brain Tumor Auto-Segmentation for Magnetic Resonance Imaging (MRI)'** from the **AI for Medical Diagnosis** course, which is part of the **AI for Medicine Specialization**.
