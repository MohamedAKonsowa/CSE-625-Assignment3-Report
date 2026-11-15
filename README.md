# CSE 625 Assignment 3 report

IEEE conference paper for the finite-field determinant assignment.
The formatting follows the group report in [CSE-625-Group2](https://github.com/ntjohn04/CSE-625-Group2): `IEEEtran`, one section per file, and a GitHub Action that builds the PDF.

The cache measurements in `sections/05_results.tex` are from one Windows machine (AMD Ryzen 9 7900X, g++ 16.2, `-O3`).
The MPI break-even table is still empty.
The PowerPoint deck is not in this repo.

Pushing to any branch runs the LaTeX action and uploads `main.pdf`.
A tag named `v*` also attaches that PDF to a GitHub release.
