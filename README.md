# Vision-Language Models for Enhanced Object Dection in Rural Autonomous Driving Applications
## Overview
This research project explores the feasibility of Vision-Language Models (VLMs) as an alternative to
conventional object detectors for autonomous driving in rural environments. It addresses the lack of
research in rural object detection and VLM applications, aiming to bridge these literature gaps. The
study modifies a rural autonomous driving dataset and evaluates Faster R-CNN, RetinaNet, and SEEM
models for 2D object detection. The results reveal that both Faster R-CNN and SEEM outperform
RetinaNet, with SEEM showing potential improvements when incorporating textual information. The
impact of object size and IoU threshold on model accuracy is highlighted, and class-specific variations
in mean Average Precision (mAP) values are explored. Despite dataset limitations, the research
contributes valuable insights to the field of rural autonomous driving object detection and highlights
the promise of VLMs in this context. Future work includes addressing dataset imbalances and label
errors for more reliable model evaluation and deployment in rural settings, enhancing object detection
systems for rural autonomous driving.

## Model Accuracy

## Detection Errors

## Limitations
There are several limitations in the projects study that must be considered when interpreting the
results. The limitations of the rural dataset introduce constraints on the conclusions that can be drawn
regarding model performance. The dataset exhibits class imbalance, with certain object classes being
underrepresented compared to others. This imbalance may skew the evaluation metrics, potentially
giving an inaccurate representation of the true models’ ability. Additionally, the presence of label
errors within the dataset further complicates the evaluation of model performance. These errors lead
to misannotated objects, affecting the training and evaluation process. Another limitation, is the
region which the rural dataset was gathered. As rural environments can vary greatly across different
regions and countries, the findings may not generalise well to other rural settings globally. Factors
such as road infrastructure, vehicle types, and traffic patterns may differ, potentially affecting the
models’ ability to adapt to a more diverse rural road scene
