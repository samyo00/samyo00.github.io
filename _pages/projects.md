---
layout: archive
permalink: /projects/
title: "Standout Projects I'm Proud of"
author_profile: true
---
# ENHANCING OPHTHALMIC BIOMARKER DETECTION: ACTIVE LEARNING STRATEGIES AND EXPLAINABLE AI FOR RADIOLOGICAL INTERPRETATION

ABSTRACT: Ophthalmic diseases are pervasive, and Optical Coherence Tomography (OCT) scanning plays a pivotal role in their diagnosis. Traditionally, experts have relied on manual identification of diseases and biomarkers from OCT scans. Recently, contemporary medical imaging practices increasingly leverage deep learning techniques to expedite and enhance diagnostic precision in ophthalmology. Within the realm of medical imaging, acquisition of datasets with accurately labeled data presents a significant challenge, primarily due to the expertise required for meticulous annotation by trained professionals. This article introduces a novel two-stage training strategy aimed at enhancing the identification of ophthalmic biomarkers utilizing OCT scans from the OLIVES dataset, which comprised only 12% labeled data. Our approach capitalizes on a robust methodology that effectively harnesses both labeled and unlabeled data, thereby improving biomarker identification accuracy. We employed active learning to leverage the unlabeled data, enhancing the identification of each biomarker through ensembling models based on their respective performance within each setup. Additionally, to pinpoint regions of interest harboring relevant biomarkers, we utilized Gradient-weighted Class Activation Mapping (GradCAM) for interpretability, with the aim of assisting experts in the identification process.

![alt text](image-14.png)

Following are the main contribution of our work:
- We introduce a two-stage training approach utilizing active learning to effectively leverage both labeled and unlabeled 
data.
- We assembled each model with the best outcome for each particular biomarker for an effective result handling each 
biomarker individually for increasing overall precision.
- Demonstrating how the application of active learning strategies, coupled with an efficient filtering system, to optimize 
the biomarker discovery process within a multi-label classification context.
- The integration of GradCAM provides a valuable contribution by offering insights into the model's decision-making 
process. This enhances the interpretability of the biomarker identification results, fostering a better understanding of 
the underlying biological significance.