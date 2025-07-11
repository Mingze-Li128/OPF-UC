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

## 4. Run OPf.ipynb
