---
layout: article
title: Using Python with Engineering Software and Data
permalink: /home/python-engineering
key: Python
cover:
aside:
  toc: false
---

![Python Database](/assets/images/python-article.png)

## Why use Python?

Digitisation of data is rapidly developing with the need of managing bulk geotechnical data and analysis. This evolution still involves engineering judgement but requires the adoption of available technology and tools to handle data outside an Excel spreadsheet. The visualisation of data brings insights into information we acquire from logs, field tests, laboratory tests and correlations. Completing repetitive calculations and summarising projects with big data reduces the efficiency whilst using conventional practices and this is where Python is a great tool.<!--more-->

## Engineering Software with Python Scripting

Python scripting is now very commonly inbuilt into a variety of engineering software, which is readily available to geotechnical engineers and has a variety of applications to automate/optimise geotechnical engineering practices. PLAXIS is an example where Python scripting is integrated into the software with resources and tutorials on its ability within the PLAXIS environment [Plaxis API Python Scripting](https://communities.bentley.com/products/geotech-analysis/w/wiki/45393/api-python-scripting---plaxis).
FLAC 3D is another program that has Python embedded into it allowing scripting with the use of the Python library Numpy to work with arrays quicker . A different example would be Surfer which already supports automation through Scripter which follows a Visual Basic like language. Python scripts can connect/call Surfer to allow automated workflows using this language instead of using Scripter. So, in some cases where Python isn’t embedded into the software, there is the possibility of connecting to the program.

## Python Uses in Geotech

Python has a plethora of libraries to serve the purpose of calculating, handling and visualising geotechnical data and is considered one of the easier programming languages to learn considering its vast applications. Python is also well-documented with many open-source projects and resources which are commonly sourced on GitHub.
Probably the most used geodatabase is gINT, where extracting data over different projects can be seen as tedious and especially when trying to merge project files that don’t follow the same gINT template. This is commonly an issue with the data we collect over varying years as irregularities in how we store data from log formats, different contractors, or changes in the industry standard.
Using python to read, import and combine gINT files gives the function of a data handler using just a few python libraries. Pyodbc is used to access the gINT database but also query from the tables. Pandas is a library that is more powerful in handling data analysis and manipulation to be able to process the data after queries are complete and the ability to export data frames to excel.

Manual conversion commonly takes the most time in the current practice, where typing hardcopy logs, converting CPT data and digitising laboratory testing plots are just some of the few obstacles that are cases that hinder automating processes. Again, there are python libraries that can scrape data from pdfs using Tabula and Pandas, where automating some of this process can be possible.
Visualization of data is a common use for Python in many industries and is a great tool for geotechnical engineering where CPTs, 3D models, soil profiles, settlement and topography data are just a few examples where python is the perfect tool. It can easily tie into automating model creation for batch processing and GIS software

## Further Resources
Some notable mentions of the python libraries that I miss are Groundhog by Bruno Stuyts which has a variety of general geotechnical purpose functions. [Groundhog Documentation](https://groundhog.readthedocs.io/en/master/)
For 3D geological models and 2D Sections GemPy is another python library that caters to the field of geotechnical engineering. [GemPy's website](https://www.gempy.org)