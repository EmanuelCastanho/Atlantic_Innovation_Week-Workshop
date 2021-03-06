# Atlantic Innovation Week

14-17 MARCH 2022 
AZORES, PORTUGAL

## Workshop - Introduction to Marine Debris Detection with Sentinel-2 using Python

**[PT]**

Este workshop oferece uma breve introdução sobre a detecção de detritos marinhos utilizando dados Level-2A de Sentinel-2. Irás aprender como baixar automaticamente os produtos Sentinel-2 usando Python (*sentinelsat*), usar bibliotecas de análise de dados geoespaciais (*Rasterio*, *GeoPandas* e *GDAL*) e calcular índices (Floating Algae Index-FAI e Floating Debris Index-FDI) para identificar aglomerações de vegetação flutuante (como *sargassum*) e possíveis aglomerados de lixo marinho.

**Como rodar este workshop?**
1. Instale [ANACONDA](https://www.anaconda.com/products/individual) ou [MINICONDA](https://docs.conda.io/en/latest/miniconda.html) (este notebook utiliza Python 3.8);
2. Prepare o ambiente:
- **Não sabe como importar um ambiente?** Veja como fazer utilizando [GUI](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/) ou [TERMINAL](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html);
- **Primeiro método:** utilize o arquivo *environment_macOS.yml* ou *environment_Win.yml* para criar o ambiente (testado no macOS Catalina e Windows 10). Se surgir o erro `ResolvePackageNotFound` tente o segundo método;
- **Segundo Método:** Crie um ambiente chamado AIW-Workshop-Env e instale manualmente os seguintes pacotes: `jupyter`, `gdal=3.4.1`, `geopandas=0.10.2`, `rasterio=1.2.10` (todos com conda-forge), `sentinelsat==1.1.1`, `python-dotenv==0.19.2` e `zipfile36==0.1.3` (todos com pip). Instale os pacotes conda-forge primeiro. No Windows, não use `conda install -c conda-forge jupyter`, mas sim `pip install notebook`. No Windows, para resolver o erro *geopandas* relacionado com *spatialindex_c.dll*, use `pip uninstall rtree`.
4. Para testar a biblioteca *sentinelsat*, crie uma conta gratuita no [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/self-registration) e adicione as credenciais ao arquivo env.txt, alterando o arquivo para oculto e removendo a extensão .txt (.env);
5. Se não quiseres criar uma conta COAH, ou se a tua conta for recente, podes baixar um exemplo de produto [AQUI](https://drive.google.com/drive/folders/1oMTw1laADQHn2_uwDBVKm6YoAcBr2XPt?usp=sharing ) e salvar na pasta *Sentinel2-Downloaded-Products*.

Resultados (sul da Ilha da Madeira, Portugal - 2021/03/29):

**[EN]**

This workshop gives you a brief introduction on marine debris detection using Sentinel-2 Level-2A data. You will learn how to automatically download Sentinel-2 products using Python (*sentinelsat*), use geospatial data analysis libraries (*Rasterio*, *GeoPandas* and *GDAL*) and calculate band indices (Floating Algae Index-FAI and Floating Debris Index-FDI) to identify agglomerations of floating vegetation (such as *sargassum*) and possible clusters of marine litter.

**How to run this workshop?**
1. Install [ANACONDA](https://www.anaconda.com/products/individual) or [MINICONDA](https://docs.conda.io/en/latest/miniconda.html) (this notebook uses Python 3.8);
2. Prepare the Environment:
- **Don't know how to import an environment?** See how to do it using [GUI](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/) or [TERMINAL](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html);
- **First Method:** Use *environment_macOS.yml* or *environment_Win.yml* file to create your environment (tested on macOS Catalina and Windows 10). If you get `ResolvePackageNotFound` error try the second method;  
- **Second Method:** Create an environment called AIW-Workshop-Env and manually install the following packages: `jupyter`, `gdal=3.4.1`, `geopandas=0.10.2`, `rasterio=1.2.10` (all with conda-forge), `sentinelsat==1.1.1`, `python-dotenv==0.19.2` and `zipfile36==0.1.3` (all with pip). Install conda-forge packages first. On Windows, do not use `conda install -c conda-forge jupyter`, but `pip install notebook`. On Windows, to solve *geopandas* error related to *spatialindex_c.dll*, use `pip uninstall rtree`.
4. To test the *sentinelsat* library, create a [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/self-registration) free account and add the credentials to the env.txt file, changing the file to hidden and removing the .txt extension (.env); 
5. If you don't want to create a COAH account, or if your account is recent, you can download an example product [HERE](https://drive.google.com/drive/folders/1oMTw1laADQHn2_uwDBVKm6YoAcBr2XPt?usp=sharing) and save to *Sentinel2-Downloaded-Products* folder.

Results (south of Madeira Island, Portugal - 2021/03/29):

![Results](https://user-images.githubusercontent.com/69935277/159045080-81e25981-dcaa-4651-a87b-1c5e3915eeb2.png)
