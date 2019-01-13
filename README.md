#  Mathematical Optimization using JuMP (MIT 18.337/6.338, Fall 2018)


This site contains materials for my guest lecture at [MIT 18.337/6.338, Modern Numerical Computing](http://courses.csail.mit.edu/18.337/2018/) in Fall 2018. 

## Installation Instructions 

You should use the latest version of Julia v1.0. Binaries of Julia for all platforms are available [here](http://julialang.org/downloads/).

You can download the materials by running
```
git clone https://github.com/juan-pablo-vielma/18.337-6.338-2018
```
or downloading [this zip file](https://github.comjuan-pablo-vielma/18.337-6.338-2018/archive/master.zip).

Finally, you can install [Jupyter](http://jupyter.org/) and its Julia backend [IJulia](https://github.com/JuliaLang/IJulia.jl) by running the following code in the Julia REPL.
```julia
import Pkg
Pkg.add("IJulia")
```

Each notebook includes a cell with the commands
```julia
import Pkg
Pkg.activate(@__DIR__)
Pkg.instantiate()
```
that will install all required packages described by the `Project.toml` and  `Manifest.toml` files in the corresponding folder. 	

The [polynomial optimization example](https://github.com/juan-pablo-vielma/18.337-6.338-2018/blob/master/Polynomial%20Optimization%20with%20JuMP%200.18/Polynomial.ipynb) requires having [Gurobi](http://www.gurobi.com/) and a [Mosek](https://www.mosek.com) license already installed. You can download Gurobi from its [download page](http://www.gurobi.com/downloads/gurobi-optimizer) and you can get an academic license for it by registering with your MIT email [here](http://www.gurobi.com/academia/for-universities). You can get an academic license for [Mosek](https://www.mosek.com) using this [form](https://license.mosek.com/academic/).

## More resources


The polynomial optimal control example was developed by [Joey Huchette](http://www.mit.edu/~huchette/) for the 2017 SIAM Conference on Optimization. For more details on this problem you can find Joey's SIAM Opt slides  [here](https://docs.google.com/presentation/d/1ASfjB1TdLJmYxT0b6rnyGh9eLbMc-66bTOt3_3yvc90/edit?usp=sharing).

