# example_Effort

This repo contains an example on how to use the `Effort.jl` emulator to analyze Power Spectra measurement with the EFTofLSS.

In order to use you have to:

- install `julia` (if needed, [here](https://www.marcobonici.com/blog/julia-tricks/#installing_julia) are some instructions)
- create a jupyter kernel (if needed, [here](https://www.marcobonici.com/blog/julia-tricks/#installing_julia_kernel_on_jupyter) are some instructions explicitely showing how to create a kernel which has access to multiple threads)
- download all the required packages

In order to perform the last step, enter `notebook` folder from the terminal, start `julia` then type

```julia
]#this will put you in the environment manager
activate . #this will activate the local environment
instantiate #this will download and install all the packages specified in the Manifest file
```
