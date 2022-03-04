# Atlantic Innovation Week

14-17 MARCH 2022 
AZORES, PORTUGAL

## Workshop 03 - Introduction to Marine Debris Detection with Sentinel-2 using Python

This workshop gives you a brief introduction on marine debris detection using Sentinel-2 Level-2A data. You will learn how to automatically download Sentinel-2 products using Python (*sentinelsat*), use geospatial data analysis libraries (*Rasterio*, *GeoPandas* and *GDAL*) and calculate band indices (Floating Algae Index-FAI and Floating Debris Index-FDI) to identify agglomerations of floating vegetation (such as *sargassum*) and possible clusters of marine litter.

**How to run this workshop?**
1. Install [ANACONDA](https://www.anaconda.com/products/individual) (this notebook uses Python 3.8);
2. Prepare the Environment:
- **First Method:** Use *environment.yml* file to create your environment (tested on macOS Catalina and Anaconda 4.11.0). If you get `ResolvePackageNotFound` error try the second method;  
- **Second Method:** Create an environment called AIW-Workshop-Env, install Jupyter Notebook and manually install the following packages: *gdal, geopandas, rasterio, sentinelsat, python-dotenv, zipfile36 and ipywidgets widgetsnbextension pandas-profiling*.
3. To test the *sentinelsat* library, create a [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/self-registration) free account and add the credentials to the env.txt file, changing the file to hidden (.env); 
4. If you don't want to create a COAH account, or if your account is recent, you can download an example product [HERE](https://drive.google.com/drive/folders/1oMTw1laADQHn2_uwDBVKm6YoAcBr2XPt?usp=sharing). Create a new folder called *Sentinel2-Downloaded-Products* and save the product to that folder.

Results (south of Madeira Island, Portugal - 2021/03/29):

![Results](https://user-images.githubusercontent.com/69935277/155123275-18cb4f19-2861-44d1-b41f-fbb52c4c5f50.png)
