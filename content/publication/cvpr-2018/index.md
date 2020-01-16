---
title: "Universal Denoising Networks : A Novel CNN Architecture for Image Denoising"
date: 2018-06-01
publishDate: 2020-01-15T07:43:10.141533Z
authors: ["S. Lefkimmiatis"]
publication_types: ["1"]
abstract: "We design a novel network architecture for learning discriminative image models that are employed to efficiently tackle the problem of grayscale and color image denoising. Based on the proposed architecture, we introduce two different variants. The first network involves convolutional layers as a core component, while the second one relies instead on non-local filtering layers and thus it is able to exploit the inherent non-local self-similarity property of natural images. As opposed to most of the existing deep network approaches, which require the training of a specific model for each considered noise level, the proposed models are able to handle a wide range of noise levels using a single set of learned parameters, while they are very robust when the noise degrading the latent image does not match the statistics of the noise used during training. The latter argument is supported by results that we report on publicly available images corrupted by unknown noise and which we compare against solutions obtained by competing methods. At the same time the introduced networks achieve excellent results under additive white Gaussian noise (AWGN), which are comparable to those of the current state-of-the-art network, while they depend on a more shallow architecture with the number of trained parameters being one order of magnitude smaller. These properties make the proposed networks ideal candidates to serve as sub-solvers on restoration methods that deal with general inverse imaging problems such as deblurring, demosaicking, superresolution, etc."
featured: true
publication: "*The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*"
url_pdf: "http://openaccess.thecvf.com/content_cvpr_2018/papers/Lefkimmiatis_Universal_Denoising_Networks_CVPR_2018_paper.pdf"
url_code: "https://github.com/slefkimmiatis/UDNet"
links:
- name: Supp
  url: "http://openaccess.thecvf.com/content_cvpr_2018/Supplemental/0512-supp.pdf"
# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  placement: 1
  focal_point: "Center"
  preview_only: false
---

