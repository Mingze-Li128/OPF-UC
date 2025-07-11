# Optimal Power Flow (OPF) using Julia

This project demonstrates the solution of the Optimal Power Flow (OPF) problem using Julia, with the `JuMP`, `Gurobi`, and `Ipopt` packages. The OPF problem is solved using the case study data from the MATPOWER dataset (e.g., `case14.mat`).

## 1. Download the Dataset

First, download the MATPOWER dataset, such as the `case14.mat` file. You can download it from the [MATPOWER website](https://matpower.org/) or use the example provided here.

## 2. Install Julia

If you don't have Julia installed, follow these steps:

- Go to the [official Julia website](https://julialang.org/downloads/).
- Download the latest stable version of Julia for your operating system.
- Follow the installation instructions for your OS.

## 3. Install Required Julia Packages

You need necessary packages to solve the OPF problem. To install these packages, open a Julia REPL and run the following commands:

```julia
using Pkg
Pkg.add("JuMP")
Pkg.add("Gurobi")
Pkg.add("Ipopt")
```

## 4. Run OPF.ipynb

# Unit Commitment using Gurobi

This project demonstrates solving the Unit Commitment (UC) problem using Python and the Gurobi solver. The problem is solved with the `gurobipy` package and is modeled in the `UCTBM_gurobi.ipynb` Jupyter notebook.

## 1. Install Python 3.10+

Make sure you have Python 3.10 or later installed. To install Python, follow these steps:

- Go to the [official Python website](https://www.python.org/downloads/).
- Download and install Python 3.10 or later for your operating system.
- Follow the installation instructions for your OS.

## 2. Install the `gurobipy` Package

You need to install the `gurobipy` package to solve the Unit Commitment problem. To install it, follow these steps:

1. **Install the Gurobi solver:**
   - Go to the [Gurobi website](https://www.gurobi.com/) and follow the installation instructions.
   - Make sure you have a valid Gurobi license.

2. **Install `gurobipy` package using pip:**

   Open a terminal or command prompt and run the following command:

   ```bash
   pip install gurobipy
   ```

## 3. Run UCTBM_gurobi.ipynb
