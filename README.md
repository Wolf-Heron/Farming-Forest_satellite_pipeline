Presentation du projet d'exploitation d'images satellites dans le domaine agricole :

Cadre du projet :
_ source de données : images Sentinel 2 (lien vers le portail ici : https://dataspace.copernicus.eu)
_ objectif : Calcul d'indices liés à l'état de santé de parcelles agricoles (ex : NDVI, NDRE, ...)
_ format de sortie : image(s) GEOTIFF, indicateurs éventuels dans un fichier .txt
_ Echelle : une image à la fois


Liste de modules Python necessaires pour coder la chaîne de traitement :

Besoin	                     --  Outil
Gestion env + deps	         --  uv (rapide) ou poetry
Lecture raster	             --  rasterio
Calcul array	             --  numpy, xarray
Géométries vectorielles	     --  geopandas, shapely
Téléchargement Sentinel	     --  sentinelsat, pystac-client
Viz	                         -- matplotlib, folium
Tests	                     --  pytest
Lint/format	                 --  ruff (remplace black+flake8+isort)
Typage	                     --  mypy