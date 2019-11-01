# TP-CIRM

You will find here the files for the practical session of the Interface course 
*Stochastic Optimization for Large-Scale Systems*


## The practical work

You can download the files from this repository (use the green button on the top right)
and run them from the jupyter notebooks ([Help for IJulia](https://github.com/JuliaLang/IJulia.jl)). 
Installation instruction are given at the end of this description.

#### First practical session (Monday afternoon)
- JuMPCrashcourse (very simple tutoriel to start working with notebooks, julia and JuMP)
- Newsvendor is the first practical work

#### Second practical session (Tuesday Morning)
- flower-girl question 1 and 2

#### Third practical session (Tuesday Afternoon)
- flower-girl question 4 and 5

#### Fourth practical session (Thursday Morning)
- SDDP

## Installing Julia

### Linux

You can either install Julia from your package manager or
1. [Download the code](https://julialang.org/downloads/index.html)
2. Unzip the files somewhere
3. Make a symbolic link e.g. `sudo ln -s ~/julia/julia-1.2.0-linux-x86_64/julia-1.2.0/bin/julia /usr/local/bin/julia` (Warning : adress should be absolute, not relative)

You can now run julia from the terminal simply calling `julia`

Then you need to install some package from the julia prompt
1. enter `]`
2. `add IJulia JuMP GLPK`
3. `precompile`
4. `build IJulia`
5. `Ctrl - C`
6. `using IJulia`
7. `notebook(detached=true)`

### Windows 

1. [Download the code](https://julialang.org/downloads/index.html)
2. double click and follow instructions
3. launch julia and enter `]`
4. `update`
5. `add IJulia JuMP GLPK`
6. `precompile`
7. `build IJulia` 
8. `Ctrl - C`
9. `using IJulia`
10. `notebook(detached=true)`


