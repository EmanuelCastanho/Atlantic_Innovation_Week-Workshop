# Atlantic Innovation Week

14-17 MARCH 2022 
AZORES, PORTUGAL

## Workshop 03 - Introduction to Marine Debris Detection with Sentinel-2 using Python

This workshop gives you a brief introduction on marine debris detection using Sentinel-2 Level-2A data. You will learn how to automatically download Sentinel-2 products using Python (*sentinelsat*), use geospatial data analysis libraries (*Rasterio*, *GeoPandas* and *GDAL*) and calculate band indices (Floating Algae Index-FAI and Floating Debris Index-FDI) to identify agglomerations of floating vegetation (such as *sargassum*) and possible clusters of marine litter.

To run this workshop just click on the **Binder Environment**. If you want to test the *sentinelsat* library, you will need a [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/self-registration) free account and add the credentials to the env.txt file, changing the file to hidden (.env). 

If you don't want to create a COAH account, or if your account is recent, you can download an example product [HERE](https://drive.google.com/drive/folders/1oMTw1laADQHn2_uwDBVKm6YoAcBr2XPt?usp=sharing). Create a new folder called *Sentinel2-Downloaded-Products* and save the product to that folder.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/EmanuelCastanho/Atlantic_Innovation_Week-Workshop/main?labpath=Introduction_to_Marine_Debris_Detection_with_Sentinel-2_using_Python.ipynb)

Results (south of Madeira Island, Portugal - 2021/03/29):

![Results](https://user-images.githubusercontent.com/69935277/155123275-18cb4f19-2861-44d1-b41f-fbb52c4c5f50.png)
