## Package Management in R

---

## Ok, what are packages?

A package is a collection of code you can use.

In R, most public packages live in the CRAN repository.

Packages are installed with a package manager.

R comes with a built-in package manager.

---

## Packages in R

R's default package manager installs all packages _globally_ on your computer. This makes working in teams difficult:

* What if you have a different version of some library than I do?
* What if I want one version of xyz-package for one project, and a different version for another?
* If I upgrade xyz-package to use the latest features in one project, will my old project stop working?

---

## Reproducible Environments

Some solutions:

* Use Docker (containerized environments, for example, with Jupyter Notebooks).
* Use Packrat/Jetpack (R libraries for reproducible environments).

---
