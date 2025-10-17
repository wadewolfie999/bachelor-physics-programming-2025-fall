# Bachelor's Programming Course for Physics Students - Fall 2025

## Overview
This repository contains exercises, solutions, and reproducible environments for a bachelor's-level programming course tailored to physics students. It covers Unix CLI, C, C++, Python, and culminates in projects using LaTeX and Git, emphasizing computational methods in physical contexts like simulations and data analysis.

## Learning Objectives
- Develop computational independence through foundational tools and languages.
- Apply programming to physics problems, bridging theory and implementation.
- Master reproducible workflows for scientific computing and documentation.

## Setup Instructions
1. **Clone the Repository**: `git clone https://github.com/wadewolfie999/bachelor-physics-programming-2025-fall.git`
2. **Install Environment**: Use Conda to create a reproducible setup:
```
conda env create -f environment.yml
conda activate physics-programming
```

This includes Python 3.x, GCC for C/C++, JupyterLab, LaTeX packages, and scientific libraries (e.g., NumPy, Matplotlib).
3. **Tools**: Install VS Code (code.visualstudio.com) or JupyterLab (jupyter.org/install) for coding.

## Weekly Structure
| Week | Topics | Resources | Activities |
|------|--------|-----------|------------|
| 1 | Introduction to Unix CLI | Tutorials on basic commands | CLI exercises in `week-1/exercises/` |
| 2 | VS Code/JupyterLab Setup; ChatGPT for CLI Assistance | Installation guides | Setup notebooks in `week-2/notebooks/` |
| 3-5 | C Programming (Think-C Chapters 1-9) | github.com/AllenDowney/ThinkC | Exercises and solutions in `week-3-5/` |
| 6-8 | C++ Programming (Think-C++ All Chapters minus 12 & 13) | github.com/AllenDowney/ThinkCPP | Code examples and tests in `week-6-8/` |
| 9-11 | Python Programming (Think-Python Chapters 1-17.3 minus 9 & 13) | allendowney.github.io/ThinkPython | Notebooks and scripts in `week-9-11/` |
| 12-14 | Projects, LaTeX, Git | XeLaTeX templates, Git workflows | Project templates in `week-12-14/`, submit via GitHub |

## Contribution Guidelines
- Students: Fork the repo, complete exercises, and submit PRs for review.
- Instructors: Solutions are in hidden branches; use GitHub Classroom for assignments.
- For issues, open a GitHub Issue with details.

## Reproducibility Notes
All code is tested via GitHub Actions (see `.github/workflows/`). Ensure your environment matches `environment.yml` for identical results.

Maintained by Vahid Gorgin, TA for Physics Programming Course.
