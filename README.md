# Bokeh tutorial notebooks

## Setup and run the tutorials

Follow these steps to run the tutorial notebooks on your local machine:

1. Start by **cloning** this repository to your local machine.
    For example:

    ```bash
    git clone git@github.com:bokeh/tutorial.git
    ```

2. After cloning the repository, **enter the folder** that contains the repository contents:

    ```bash
    cd tutorial
    ```

3. Next, you need to **set up your environment**. This tutorial uses the `conda` package
    manager.
    Please make sure
    [conda or Miniconda are installed and configured correctly](https://docs.conda.io/projects/conda/en/stable/)
    on your system.

    Run the following command inside your local repository folder to create your environment:

    ```bash
    conda env create -f environment.yml
    ```

4. After the environment is set up, **activate** it with the following command:

    ```bash
    conda activate bk-tutorial
    ```

5. From inside the  ``bk-tutorial`` environment, you can now **start the Jupyter
    notebook server**:

    ```bash
    jupyter notebook
    ```

6. After opening Jupyter notebooks in a browser, go to the folder `notebooks`.
    **Open the first notebook in this folder**. It is called
    `01_introduction.ipynb`.

## Contributing to this tutorial

Thank you for helping to make this tutorial a better resource for everyone!

Everyone active in the Bokeh project’s codebases, issue trackers, and discussion forums
is expected to follow the
[Code of Conduct](https://github.com/bokeh/bokeh/blob/main/docs/CODE_OF_CONDUCT.md).
This includes working on these tutorials!

### Preparing your environment

The ``bk-tutorial`` environment includes the necessary dependencies to contribute to this repository.

For consistency, we ask that you generally follow the
[Black code style](https://black.readthedocs.io/en/stable/the_black_code_style/current_style.html)
wherever possible.

### Making changes

Contributing to this tutorial repository works similarly to
[contributing to Bokeh itself](https://docs.bokeh.org/en/latest/docs/dev_guide.html):

1. Open an issue in the [issue tracker of this repository](https://github.com/bokeh/tutorial/issues)
2. Make PR and link it to the issue you created

Once you have created a pull request, a member of the Bokeh core team will begin reviewing your pull request and may request changes or additions. If so, they will help you along the way with any questions you may have.

## Previous presentations

* SciPy 2024: [Material](https://github.com/bokeh/tutorial/releases/tag/SciPy2024)
* SciPy 2023: [Video](https://youtu.be/G0Yc3ck4lC8?si=ZGqatTPnZBwjtdXO), [Material](https://github.com/bokeh/tutorial/releases/tag/SciPy2023)
