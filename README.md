<div align="center">

# Image-based 3D Object Reconstruction: State-of-the-Art and Trends in the Deep Learning era

[Xianfeng Han](https://scholar.google.com/citations?user=4FaCTFgAAAAJ&hl=en) · [Hamid Laga](https://sites.google.com/view/hamidlaga) · [Mohammed Bennamoun](https://research-repository.uwa.edu.au/en/persons/mohammed-bennamoun) 

### [Paper](https://ieeexplore.ieee.org/abstract/document/8908779) | [Abstract](#abstract) | [Cittaion](#citation) | [Chronological Overview](#overview) | [Updates](#updates)  | [Contributors](#contributors)

</div>


## Abstract

3D reconstruction is a longstanding ill-posed problem, which has been explored for decades by the computer vision, computer graphics, and machine learning communities. Since 2015, image-based 3D reconstruction using convolutional neural networks (CNN) has attracted increasing interest and demonstrated an impressive performance. Given this new era of rapid evolution, this article provides a comprehensive survey of the recent developments in this field. We focus on the works which use deep learning techniques to estimate the 3D shape of generic objects either from a single or multiple RGB images. We organize the literature based on the shape representations, the network architectures, and the training mechanisms they use. While this survey is intended for methods which reconstruct generic objects, we also review some of the recent works which focus on specific object classes such as human body shapes and faces. We provide an analysis and comparison of the performance of some key papers, summarize some of the open problems in this field, and discuss promising directions for future research.

This repository will be continuously maintained. Please feel free to create issues if you have any suggestions!

```
Organization of the Survey
├── Introduction
├── Problem Statement and Taxonomy
├── The Encoding Stage
│   ├── Discrete Latent Spaces
│   ├── Continuous Latent Spaces
│   ├── Hierarchical Latent Spaces
│   └── Desentangled Representation
├── Volumetric Decoding
│   ├── Volumetric Representations of 3D Shapes
│   ├── Low Resolution 3D Volume Reconstruction
│   ├── High Resolution 3D Volume Reconstruction
│   │   ├── Space Partitioning
│   │   ├── Occupancy Networks
│   │   ├── Shape Partioning
│   │   ├── Subspace Parameterization
│   │   └── Coarse-to-fine Refinement
│   └── Deep  Marching Cubes
├── 3D Surface Decoding
│   ├──  Parameterization-Based 3D Reconstruction
│   ├──  Deformation-Based 3D Reconstruction
│   │   ├── Deformation Models
│   │   ├── Defining the Template
│   │   └── network Architectures
│   ├──Point-Based Techniques
│   │   ├──  Representations
│   │   └──  network Architectures
├── Leveraging Other Cues
│   ├──  Intermediating
│   └──  Exploitng Spatio-Temporal Correlations
├── Training
│   ├──  Degree of Supervision
│   │   ├── Training with 3D Supervision
│   │   └── Training with 2D Supervision
│   ├──  Training with video Supervision
│   ├──  Training Procedure
│   │   ├── Joint 2D-3D Embedding
│   │   ├── Adversarial Training
│   │   └── Joint Training with other Tasks
├── Applications and Special Cases
│   ├──  3D Human Reconstruction
│   │   ├── Parametric Methods
│   │   ├── Volumetric Methods
│   ├──  3D Face Reconstruction
│   │   ├── Network Architectures
│   │   ├── Training and Supervision
│   │   ├── Model-Free Approaches
│   └──  3D Scene Parsing
├── Datasets
├── Performance Comparison
│   ├──  Accuracy Metrics and Performance Criteria
│   │   ├── Accuracy Metrics
│   │   ├── Performance Criteria
│   └──  Comparison and Discussion
└── Conclusion and Future Directions
```

## Citation

If our survey helps in your research, please consider citing the following paper:

    @article{han2019image,
        title={Image-based 3D object reconstruction: State-of-the-art and trends in the deep learning era},
        author={Han, Xian-Feng and Laga, Hamid and Bennamoun, Mohammed},
        journal={IEEE transactions on pattern analysis and machine intelligence},
        volume={43},
        number={5},
        pages={1578--1604},
        year={2019},
        publisher={IEEE}
    }
    <p align="center"> <img src="./assets/datasets.png" width="95%"> </p>

## Overview

### Chronological Overview

Coming soon ....

## Updates
We are currently collecting the papers that appeared between 2020 and 2022. Stay tuned ...

## Contributors

-- [Hamid Laga](https://sites.google.com/view/hamidlaga)
-- [Xianfeng Han](https://scholar.google.com/citations?user=4FaCTFgAAAAJ&hl=en)
-- [Mohammed Bennamoun](https://research-repository.uwa.edu.au/en/persons/mohammed-bennamoun) 


