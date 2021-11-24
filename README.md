# DomDecOTExamples.jl
Examples for the library DomDecOT.jl. You can inspect the `.html` generated from these notebooks in the same repo. Alternatively, you can run them online or locally.

## Running the examples online

Run them in `Binder` by clicking below. Allow some moments for the environment setup and compilation.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ismedina/DomDecOTExamples.jl/HEAD)

## Running the examples locally

Clone the repo and run them. The first line on each notebook should activate a reproducible environment and install all the needed packages.

For testing the parallel implementation you may want to start Julia with more than 1 thread. Probably the easiest way to do so is to create a new jupyter kernelspec: 

```julia-repl
using IJulia
IJulia.installkernel("Julia 6 Threads", env=Dict(
    "JULIA_NUM_THREADS" => "6",
))
```

(as explained in https://github.com/JuliaLang/IJulia.jl/issues/882#issuecomment-579520246)