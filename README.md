# Visual-Attention Siamese Network for Object Localization

**VGG16-based Siamese network with a visual-attention mechanism that detects and localizes an object of interest in altered environments — reaching MSE 0.003 with faster convergence than the reference architecture.**

📓 [**Code notebook**](./Code.ipynb) · 🎞 [**Slides (PDF)**](./Lokesh_Attention_PPT.pdf)

## Overview
Pick-and-place robots must re-locate an object of interest even when the surrounding scene changes. This is a **reproducible study of attention mechanisms** for that problem: an end-to-end Siamese network (Keras) compares a template of the object against the live scene, with a visual-attention module focusing the comparison, to detect and localize the object in altered environments.

## Method
- Siamese architecture with a **VGG16 backbone** and visual-attention mechanism, implemented end-to-end in Keras.
- Template-vs-scene matching for localization under environmental changes.

## Results
- Localization error of **MSE 0.003**.
- **Faster convergence with the VGG16 backbone** than the architecture used in the reference literature.

## Context
Graduate research project, Robotics & Autonomous Systems, **IISc Bengaluru** (Jun–Jul 2022).
