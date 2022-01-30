# ext-math
A PHP extension providing comprehensive mathematics support.

# Introduction
At the moment, this repository is acting as a place to put research and planned scope/design.

# Planned Features

- Core Principles:
  - Seemless and performant transition between standard precision and arbitrary precision to allow replacement of scalars without significant increases in RAM/CPU usage unless high precision is being actively used.
  - Portability of types, regardless of base or precision, across different operations and features within the extension
  - Extended math features currently not available in PHP
  - Should have full operator overload support for all types provided to again act as full replacements for scalars
- Type System:
  - Decimals
    - Reals
    - Imaginary
    - Multiple Bases
  - Fractions
    - Reals
    - Imaginary
    - Multiple Bases
  - Complex
    - Composed of Decimals/Fractions
  - Matrices
    - Composed of Decimals/Fractions/Complex
  - Tuples
- Operations/Domains:
  - Arithmetic
  - Bitwise Arithmetic
  - Trigonometry
  - Statistics
    - Including things such as erf() and inverse erf()
    - At a minimum support for gaussian normal distributions, exponential distributions, and poisson distributions
  - RNG (non-cryptographic & cryptographic)
  - Rounding
  - Calculus (where analytical solutions are possible)
  - Grid/Graph/Coordinate systems
    - Including pathfinding algorithms
  - Combinatorics/Permutations

# Possible Libraries/Utilities

- FLINT + Arb
- MPDecimal
