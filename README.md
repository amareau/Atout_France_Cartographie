# Prérequis :
- Ouvrir une console anaconda prompt;
- Se placer dans le chemin où se trouve le fichier 1_Entretien technique.ipynb;
- Taper les commandes suivantes :
	- Création d'un environnement python que l'on appelle geopandas;
	  > conda create -n geopandas python   
	- Activer l'environnement geopandas que l'on vient de créer;
	  > conda activate geopandas
	- Télécharger et placer dans le chemin courant les fichiers *GDAL-3.4.2-cp310-cp310-win_amd64.whl* et *Fiona-1.8.21-cp310-cp310-win_amd64.whl* ;
	- Lancer les commandes ci-dessous (explications : voir sources 1, 2 et 3) ;
	  > pip install GDAL-3.4.2-cp310-cp310-win_amd64.whl
	  > pip install Fiona-1.8.21-cp310-cp310-win_amd64.whl
	- Installation de geopandas ;
	  > pip install geopandas
	- Installation de jupyter notebook;
	  > pip install notebook
	- Installation de jupyter lab;
	  > pip install jupyterlab
	  > 

	- Installation du package fiona (1.8.21) avec conda-forge;
	  > conda install -c conda-forge fiona==1.8.21
	- Installation des packages présents dans le fichier requirements.txt;
	  > pip install -r requirements.txt
	- Ouverture d'une console jupyter;
	  > jupyter notebook
	- Suivre le reste des étapes de la source 4 (optionnel)

# Sources :
1 - https://stackoverflow.com/questions/50876702/cant-install-fiona-on-windows
2 - https://www.lfd.uci.edu/~gohlke/pythonlibs/#gdal
3 - https://www.lfd.uci.edu/~gohlke/pythonlibs/#fiona
4 - https://medium.com/@apremgeorge/using-conda-python-environments-with-spyder-ide-and-jupyter-notebooks-in-windows-4e0a905aaac5


# Auteur :
* MAREAU Alexis
