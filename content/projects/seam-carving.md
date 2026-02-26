+++
title = "Content-Aware Image Resizing (Seam Carving) in C"
date = 2025-05-15T00:00:00Z
tags = ["c", "seam carving", "dynamic programming", "image processing", "memory safety"]
+++

C application for content-aware image resizing based on the Seam Carving algorithm.

- Developed a Dynamic Programming solution to efficiently calculate total energy for all candidate seams, avoiding redundant computations.
- Carefully managed heap allocations and pointer arithmetic to achieve **100% memory safety**, validated using AddressSanitizer.
- Structured the code to separate energy calculation, seam search, and image manipulation, making the implementation easier to reason about and test.

