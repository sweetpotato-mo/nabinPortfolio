+++
title = "Edge Detection Image Processing in C"
date = 2024-05-15T00:00:00Z
tags = ["c", "image processing", "convolution", "gradients"]
+++

Command-line application in C for content-aware edge detection on grayscale images using convolution-based filters.

- Implemented a multi-stage pipeline including image blurring, discrete derivatives in the x and y directions, and gradient magnitude computation.
- Worked with the PGM (Portable Graymap) image format and explicit file I/O using the C standard library.
- Structured the program into clear stages so that each step (load, filter, detect edges, write output) can be tested and reasoned about independently.

