# Open Geoscience Computing Repository

[![License](https://img.shields.io/badge/license-Creative%20Commons%204.0-orange)](https://creativecommons.org/licenses/by/4.0/)

> Geoscience computing workflow using Python with dataset in online and Google Drive databases.

👇 This is a quick catalogue of the open databases! Click on the associated link of each database to read the further details, including more detailed explanations (step-by-step) on the Python workflow to access the data.

Let's get started!

|Open Databases|Owner|Topics|Accessible Contents|How-to-access tutorial|
|:---:|:---:|:---:|:---:|:---:|
|[Google Drive<br> *Public geoscience Data*](https://github.com/yohanesnuwara/open-geoscience-repository#google-drive-public-geoscience-data)|Peter Amstrand|<ul> <li>Well logs</li> <li>Core data</li> <li>Seismic (3D)</li> </ul>|<ul> <li>Canning 3D TDQ seismic</li> <li>Dutch F3 seismic data</li> <li>GEOLINK North Sea wells</li> <li>Poseidon seismic</li> <li>Core Images</li> <li>48 well composite logs</li> </ul>|[Notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_access_public_geoscience_data.ipynb)|
|[SEG Wiki](https://github.com/yohanesnuwara/open-geoscience-repository#seg-wiki-open-data)|SEG|<ul> <li>Well logs</li> <li>Seismic (2D)</li> <li>Seismic (3D)</li> <li>Synthetic Models</li> </ul>|<ul> <li>Poland 2D Vibroseis</li> <li>Stratton 3D</li> <li>Mobil Avo Viking<br>Graben Line 12</li> <li>New Zealand 3D</li> </ul>|[Notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_open_seg_wiki.ipynb)|
|[GDR OpenEI](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/README.md#geothermal-data-repository-gdr-openei)|United States<br> Department of Energy|Geothermal|<ul> <li>Project Utah FORGE</li> <li>Project HOTSPOT</li> </ul>|[Notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_access_gdr_openei.ipynb)|
|[KGS Repository](http://www.kgs.ku.edu/PRS/Scans/Log_Summary/index.html)|Kansas Geological Survey|Oil and Gas|Archive of well logs<br> from 1990 up to date||
|[MSEEL Repository](http://www.mseel.org/data/Wells_Datasets/)|Marcellus Shale Energy<br> and Environmental Laboratory|Unconventional<br> Oil and Gas|Well datasets in<br> Marcellus Shale|[notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_access_mseel.ipynb)|
|[14 Wildcat Wells in the</br> National Petroleum Reserve</br> in Alaska](https://certmapper.cr.usgs.gov/data/PubArchives/OF00-200/WELLS/WELLIDX.HTM)|Department of the Interior</br>U.S. Geological Survey|Oil and Gas</br> wildcat survey|<ul> <li>Well logs</li> <li>Core photographs</li></ul>||
|[Oil and Gas Data</br> Files](http://www.occeweb.com/og/ogdatafiles2.htm)|Oklahoma Corporation Commission|Oil and Gas|Production Data||
|[SPE Data Repository](https://www.spe.org/en/industry/data-repository/)|SPE|Multi-fracture well|<ul> <li>Well logs</li> <li>Deviation</li> <li>Production data</li></ul>

### ⚠️ Look at this sign ... 

at the end of each of the open databases below. This is a **Copyright** note, meaning that when you use this data for certain purposes, you should cite the dataset to its owner institution. Please review the <ins>wiki-page link</ins> that associates.  

### ❓ Why do we need Google Colaboratory?

For Python users, we have already been familiar with the **Jupyter notebooks** on a local computer. While geoscience datasets often comes into a very **large size** (megabytes, gigabytes), we don't want to populate our computer with large datasets. The right choice, is to access the datasets and compute **on cloud**.

Yes, **Google Colaboratory is a Jupyter notebook in the Google cloud** (Note: not a Google Cloud Platform). Why Google Colab? Well, first and foremost, Google Colab is free. Second, we can speed up the download rate of a large dataset. 

On top of every how-to-access tutorial notebooks link, there will be a badge like this ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg). **<ins>Click this badge</ins>**, and we will be re-directed to Google Colab to run the codes. 

# Google Drive *Public geoscience Data*

This Google Drive database comprises of public geoscience data compiled by [@peter Ba](peteramstrand@gmail.com). Contents as follows:
* Canning 3D TDQ seismic
* Dutch F3 seismic data
* GEOLINK North Sea wells
* Poseidon seismic
* Core images
* 48 well composite logs

### How to access these data?

Follow these steps:
1. Open this link 👉 [![Data repo](https://img.shields.io/badge/data%20available-google%20drive-green)](https://drive.google.com/drive/u/0/folders/0B7brcf-eGK8CRUhfRW9rSG91bW8)
2. Once you open the drive, the folder `Public geoscience Data` will be stored in your `Shared with Me`.
3. Move the folder `Public geoscience Data` into your `My Drive`. Just drag and drop. Follow the GIF tutorial below if you feel lost how to do this action 🙂

<div>
<img src="https://user-images.githubusercontent.com/51282928/81036756-74108880-8eca-11ea-94c3-041ff4a5cc5d.gif" width="900"/>
</div>

4. Once the `Public geoscience Data` moved to your `My Drive`, you could then access it. To access the data, we will use Google Colaboratory! Google Colab will be used for the entire geoscience computation in this repo.
5. A tutorial notebook consists of workflow to access the data (from **extracting ZIP or TAR files** to **viewing simple data e.g. seismic data and well log data**) is provided. Visit [this notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_access_public_geoscience_data.ipynb)

> ⚠️ **Copyright** Every dataset that we use must be cited to the institution that owns the dataset. Please refer to this [citation wiki-page](https://github.com/yohanesnuwara/open-geoscience-repository/wiki/Google-Drive-Public-geoscience-Data---How-to-Cite)

# SEG Wiki Open Data

The website SEG Wiki, please go through the [page](https://wiki.seg.org/wiki/Open_data) to see the lists of the open data. There are almost > 30 major datasets (well logs, 2D and 3D seismic both the original data from major fields and synthetic data, synthetic earth model, gravity and magnetic data, etc) overall, <ins>however</ins> some data contains unrecognizable formats that could not be processed simply in Python. Here are some of the contents that are accessible so far:

* Poland 2D Vibroseis Line
* Stratton 3D
* Mobil Avo Viking Graben Line 12

> Note: These lists will be updated frequently whenever I find certain dataset could be accessed using Python!

### How to access these data?

First off, it is best if we know any detail about the dataset. So, please visit first the SEG Wiki [page](https://wiki.seg.org/wiki/Open_data), and browse the name of the dataset.

Next, directly visit this tutorial [notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_open_seg_wiki.ipynb) link, click on the badge ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) that appeared on top, and you will be re-directed to Google Colab. We will learn how to use `wget` to get the data directly from the open database website, just follow through the instructions! 

> ⚠️ **Copyright** Every dataset that we use must be cited to the institution that owns the dataset. Please refer to this [citation wiki-page](https://github.com/yohanesnuwara/open-geoscience-repository/wiki/SEG-Wiki-Open-Data---How-to-Cite)

# Geothermal Data Repository (GDR) OpenEI

GDR OpenEi is an open geothermal energy data portal provided by the United States Department of Energy (DoE) and developed by the National Renewable Energy Laboratory (NREL). Datasets in from the U.S. FORGE geothermal projects, Enhanced Geothermal System (EGS), and Hydrothermal, in this [webpage](https://gdr.openei.org/). Contents as follows:

* Project Utah FORGE (Roosevelt Hot Springs)
* Project HOTSPOT (The Snake River Plain, SRP)

### How to access these data?

First off, it is best if we know any detail about the dataset. So, please visit first the SEG Wiki [page](https://wiki.seg.org/wiki/Open_data), and browse the name of the dataset.

Next, directly visit this tutorial [notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_access_gdr_openei.ipynb) link, click on the badge ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) that appeared on top, and you will be re-directed to Google Colab. We will learn how to use `wget` to get the data directly from the open database website, just follow through the instructions! 

> ⚠️ **Copyright** Every dataset that we use must be cited to the institution that owns the dataset. Please refer to this [citation wiki-page](https://github.com/yohanesnuwara/open-geoscience-repository/wiki/GDR-OpenEi---How-to-Cite)

## Valuable libraries

1. segyio: the easy-to-understand tutorial from [Awesome Open Source](https://awesomeopensource.com/project/equinor/segyio) and official docs from [Equinor's segyio](https://segyio.readthedocs.io/en/1.5.3/segyio.html)
2. lasio: [docs](https://lasio.readthedocs.io/en/latest/)
3. amazing project.
