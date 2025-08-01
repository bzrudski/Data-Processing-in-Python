# Data Processing in Python (Part 2)

**Click one of these:**
[![Open student version in Colab](https://img.shields.io/badge/Open%20in%20Colab-Student%20version-blue?logo=googlecolab)](https://colab.research.google.com/github/bzrudski/Data-Processing-in-Python/blob/main/Exercises/scripts/DataProcessingPython.ipynb)
[![Open solutions version in Colab](https://img.shields.io/badge/Open%20in%20Colab-Solutions%20version-blue?logo=googlecolab)](https://colab.research.google.com/github/bzrudski/Data-Processing-in-Python/blob/main/Exercises/solutions/DataProcessingPython.ipynb)

## Overview

In this 4-hour workshop, students will learn basic data processing skills using Python. Attendees will learn how to import code from other modules and packages to take advantage of the existing Python ecosystem. After seeing how to access packages, we will explore popular data analysis packages. We will see how to use NumPy to perform operations on large data arrays and how to use Matplotlib to generate clear data visualisations. We will also scratch the surface on using pandas to store data in tables. Along the way, we will discuss how to approach new, unfamiliar packages and learn how to use them.

## Learning Objectives

By the end of this workshop, you should be able to:

1. Import code from existing modules and packages.
2. Use NumPy to easily process multidimensional data.
3. Use Matplotlib to generate different types of plots to visualise data.
4. Use pandas to represent data stored in tables.
5. Approach a new package and explore its documentation and examples.

## Prerequisites

* Basic knowledge of Python is required.
* Attendees must be comfortable using variables for simple data types,
  as well as collections. Attendees should also be comfortable with
  loops and control flow and be familiar with the basics of using
  functions in Python.
* To be able to participate in the exercises, participants must either:
  * Have a local installation of Python and Jupyter notebooks.
     Microsoft Visual Studio Code with the Python extension installed
     can also be used to run the Notebook.
  * Have a Google Account (to run in-browser as a Colab notebook)

## Setup Information

This workshop is intended to be interactive. Before the workshop, please download the materials from this repository. You can download the material as a ZIP file using the green button higher up on this page, or you can simply clone this repository by typing the following in a terminal:

```shell
git clone https://github.com/bzrudski/Data-Processing-in-Python.git
```

### Requirements

To take full advantage of this interactive workshop, you must have access to a Python environment and Jupyter Lab.

You must also install the following packages:

* NumPy
* Matplotlib
* pandas

#### Local

The required steps depend on how you installed Python:

* **(Recommended)** If you installed **minconda**, you can easily install all these packages by running the following on the command line:

```shell
conda install -c conda-forge jupyterlab numpy matplotlib pandas -y
```

* If you installed Python from the official website, you can easily install Jupyter using `pip` by running the following on the command line:

```shell
pip install jupyterlab numpy matplotlib pandas
```

* If you installed **Anaconda**, you already have everything you need installed.

For more details on installing Jupyter Lab, see <https://jupyter.org/install>.

Once you have Jupyter installed, open the `Data-Processing-in-Python` folder on your computer and launch Jupyter Lab by typing:

```shell
jupyter lab
```

Then you can open the Jupyter notebook files in the `Exercises/scripts` and `Exercises/solutions` folders.

#### Cloud

If you don't want to install anything locally, you can open the workshop materials using Google Colab:

* Student version (with blank fields): <https://colab.research.google.com/github/bzrudski/Data-Processing-in-Python/blob/main/Exercises/scripts/DataProcessingPython.ipynb>
* Solution version (filled out): <https://colab.research.google.com/github/bzrudski/Data-Processing-in-Python/blob/main/Exercises/solutions/DataProcessingPython.ipynb>

> &#x26A0; **Warning:** To configure for Google Colab, make sure to set `using_colab = True` in the first code cell and run that cell to download all the data files.

## Outline

*For a more detailed outline, see [Outline/Outline.md](Outline/Outline.md).*

1. **Module 1 -- Modules and Packages**
2. **Module 2 -- Introduction to NumPy Arrays**
3. **Module 3 -- Visualising Data with Matplotlib**
4. **Module 4 -- Intro to Tabular Data with Pandas**
5. **Module 5 -- A Brief Guide to Exploring the Unknown**

## References

This workshop is based on my previous iterations of this workshop (as **Intermediate Python**) and my **Intro to Python** workshop, which can be found at the following repositories:

* Intro to Python:
  * [Winter 2025](https://github.com/bzrudski/Intro-to-Python)
  * [Fall 2024](https://github.com/bzrudski/micm_intro_to_python_fall_2024)
  * [Summer 2024](https://github.com/bzrudski/micm_intro_to_python_summer_2024)
  * [Winter 2024](https://github.com/bzrudski/micm_intro_to_python_winter_2024)
  * [Summer 2023](https://github.com/bzrudski/micm_intro_to_python_summer_2023)
  * [Fall 2022](https://github.com/bzrudski/micm_intro_to_python_fall_2022)
* Intermediate Python:
  * [Fall 2024](https://github.com/bzrudski/micm_intermediate_python_fall_2024)
  * [Summer 2024](https://github.com/bzrudski/micm_intermediate_python_summer_2024)
  * [Fall 2023](https://github.com/bzrudski/micm_intermediate_python_fall_2023)

Colab badge created using <https://shields.io>.

Some cool Markdown tricks can be found at <https://www.markdownguide.org/hacks/>.

---

*Workshop created as part of the McGill Initiative in Computational Medicine*.

For more information about the QLS-MiCM, visit: <https://www.mcgill.ca/micm/>.

The contents of this repository are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

[![CC-BY-SA](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
