+++
# Date this page was created.
date = 2019-05-10

weight = 1

# Project title.
title = "Image-to-image transformation learning"

# Project summary to display on homepage.
summary = "This is a project started long ago and still ongoing"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Deep Learning", "machine-learning"]


# Does the project detail page use math formatting?
math = false

+++

*Image transformation* is a common task in many image analysis and understanding projects. For instance, one may find Morphological Operators to be particularly well suited to process a specific family of images. However, finding the right parameters and composition of these operators may not a simple task. In other situations, one may have no clue about how to start.

In such scenarios, the task of transforming input images into desired output images can be formulated as a machine learning problem.

Previous reference works:

- [TRIOSLib][TRIOSLib]: a Python library with functions that help learning locally defined image transformations 
- The tutorial paper [Image Operator Learning and Applications][TRIOSpaper], by Igor S. Montagner, N. S. T. Hirata and R. Hirata 

[TRIOSLib]: https://trioslib.github.io/
[TRIOSpaper]: https://ieeexplore.ieee.org/document/7812925

Ongoing works:

- employing fully convolutional and other modern image-to-image networks