---
layout: page
title: Setup for Python workshop
---






# Overview

This workshop is designed to be run on your laptop.
First, you will need to download the data we use in the workshop.
Then, you need to install some software.
After following the instructions on this
page, you should have everything you need to participate fully in the workshop!








## Data

You can [download all of the data used in this workshop](https://ndownloader.figshare.com/articles/6262019/versions/4)
as a single zip file. The file is 206 KB.

Clicking the download link will automatically download all of the files to your default download directory as a single compressed
(`.zip`) file. To expand this file, double click the folder icon in your file navigator application (for Macs, this is the Finder
application).

For a full description of the data used in this workshop see the [data page](data).



## Software

| Software              | Install                         | Manual | Available for         | Description                                      | 
| --------------------- | ------------------------------- | ------ | --------------------- | ------------------------------------------------ |
| Spreadsheet program   | [Download LibreOffice](https://www.libreoffice.org/download/download/)                                | [LibreOffice documentation](https://documentation.libreoffice.org/en/english-documentation/)       | Linux, MacOS, Windows | Spreadsheet program for organizing tabular data. | 
| OpenRefine            | [Download OpenRefine](https://openrefine.org/download.html)                                | [OpenRefine documentation](https://openrefine.org/docs)       | Linux, MacOS, Windows |                                                  | 
| Python                | See install instructions below. |        | Linux, MacOS, Windows |                                                  | 
| DB Browser for SQLite | [Download DB Browser for SQLite](https://sqlitebrowser.org/dl/)                                |        | Linux, MacOS, Windows |                                                  | 






### Spreadsheet program

- To interact with spreadsheets, we can use LibreOffice, Microsoft Excel, Gnumeric, OpenOffice.org, or other programs.
  Commands may differ a bit between programs, but the general ideas for thinking about spreadsheets are the same. For this workshop,
  we recommend using either Microsoft Excel (paid software) or LibreOffice (free and open source). Other spreadsheet programs may
  not have all of the features we will be exploring in this workshop.

- To install LibreOffice, first [download LibreOffice](https://www.libreoffice.org/download/download-libreoffice/). The website should
  automatically select the correct option for your operating system. Click the "Download" button. You will go to a page that asks about a
  donation, but you don't need to make one. Your download should begin automatically. Once the installer is downloaded, double click on it (you may need to open your Downloads folder) and LibreOffice should install.








### OpenRefine

OpenRefine can be downloaded from the [OpenRefine downloads]() page.
When you download the version for your operating system, you are redirected to
a page with initial instructions for running the software.

More detailed instructions are included in the [Setup section in the OpenRefine
for Social Science Data](https://datacarpentry.org/openrefine-socialsci/#software).








### Python and Jupyter Notebooks

- [Python](https://python.org) is a popular language for
  scientific computing, and great for general-purpose programming as
  well. For this workshop we use Python version 3.x.
  Installing all of its scientific packages individually can be
  a bit difficult, so we recommend an all-in-one installer.
  We will use Anaconda or Miniconda.
  They both use [Conda](https://conda.io/en/latest/), the main difference is
  that Anaconda comes with a lot of packages pre-installed.
  With Miniconda you will need to install the required packages.
  We recommend using the Anaconda installation instructions.

:::::::::::::::: spoiler

## Anaconda installation

Download and install [Anaconda](https://www.anaconda.com/distribution/#download-section).
Remember to choose the installer for Python 3.x.
Anaconda does not include the plotting package plotnine.  To install this package, open your terminal application and
type:

```bash
conda install -c conda-forge plotnine
```

:::::::::::::::::::::::::

:::::::::::::::: spoiler

## Miniconda installation

Miniconda is a "light" version of Anaconda. If you install and use Miniconda
you will also need to install the workshop packages.

Download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
following the instructions. Remember to choose the installer for
Python 3.x.

From your terminal application, type:

```bash
conda list
```

To install the packages we'll be using in the workshop, type:

```bash
conda install -y numpy pandas matplotlib jupyter
conda install -c conda-forge plotnine
```

:::::::::::::::::::::::::

After installing either Anaconda or Miniconda and the workshop packages,
launch a Jupyter notebook by typing this command from the terminal:

```bash
jupyter notebook
```

The notebook should open automatically in your browser. If it does not or you
wish to use a different browser, open this link: [http://localhost:8888](https://localhost:8888).

For a brief introduction to Jupyter Notebooks, please consult our
[Introduction to Jupyter Notebooks](https://datacarpentry.org/python-ecology-lesson/jupyter_notebooks) page.








## SQL

- SQL is a specialized programming language used with databases.  We
  use a simple database manager called [SQLite](https://www.sqlite.org/)
  in our lessons. We will use the [DB Browser for SQLite](https://sqlitebrowser.org/) program,
  which is available for all major platforms.

- To install the DB Browser, first [download DB Browser for SQLite](https://sqlitebrowser.org/dl/) and choose the correct installer for
  your operating system. Once the installer is downloaded, double click on it (you may need to open your Downloads folder), follow
  any other instructions that appear, and
  DB Browser should install. After installing, you can delete the installer file.



Congratulations! You are now ready for the workshop!


