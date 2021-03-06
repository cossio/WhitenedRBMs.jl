# WhitenedRBMs Julia package

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/cossio/WhitenedRBMs.jl/blob/master/LICENSE.md)
[![](https://img.shields.io/badge/docs-dev-blue.svg)](https://cossio.github.io/WhitenedRBMs.jl/dev)
![](https://github.com/cossio/WhitenedRBMs.jl/workflows/CI/badge.svg)
[![codecov](https://codecov.io/gh/cossio/WhitenedRBMs.jl/branch/master/graph/badge.svg?token=90I3AJIZIG)](https://codecov.io/gh/cossio/WhitenedRBMs.jl)
![GitHub repo size](https://img.shields.io/github/repo-size/cossio/WhitenedRBMs.jl)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/cossio/WhitenedRBMs.jl)

Train and sample whitned [Restricted Boltzmann machines](https://en.wikipedia.org/wiki/Restricted_Boltzmann_machine) in Julia.

## Installation

This package is not registered.
Install with:

```julia
using Pkg
Pkg.add(url="https://github.com/cossio/WhitenedRBMs.jl")
```

This package does not export any symbols.

## Related

Builds upon the [RestrictedBoltzmannMachines](https://github.com/cossio/RestrictedBoltzmannMachines.jl) Julia package, which defines the `RBM` and layer types.