# Prérequis :
- Ouvrir une console anaconda prompt;
- Se placer dans le chemin où se trouve le fichier 1_Entretien technique.ipynb;
- Taper les commandes suivantes :
	- Création d'un environnement python 3.7 que l'on appelle geopandas;
	  > conda create -n geopandas python=3.7   
	- Activer l'environnement geopandas que l'on vient de créer;
	  > conda activate geopandas
	- Installation forcée du package fiona (1.8.21);
	  > conda install -c conda-forge fiona
	- Installation des packages présents dans le fichier requirements.txt;
	  > pip install -r requirements.txt
	- Ouverture d'une console jupyter;
	  > jupyter notebook
