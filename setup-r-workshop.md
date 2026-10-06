---
layout: page
title: Setup for R workshop
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

| Software              | Install                         | Manual                | Available for         | Description                                      | 
| --------------------- | ------------------------------- | --------------------- | --------------------- | ------------------------------------------------ |
| Spreadsheet program   | [Download LibreOffice](https://www.libreoffice.org/download/download-libreoffice/)                                | [LibreOffice documentation](https://documentation.libreoffice.org/en/english-documentation/)                      | Linux, MacOS, Windows | Spreadsheet program for organizing tabular data. | 
| OpenRefine            | [Download OpenRefine](https://openrefine.org/download.html)                                | [OpenRefine documentation](https://openrefine.org/docs)                      | Linux, MacOS, Windows |                                                  | 
| R                     | See install instructions below. |                       | Linux, MacOS, Windows |                                                  | 
| RStudio               | [Download RStudio](https://posit.co/download/rstudio-desktop/#download)                                | [RStudio Cheatsheet](https://raw.githubusercontent.com/rstudio/cheatsheets/main/rstudio-ide.pdf)                      | Linux, MacOS, Windows |                                                  | 
| DB Browser for SQLite | [Download DB Browser for SQLite](https://sqlitebrowser.org/dl/)                                | Linux, MacOS, Windows |                       |                                                  | 






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








### R and RStudio

- R and RStudio are separate downloads and installations. R is the
  underlying statistical computing environment, but using R alone is no
  fun. RStudio is a graphical integrated development environment (IDE) that makes
  using R much easier and more interactive. You need to install R before you
  install RStudio. After installing both programs, you will need to install
  some specific R packages within RStudio. Follow the instructions below for
  your operating system, and then follow the instructions to install
  **`tidyverse`** and **`RSQLite`**.

#### Windows

:::::::::::::::: spoiler

## If you already have R and RStudio installed

- Open RStudio, and click on "Help" > "Check for updates". If a new version is
  available, quit RStudio, and download the latest version for RStudio.
- To check which version of R you are using, start RStudio and the first thing
  that appears in the console indicates the version of R you are
  running. Alternatively, you can type `sessionInfo()`, which will also display
  which version of R you are running. Go on
  the [CRAN website](https://cran.r-project.org/bin/windows/base/) and check
  whether a more recent version is available. If so, please download and install
  it.

You can [uninstall older versions of R][uninstall-r] if you wish to do so.


:::::::::::::::::::::::::

:::::::::::::::: spoiler

## If you don't have R and RStudio installed

- Download R from
  the [CRAN website](https://cran.r-project.org/bin/windows/base/release.htm).
- Run the `.exe` file that was just downloaded
- Go to the [RStudio download page][download-rstudio]
- Under *Installers* select **RStudio x.yy.zzz - Windows Vista/7/8/10** (where x, y, and z represent version numbers)
- Double click the file to install it
- Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.
  

:::::::::::::::::::::::::

#### macOS

:::::::::::::::: spoiler

## If you already have R and RStudio installed

- Open RStudio, and click on "Help" > "Check for updates". If a new version is
  available, quit RStudio, and download the latest version for RStudio.
  - To check the version of R you are using, start RStudio and the first thing
    that appears on the terminal indicates the version of R you are running. Alternatively, you can type `sessionInfo()`, which will
    also display which version of R you are running. Go on
    the [CRAN website](https://cran.r-project.org/bin/macosx/) and check
    whether a more recent version is available. If so, please download and install
    it. In any case, make sure you have at least R 3.2.
    

:::::::::::::::::::::::::

:::::::::::::::: spoiler

## If you don't have R and RStudio installed

- Download R from
  the [CRAN website](https://cran.r-project.org/bin/macosx/).
- Select the `.pkg` file for the latest R version
- Double click on the downloaded file to install R
- It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed
  by some packages)
- Go to the [RStudio download page][download-rstudio]
- Under *Installers* select **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)**
  (where x, y, and z represent version numbers)
- Double click the file to install RStudio
- Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.
  

:::::::::::::::::::::::::

#### Linux

- Follow the instructions for your distribution
  from [CRAN](https://cloud.r-project.org/bin/linux), they provide information
  to get the most recent version of R for common distributions. For most
  distributions, you could use your package manager (e.g., for Debian/Ubuntu run
  `sudo apt-get install r-base`, and for Fedora `sudo yum install R`), but we
  don't recommend this approach as the versions provided by this are
  usually out of date. In any case, make sure you have at least R 3.2.

- Go to the [RStudio download page][download-rstudio]

- Under *Installers* select the version that matches your distribution, and
  install it with your preferred method (e.g., with Debian/Ubuntu `sudo dpkg -i rstudio-x.yy.zzz-amd64.deb` at the terminal).

- Once it's installed, open RStudio to make sure it works and you don't get any
  error messages.

- After installing R and RStudio, you need to install the `tidyverse` and
  `RSQLite` packages. Start RStudio by double-clicking the icon and then type:
  `install.packages(c("tidyverse", "RSQLite"))`. You can also do this by going to Tools -> Install Packages and
  typing the names of the packages you want to install, separated by a comma.

[uninstall-r]: https://cran.r-project.org/bin/windows/base/rw-FAQ.html#How-do-I-UNinstall-R_003f
[download-rstudio]: https://posit.co/download/rstudio-desktop/#download









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


