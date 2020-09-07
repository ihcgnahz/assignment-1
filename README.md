# Assignment #1 (Required)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-550-Fall-2020/assignment-1/master)

### Note

If you are unable to successfully install Python locally in Part 1 of this
assignment, you can also use the Binder link above to proceed with step 2. After
loading Binder, a new Jupyter notebook can be created to complete Part 2.

If this is the case, please make a note in your submitted Jupyter notebook that
you still having trouble setting up Anaconda locally and we can work to resolve
it.

**Be aware that if you complete the assignment on Binder, you cannot save and
return to your Binder session.**

### Due Date: 6pm on 9/10

This week's assignment will be broken into two parts:

## Part 1: Installing Python locally and launching a Jupyter notebook

Follow the [Zero to Python guide](https://musa-550-fall-2020.github.io/guides/zero-to-python) on the course website for instructions on how to setup Python
locally and launch the Jupyter notebook.

Please see the [list of recommended readings](https://github.com/MUSA-550-Fall-2020/week-1#recommended-readings) for tutorials and background reading to get
familiar with Python, conda, and the Jupyter notebook.

**Problems?** Post your question to [Piazza](https://piazza.com/class/ke999wuhrls2t8)!

## Part 2: Finding the Philadelphia ZIP Code with the maximum ZHVI over time

If you've successfully followed the guide in the previous step, you should have
installed Python and launched Jupyter by running `jupyter notebook`. This should
have launched the [Jupyter
dashboard](https://jupyter-notebook.readthedocs.io/en/stable/ui_components.html#notebook-dashboard).
Now you can create a new notebook
([instructions](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#creating-a-new-notebook-document))
and get started on the homework!

The notebook will execute code from the current working directory (the folder
that the notebook was launched from). This folder is usually your home folder on
your laptop. If you are using relative file paths to load the data, the path
should be relative to this working directory. From within the Jupyter notebook,
you can find out the current working directory by running the following command
in a cell:

```python
pwd
```

If you've downloaded the [assignment-1](https://github.com/MUSA-550-Fall-2020/assignment-1) repository to your computer, it usually makes sense to launch the
Jupyter notebook from this folder instead of the default folder. You can
change the start-up folder by first navigating to your assignment folder in
the command line: see instructions [here](https://musa-550-fall-2020.github.io/guides/jupyter#changing-the-jupyter-notebook-start-up-folder).

### Assignment Steps

Use a Jupyter notebook to find the Philadelphia ZIP code with the largest
average annual ZHVI value, for each year in the data set. The Zillow data is
available for download in this repository:
[data/Zip_Zhvi_AllHomes.csv](data/Zip_Zhvi_AllHomes.csv).

The Jupyter notebook should use _pandas_ to load the data and analyze it. The following steps should be followed:

1. Load the ZHVI data for each ZIP code, selecting only Philadelphia ZIP codes.
1. Calculate the annual average ZHVI for each ZIP code in Philadelphia and each year.
1. Identify the ZIP code with the maximum value for each year.

The final result should be the year and the ZIP code with the maximum value.

## Submission

Your assignment will be submitted as a Jupyter notebook (a `.ipynb` file) on Github.

**Please include your name and Github username at the top of the submitted
notebook.**

### Setting up GitHub for assignment submission

You should submit your assignment through Github. For each assignment, I will
provide a GitHub link that can be used to create a new repostiory. Each student
will have their own private repository on GitHub where the assignment can be
submitted. Only the student and instructors will have access to the private
repository.

The invitation link for this week is:

https://classroom.github.com/a/NzLRqDDV

If you do not have a GitHub account yet, you should be prompted to make an account. After clicking on this link, GitHub will create a new private repo with permissions such that only you and the instructors can view the commits.

Your assignment should be added to this GitHub repository before the deadline. You can add files to the repository through the web (github.com) interface or using the command line locally on your machine.

Below are some references if you need help:

- [Setting up git](https://help.github.com/articles/set-up-git/)
- [Managing files on GitHub](https://help.github.com/articles/managing-files-on-github/)
- [Managing files via the command line](https://help.github.com/articles/managing-files-using-the-command-line/)

**Important**: Files should be committed to the newly created private repository (after following the above link) and _not_ to your forked version of the [assignment-1](https://github.com/MUSA-550-Fall-2020/assignment-1) repository.

**Your Jupyter notebook should be submitted to your private repository by the deadline, 6pm on 9/10.**
