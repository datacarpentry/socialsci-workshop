---
layout: lesson
root: .
---

Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools for working
with data so that they can get more done in less time, and with less pain. This workshop
teaches data management and analysis for social science research including best practices for data organization 
in spreadsheets, reproducible data cleaning with OpenRefine, data analysis and visualization in either R or Python
and extraction of information from relational databases using SQL. This workshop is designed to 
be taught over two full days of instruction.

> ## Getting Started
>
> This lesson assumes no prior experience with the tools covered in the workshop. 
> Participants should bring their laptops and plan to participate actively. 
> 
> To get started, follow the directions in the [setup](./setup.md) page to 
> get access to the required software and data for this workshop.
{: .prereq}

> ## Data
> 
> This workshop uses data from two different sources.
> 
> ### Audit of Political Engagement 11, 2013 (UKDS: SN7577)
> 
> The dataset is an open dataset available for download from the [UK Data Service](https://www.ukdataservice.ac.uk/ ). It can 
> be found by searching using the keyword SN7577.
> 
> There are several dated versions of the dataset available. We will be using the 2013 edition. Several other years are available, 
> although the columns may change. There is also a combined dataset for the years 2003-2012 under SN7404. As with most datasets > in the UK Data Service, the data can be downloaded in a variety of formats.  Rather than downloading directly from the UK Data > Service site, copies of the data in csv (comma separated values) and .sqlite (for the SQL lesson)  has been made and can be 
> downloaded from the [setup](./setup.md) page. 
> 
> ### SAFI survey data
> 
> SAFI is a currently running project which is looking at farming and irrigation methods. 
> This is survey data relating to households and agriculture in Tanzania and Mozambique. 
> The survey form was created using the ODK (Open Data Kit) software via an Excel spreadsheet. 
> This is used to create a form which can be downloaded and displayed (and completed) on an Android smartphone. 
> The results are then sent back to a central server. 
> The server can be used to produce the collected data in both JSON and CSV formats.
> It is a sample of the collected data in csv format that we will be using. 
> The data can be downloaded from the [setup](./setup.md) page.
> 
{: .prereq} 

# Workshop Overview 

| Lesson    | Overview |
| ------- | ---------- |
| [Data Organization in Spreadsheets](https://datacarpentry.github.io/spreadsheets-socialsci/) | Learn how to organize tabular data, handle date formatting, carry out quality control and quality assurance and export data to use with downstream applications. |
| [Data Cleaning with OpenRefine](https://datacarpentry.github.io/openrefine-socialsci/) | Explore, summarize, and clean tabular data reproducibly. |
| [Data Analysis and Vizualization with R](https://datacarpentry.github.io/r-socialsci) | Import data into R, calculate summary statistics, and create publication-quality graphics.|
| [Data Analysis and Vizualization with Python](https://datacarpentry.github.io/python-socialsci/) | Import data into Python, calculate summary statistics, and create publication-quality graphics.|
| [Data Management with SQL](https://datacarpentry.github.io/sql-socialsci/) | Extract information from relational databases. |
