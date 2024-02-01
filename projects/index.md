---
title: Projects
nav:
  order: 2
  tooltip: Experiments, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

### Supervised, semisupervised, and unsupervised epileptogenic biomarker high-frequency oscillations discovery and classification in intercrinal EEG recording

Intracranially recorded interictal high-frequency oscillations have been proposed as a promising spatial biomarker of the epileptogenic zone. However, its visual verification is time-consuming and exhibits poor inter-rater reliability. Furthermore, no method is currently available to distinguish high-frequency oscillations generated from the epileptogenic zone from those generated from other areas, in this project, we design supervised models, weakly supervised models trained from clinical evidence, and even fully unsupervised models to automatically discover the morphological distinction between pathological HFO and physiological HFO. The retrospective study demonstrates that the discovery aligns with conventional clinical pathological definition and outperforms the state-of-the-art approach through the validation of a massive multi-center, multi-source dataset.

### PyHFO: Lightweight Deep Learning-powered End-to-End High-Frequency Oscillations Analysis Application

This study aims to develop and validate an end-to-end software platform, PyHFO, that streamlines the application of deep learning methodologies in detecting neurophysiological biomarkers for epileptogenic zones from EEG recordings. PyHFO, combines time-efficient HFO detection algorithms like short-term energy (STE) and Montreal Neurological Institute and Hospital (MNI) detectors. It incorporates deep learning models for artifact and HFO with spike classification, designed to operate efficiently on standard computer hardware. PyHFO demonstrated an ability to handle datasets efficiently, with optimization techniques enabling it to achieve speeds up to 50 times faster than traditional HFO detection methods. Users have the flexibility to employ our pre-trained deep learning model or use their EEG data for custom model training. PyHFO successfully bridges the computational challenge faced in applying deep learning techniques to EEG data analysis in epilepsy studies, presenting a feasible solution for both clinical and research settings. 

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

<!-- ## Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %} -->

<!-- ## More

{% include list.html component="card" data="projects" filters="group: " style="small" %} -->
