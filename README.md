# OpenMIGS
Official code implemention for "OpenMIGS: Multi-granularity Information-preserving Open-Vocabulary 3D Gaussian Splatting".

# Abstract
Open-vocabulary scene understanding is critical for robotics, yet existing 3D Gaussian Splatting (3DGS) methods rely on compressed feature embeddings, compromising semantic fidelity and fine-grained interpretation. Although utilizing uncompressed high-dimensional features offers a potential solution, their direct integration imposes prohibitive memory and computational costs. To address this challenge, we propose OpenMIGS, a novel 3DGS-based framework for multi-granularity, information-preserving open-vocabulary understanding across both object and part levels. Specifically, OpenMIGS first constructs object-level Gaussian fields as structured carriers where a two-stage clustering strategy ensures global consistency in object labeling, and a codebook subsequently associates these object label with their uncompressed high-dimensional features. Building on this, a lightweight implicit field processes the geometric coordinates of object Gaussians to regress part-level high-dimensional features, enabling multi-granularity understanding. Experimental results on multiple datasets show that OpenMIGS outperforms existing methods in open-vocabulary understanding and retrieval tasks. It also supports multi-granularity scene editing for flexible semantic manipulation.

# Overview
The overview of OpenMIGS goes as follows:


# Code for installation
The full implementation of LCP-Fusion is coming soon !!!
