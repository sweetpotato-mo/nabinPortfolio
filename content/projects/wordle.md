+++
title = "Wordle & Quantum Wordle in C"
date = 2025-06-15T00:00:00Z
tags = ["c", "algorithms", "data structures", "wordle", "performance"]
+++

High-performance implementation of Wordle in C, including a dual-secret **“Quantum Wordle”** variant that maintains two possible solutions in parallel.

- Designed an O(k) feedback algorithm that avoids nested loops, enabling rapid evaluation of guesses even on larger dictionaries.
- Managed dynamic memory explicitly in C to keep the game responsive and avoid leaks, while keeping the core engine cleanly separated from I/O.

