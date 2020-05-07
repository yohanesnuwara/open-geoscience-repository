# Open Geoscience Computing Repository

> Geoscience computing workflow using Python with dataset in online and Google Drive databases.

👇 This is a quick catalogue of the open databases! Click on the associated link of each database to read the further details, including more detailed explanations (step-by-step) on the Python workflow to access the data.

Let's get started!

|Open Databases|Owner|Topics|Accessible Contents|How-to-access tutorial|
|:---:|:---:|:---:|:---:|:---:|
|[Google Drive<br> *Public geoscience Data*](https://github.com/yohanesnuwara/open-geoscience-repository#google-drive-public-geoscience-data)|Peter Amstrand|<ul> <li>Well logs</li> <li>Core data</li> <li>Seismic (3D)</li> </ul>|<ul> <li>Canning 3D TDQ seismic</li> <li>Dutch F3 seismic data</li> <li>GEOLINK North Sea wells</li> <li>Poseidon seismic</li> <li>Core Images</li> <li>48 well composite logs</li> </ul>|[Notebook](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/how_to_access_public_geoscience_data.ipynb)|
|[Google Drive<br> *Open Digital Rock*](https://github.com/yohanesnuwara/open-geoscience-repository#google-drive-open-digital-rock)|yohanesnuwara|Digital rock<br>dataset|<ul> <li>Berea sandstone</li> <li>Synthetic rock</li> </ul>|[Notebook]()|
|[SEG Wiki](https://github.com/yohanesnuwara/open-geoscience-repository#seg-wiki-open-data)|SEG|<ul> <li>Well logs</li> <li>Seismic (2D)</li> <li>Seismic (3D)</li> <li>Synthetic Models</li> </ul>|<ul> <li>Poland 2D Vibroseis</li> <li>Stratton 3D</li> <li>Mobil Avo Viking<br>Graben Line 12</li> <li>New Zealand 3D</li> </ul>|[Notebook]()|
|[Digital Rocks Portal](https://github.com/yohanesnuwara/open-geoscience-repository#digital-rocks-portal)|The University of Texas<br>at Austin|Digital rock<br>dataset|<ul> <li>Austin Chalk</li> <li>Bentheimer</li> <li>Estaillades Carbonate</li> <li>Fontainebleau</li> </ul>|[Notebook]()|
|[GDR OpenEi](https://github.com/yohanesnuwara/open-geoscience-repository/blob/master/README.md#geothermal-data-repository-gdr-openei)|United States<br> Geological Survey|Geothermal|<ul> <li>Utah FORGE</li> <li>Project KIMAMA</li> </ul>|[Notebook]()|

### Why do we need Google Colaboratory?

For Python users, we have already been familiar with the **Jupyter notebooks** on a local computer. While geoscience datasets often comes into a very **large size** (megabytes, gigabytes), we don't want to populate our computer with large datasets. The right choice, is to access the datasets and compute **on cloud**.

Yes, **Google Colaboratory is a Jupyter notebook in the Google cloud** (Note: not a Google Cloud Platform). Why Google Colab? Well, first and foremost, Google Colab is free. Second, we can speed up the download rate of a large dataset. 

On top of every how-to-access tutorial notebooks link, there will be a badge like this [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com). Click this badge, and we will be re-directed to Google Colab to run the codes. 

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

After this, we will do lots of geoscience computation with this open dataset!

### Python computing workflows

* Well log visualization and analysis (BIG DATA)
* Read seismic data
* Colored seismic inversion
* Machine learning!

# Google Drive *Open Digital Rock*

I just compile a handful of public digital rock datasets in this Google Drive. Contents as follows:
* Berea sandstone (Source: [Imperial College London](https://www.imperial.ac.uk/earth-science/research/research-groups/perm/research/pore-scale-modelling/micro-ct-images-and-networks/berea-sandstone/))
* Synthetic rock datasets (7 datasets)

### How to access these data?

The steps also go similarly with the [previous steps](https://github.com/yohanesnuwara/open-geoscience-repository#google-drive-public-geoscience-data) of transferring the folder `Open Digital Rock` from folder `Shared with Me` to `My Folder`. Follow through the steps, until you are in Google Colab. Then open this [notebook]() to learn how to access the dataset.  

# SEG Wiki Open Data

The website SEG Wiki, please go through the [page](https://wiki.seg.org/wiki/Open_data) to see the lists of the open data. There are almost > 30 major datasets (well logs, 2D and 3D seismic both the original data from major fields and synthetic data, synthetic earth model, gravity and magnetic data, etc) overall, <ins>however</ins> some data contains unrecognizable formats that could not be processed simply in Python. Here are some of the contents that are accessible so far:

[![Data repo](https://img.shields.io/badge/data%20available-SEG%20wiki-orange)](https://wiki.seg.org/wiki/Open_data)

* Poland 2D Vibroseis Line
* Stratton 3D
* Mobil Avo Viking Graben Line 12

> Note: These lists will be updated frequently whenever I find certain dataset could be accessed using Python!



# Digital Rocks Portal

# Geothermal Data Repository (GDR) OpenEi

