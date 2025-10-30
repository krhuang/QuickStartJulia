# QuickStartJulia
Repository for the talk "Julia for the working Mathematician"

# Install Julia via juliaup
In Mac/Linux execute
```
curl -fsSL https://install.julialang.org | sh
```
and follow the installer instructions. You can set download locations by setting the environmental variables `JULIA_DEPOT_PATH` and `JULIAUP_DEPOT_PATH`.

In Windows execute
```
winget install --name Julia --id 9NJNWW8PVKMN -e -s msstore
```

# (Optional) Install IJulia to interface Julia and Jupyter notebooks
First install Jupyter Notebook via 
```
pipx install jupyterlab
```
and then, in a `julia` terminal, execute
```
using Pkg
Pkg.add("IJulia")
```
