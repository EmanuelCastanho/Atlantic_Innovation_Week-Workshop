# Atlantic Innovation Week

14-17 MARCH 2022 
AZORES, PORTUGAL

## Workshop - Introduction to Marine Debris Detection with Sentinel-2 using Python

This workshop gives you a brief introduction on marine debris detection using Sentinel-2 Level-2A data. You will learn how to automatically download Sentinel-2 products using Python (*sentinelsat*), use geospatial data analysis libraries (*Rasterio*, *GeoPandas* and *GDAL*) and calculate band indices (Floating Algae Index-FAI and Floating Debris Index-FDI) to identify agglomerations of floating vegetation (such as *sargassum*) and possible clusters of marine litter.

**How to run this workshop?**
1. Install [ANACONDA](https://www.anaconda.com/products/individual) or [MINICONDA](https://docs.conda.io/en/latest/miniconda.html) (this notebook uses Python 3.8);
2. Prepare the Environment:
- **First Method:** Use *environment_macOS.yml* or *environment_Win.yml* file to create your environment (tested on macOS Catalina and Windows 10). If you get `ResolvePackageNotFound` error try the second method;  
- **Second Method:** Create an environment called AIW-Workshop-Env and manually install the following packages: `jupyter`, `gdal=3.4.1`, `geopandas=0.10.2`, `rasterio=1.2.10` (all with conda-forge), `sentinelsat==1.1.1`, `python-dotenv==0.19.2` and `zipfile36==0.1.3` (all with pip). Install conda-forge packages first. On Windows, do not use `conda install -c conda-forge jupyter`, but `pip install notebook`. On Windows, to solve *geopandas* error related to *spatialindex_c.dll*, use `pip uninstall rtree`.
3. To test the *sentinelsat* library, create a [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/self-registration) free account and add the credentials to the env.txt file, changing the file to hidden and removing the .txt extension (.env); 
4. If you don't want to create a COAH account, or if your account is recent, you can download an example product [HERE](https://drive.google.com/drive/folders/1oMTw1laADQHn2_uwDBVKm6YoAcBr2XPt?usp=sharing) and save to *Sentinel2-Downloaded-Products* folder.

Results (south of Madeira Island, Portugal - 2021/03/29):

![Results](https://user-images.githubusercontent.com/69935277/155123275-18cb4f19-2861-44d1-b41f-fbb52c4c5f50.png)
