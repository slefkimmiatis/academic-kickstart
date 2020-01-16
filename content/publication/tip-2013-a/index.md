---
title: "Hessian Schatten-Norm Regularization for Linear Inverse Problems"
date: 2013-05-01
publishDate: 2020-01-15T07:43:10.139213Z
authors: ["S. Lefkimmiatis", "J. P. Ward", "M. Unser"]
publication_types: ["2"]
abstract: "We introduce a novel family of invariant, convex, and non-quadratic functionals that we employ to derive regularized solutions of ill-posed linear inverse imaging problems. The proposed regularizers involve the Schatten norms of the Hessian matrix, which are computed at every pixel of the image. They can be viewed as second-order extensions of the popular total-variation (TV) semi-norm since they satisfy the same invariance properties. Meanwhile, by taking advantage of second-order derivatives, they avoid the staircase effect, a common artifact of TV-based reconstructions, and perform well for a wide range of applications. To solve the corresponding optimization problems, we propose an algorithm that is based on a primal-dual formulation. A fundamental ingredient of this algorithm is the projection of matrices onto Schatten norm balls of arbitrary radius. This operation is performed efficiently based on a direct link we provide between vector projections onto norm balls and matrix projections onto Schatten norm balls. Finally, we demonstrate the effectiveness of the proposed methods through experimental results on several inverse imaging problems with real and simulated data."
featured: true
publication: "*IEEE Transactions on Image Processing*"
url_pdf: "http://bigwww.epfl.ch/publications/lefkimmiatis1302.pdf"
url_code: "https://github.com/cig-skoltech/HessianRegularization"
doi: "10.1109/TIP.2013.2237919"
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

