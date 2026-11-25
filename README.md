# SCOLIOVENGE 🦴
### Computer Vision-Based Scoliosis Analysis

> Exploring automated spinal curvature analysis using medical image processing and computer vision.

## About

Scoliosis is a condition characterized by an abnormal sideways curvature of the spine, often accompanied by vertebral rotation. It is commonly assessed using spinal X-rays and measurements such as the Cobb angle.

**SCOLIOVENGE** is an ongoing computer vision project focused on exploring how spinal X-ray images can be processed and analysed computationally.

The goal is to develop a system that can identify spinal structures, estimate curvature and visualise relevant anatomical measurements.

## Objectives

- Spinal X-ray preprocessing and enhancement.
- Vertebral detection and segmentation.
- Anatomical landmark localization.
- Automated Cobb angle estimation.
- Spinal curvature visualisation.
- Evaluation against reference annotations and measurements.

## Proposed Workflow

```text
Spinal X-ray Input
       ↓
Image Preprocessing
       ↓
Vertebral Detection
       ↓
Vertebral Segmentation
       ↓
Landmark Localization
       ↓
Cobb Angle Estimation
       ↓
Visualisation & Evaluation
```

## Tech Stack

*Proposed technologies — subject to experimentation.*

- **Language:** Python
- **Image Processing:** OpenCV, NumPy
- **Deep Learning:** PyTorch
- **Computer Vision:** CNNs, segmentation models
- **Visualisation:** Matplotlib

## Development Roadmap

- [ ] Literature review and problem understanding
- [ ] Dataset exploration and preprocessing
- [ ] Baseline vertebral detection
- [ ] Vertebral segmentation
- [ ] Anatomical landmark detection
- [ ] Cobb angle estimation
- [ ] Visualisation and evaluation
- [ ] Model refinement and experimentation

## Research Direction

The project will explore existing approaches, identify their limitations and investigate potential improvements in automated spinal image analysis.

All algorithms and measurements will be evaluated against appropriate reference annotations wherever available.

## Build in Public

I'm documenting the development journey, including research papers, implementation decisions, experiments, challenges and learnings.

Follow along as SCOLIOVENGE evolves from an idea into a working computer vision system.

## Disclaimer

SCOLIOVENGE is an experimental research and educational project. It is not a clinically validated diagnostic tool and is not intended to replace professional medical assessment.

---

**Status:** <code>Early Development · Day 1</code>

**Author:** Anjali

*Making spinal curvature analysis computational.*
