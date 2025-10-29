# QuickStartJulia
Repository for the talk "Julia for the working Mathematician"

# Install Julia via juliaup
In Mac/Linux execute
```
curl -fsSL https://install.julialang.org | sh
```
and follow the installer instructions.

In Windows execute
```
winget install --name Julia --id 9NJNWW8PVKMN -e -s msstore
```

# (Optional) Install IJulia to interface Julia and Jupyter notebooks
First install Jupyter Notebook via 
```
pip install jupyterlab
```
and then, in a `julia` terminal, execute
```
using Pkg
Pkg.add("IJulia")
```