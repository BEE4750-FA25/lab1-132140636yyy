# Homework 1: Introduction to Using Julia

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the repository for Homework 1 for [BEE 4750](https://viveks.me/environmental-data-analysis), taught at [Cornell University](https://cornell.edu) in Fall 2025 by [Vivek Srikrishnan](https://viveks.me).

If enrolled in the class, a PDF of the solution should be submitted to Gradescope *no later* than the due date at 9:00pm. Submitting up to 24 hours late will result in a 50% penalty.

## Learning Objectives

After completing this lab, students will be able to:

- apply basic strategies of code debugging;
- interpret code snippets;
- use your knowledge of Julia to fix code errors;
- write a basic Julia function to represent system outcomes.

## Repository Overview

The repository consists of the following files:

- `hw01.ipynb`: Jupyter Notebook for the homework assignment. Students should create code or Markdown blocks as necessary to answer questions. **This is the only file you should need to edit.**
- `Project.toml`, `Manifest.toml`: Julia environment files. These should just work, but feel free to add other packages as needed using the `Pkg` package manager. **This is the only other file that you might end up making changes to, though you should do this using `Pkg`, not directly.**
- `hw01.qmd`: Source file for Jupyter notebook generation. You shouldn't need to or want to touch this; everything is in the `.ipynb` file.
- `LICENSE`: This material is licensed using the MIT license. You can ignore this for working on the problem set.
- `README.md`: This file. You shouldn't need to touch this.
- `.gitignore`: This tells `git` what files to ignore. You shouldn't need to touch this.
- `.github/`: This folder contains a GitHub Action workflow to automatically render a committed and pushed notebook to a PDF. You don't need to touch this.

## Dependencies

This notebook was written using Julia 1.11.5, and depends on the following packages:

- `Plots.jl` (basic plotting library)
- `GraphRecipes.jl` (make graphical plots for Problem 4)
- `LaTeXStrings.jl` (use LaTeX for mathematical markdown in Plots)
- `Distributions.jl` (interface for working with probability distributions)

## Prerequisites

1. [Install Julia](https://julialang.org/downloads/) before beginning this lab. This notebook was developed with version 1.11.5, but any 1.11.x should work (there could be some issues with other versions, depending on what's changed; if that occurs, delete `Manifest.toml` before re-evaluating the first notebook cell). 
2. If necessary, [install git](https://happygitwithr.com/install-git.html) and [create a GitHub account](https://github.com). 