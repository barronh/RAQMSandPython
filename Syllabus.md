# Python for Air Research and Application

## Objectives

1. Produce publication quality graphics
2. Perform standard model performance evaluations
3. Create emission perturbations
4. Add custom modifications to each exercise

## Abstract

Attendees will learn how to leverage Python to interact with air pollution-related model and observational data. Air research and application relies on big data. In addition to the challenge presented by data size, researchers must understand a multitude of formats and meta-data standards. For example, CMAQ, CAMx, and GEOS-Chem all use different formats and different meta-data conventions. This tutorial provides format-independent and convention-independent tools.

## Requirements

* Some scripting experience (R, Python, Perl, bash, or csh). Attendees who do not have experience can follow my on-line Python-primer (http://www.barronh.com/software/tutorials/python-tutorial) to satisfy the requiremnt.
* A computer with either
  * Windows, Linux, or Mac; a text editor; and Anaconda 3.5 installed.
  * or a computer and an account on wakari.io

## Sections (4 hours)

### Intro to the Common Data Model (30 minutes)

1. files and groups
2. dimensions
3. properties
4. variables
5. Conventions
  * IOAPI and WRF-IOAPI
  * Climate Forecasting (CF) Conventions
6. Conceptualizing any data set as CDM

### Intro to ipython (30 minutes)

1. Loading key libraries
2. Running interactively
3. Running a saved file
4. Making and saving a figure

### Tile Plots (30 minutes)

Make tile plots of ozone with 3 different methods from CMAQ data.

1. Python Environment
2. Python with PseudoNetCDF
3. Command Line Interface (terminal or DOS)
4. Advanced users will overlay observations
5. Advanced users will repeat with CAMx or GEOS-Chem

### Common Processing and Terminology (30 minutes)

This section will explain many of the techniques used in the tile plot section and in all subsequent sections.

1. slicing in numpy
2. dimensional reductions
3. Loading data from different formats
  * CMAQ (already done)
  * CAMx, WRF, GEOS-Chem, CSV, NASA AMES, AQS
4. Adding coordinate variables
5. Using named dimensions via PseudoNetCDF
6. Adding derived variables via PseudoNetCDF

### Time series (30 minutes)

Make time series plots with 3 different methods from CMAQ data.

1. Python Environment
2. Python with PseudoNetCDF
3. Command Line Interface (terminal or DOS)
4. Advanced users will add observations
5. Advanced users will add another species on a secondary axis
6. Advanced users will repeat with CAMx or GEOS-Chem


### Scatter Plots (30 minutes)

1. Python Environment
2. Python with PseudoNetCDF
3. Command Line Interface (terminal or DOS)
4. Advanced users will switch from time/space paired to rank paired

### Statistical Evaluations (30 minutes)

1. Python with PseudoNetCDF
2. Command Line Interface
3. Advanced users will write their own function.

### Emissions Perturbations (30 minutes)

1. CMAQ - Python without PseudoNetCDF
2. CAMx - Python with PseudoNetCDF

### Wrapping up (30 minutes)

1. Expanding on what we've done
2. Questions

### Guided Custom Analyses (afternoon optional session: 120 minutes)

1. k-cluster analysis in Python
2. ttest, Mann-Whitney-U
3. applying evaluations over specified dimensions
