---
title: "Improved Computational Efficiency of Locally Low Rank MRI Reconstruction Using Iterative Random Patch Adjustments"
date: 2017-06-01
publishDate: 2020-01-15T07:43:10.136907Z
authors: ["A. Saucedo", "S. Lefkimmiatis", "N. Rangwala", "K. Sung"]
publication_types: ["2"]
abstract: "This paper presents and analyzes an alternative formulation of the locally low-rank (LLR) regularization framework for magnetic resonance image (MRI) reconstruction. Generally, LLR-based MRI reconstruction techniques operate by dividing the underlying image into a collection of matrices formed from image patches. Each of these matrices is assumed to have low rank due to the inherent correlations among the data, whether along the coil, temporal, or multi-contrast dimensions. The LLR regularization has been successful for various MRI applications, such as parallel imaging and accelerated quantitative parameter mapping. However, a major limitation of most conventional implementations of the LLR regularization is the use of multiple sets of overlapping patches. Although the use of overlapping patches leads to effective shift-invariance, it also results in high-computational load, which limits the practical utility of the LLR regularization for MRI. To circumvent this problem, alternative LLR-based algorithms instead shift a single set of non-overlapping patches at each iteration, thereby achieving shift-invariance and avoiding block artifacts. A novel contribution of this paper is to provide a mathematical framework and justification of LLR regularization with iterative random patch adjustments (LLR-IRPA). This method is compared with a state-of-the-art LLR regularization algorithm based on overlapping patches, and it is shown experimentally that results are similar but with the advantage of much reduced computational load. We also present theoretical results demonstrating the effective shift invariance of the LLR-IRPA approach, and we show reconstruction examples and comparisons in both retrospectively and prospectively undersampled MRI acquisitions, and in T1 parameter mapping."
featured: false
publication: "*IEEE Transactions on Medical Imaging*"
url_pdf: "https://ieeexplore.ieee.org/abstract/document/7835306"
doi: "10.1109/TMI.2017.2659742"
---

