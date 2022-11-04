# Python course materials

This is a [Jupyter Book][jb] that serves as the course materials for the
[Centre for Digital Scholarship][cds]'s courses *Introduction to programming
with Python* and *Data analysis with Python*.

During the course, students are asked to run the code in the tutorial notebooks
and practice their understanding through exercises.
Solutions to the exercises are included in separate notebooks.

The tutorial notebooks and solutions are converted and published as the
[course website][web].

[jb]: https://jupyterbook.org/
[cds]: https://www.library.universiteitleiden.nl/about-us/centre-for-digital-scholarship
[web]: https://cdsleiden.github.io/python-tutorial/

## Installation

To install the dependencies for this book, or the notebooks, you need Python
3.7 or newer.
Clone the repository and `cd` into the repository directory.
Then you can install the dependencies.

```sh
pip install -r requirements.txt
```

It is recommended to create a virtual environment for this.

## Building the book

To build the HTML version of the book, run:

```sh
jupyter-book build .
```

## Contributing

Contributions to improve the materials are welcome in the form of issues and
pull requests.

Each merged pull request will update the website and create a release that
includes a zipfile containing the original notebooks for students to use.
