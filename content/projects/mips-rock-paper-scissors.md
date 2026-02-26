+++
title = "MIPS Assembly Rock-Paper-Scissors"
date = 2024-05-15T00:00:00Z
tags = ["mips", "assembly", "systems programming", "randomness"]
+++

Specialized Rock-Paper-Scissors implementation in MIPS Assembly, where the computer plays against itself using pseudo-randomly generated moves.

- Implemented subroutines such as `gen_bit` and `gen_byte` to produce uniformly distributed game moves using MIPS system calls.
- Adhered strictly to MIPS calling conventions and used the MARS simulator to debug and reason about low-level state.
- Verified correctness via automated Python testing scripts, ensuring that randomization and game logic behaved as expected.

