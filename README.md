# OMERO Plus Jupyter notebooks

This repository contains a set of [Jupyter notebooks](http://jupyter.org/) that demonstrate various image and metadata workflows by utilising OMERO Plus API.

Notebooks 1 - 3
================

Presented during [OMERO Plus for High Content Screening & Analysis: The Gold Standard in Data Management & Integratio](http://glencoesoftware.com/webinars.html#omero-plus-for-hcs) webinar.
These notebooks demonstrate how to access the analytical data stored in OMERO using OMERO.tables and file annotations.
The notebooks cover data retrieval, visualisation, statistical analysis and machine learning.

Notebook 4
==========

Preseted during [Using PathViewer and Multiplexed Imaging to Advance Cancer Research](http://glencoesoftware.com/webinars.html#pathviewer-multiplexed-imaging) webinar.
This notebook demonstrates how to read raw image pixels from OMERO Plus, perform image processing using [scikit-image](http://scikit-image.org/) and save the analysis results to OMERO Plus. Objects identified by [scikit-image](http://scikit-image.org/) algorithms are converted to OMERO region of interests (ROIs) and a set of key - value pairs describing each object.
The notebook covers raw pixel retrieval, image processing, OMERO ROI creation and saving, OMERO key - value pair creation, saving and linking to ROIs.

Requirements:
 * [OMERO.server](http://www.openmicroscopy.org/site/products/omero),
 * [OMERO.tables](https://www.openmicroscopy.org/site/support/omero5.2/sysadmins/server-tables.html),
 * [matplotlib](http://matplotlib.org/),
 * [pandas](http://pandas.pydata.org/),
 * [scikit-learn](http://scikit-learn.org/),
 * [scikit-image](http://scikit-image.org/).
