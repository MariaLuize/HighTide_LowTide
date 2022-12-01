# Workflow para criação de Mosaicos Landsat considerando mecaîsmos de maré


Google Colab:
* (PUBLIC)00_Agregacao_boiasMarinha_1985-2019.ipynb
	- https://colab.research.google.com/drive/1qXYZ1jh--DkeFYRBoCJrnmoNxtk2-wG7?usp=sharing

* Upload to GEE of csv's created in (PUBLIC)00_Agregacao_boiasMarinha_1985-2019.ipynb
	- https://code.earthengine.google.com/?asset=users/MariaLuizeSolvedCurso/Artigo_praias/Tabuas_naoPrecessadas

* (PUBLIC)01_Boias_especificacao_status_toGEE.ipynb 
	- https://colab.research.google.com/drive/1UmPge7SQ2pKbu2ZJ7yENX_9B_hutAK1n?usp=sharing

GEE:
01_Boias_especificacao_status_toGEE.ipynb upload FeatCollections_Individual_Buoys of each year to GEE
* 00_Join_Individual_Buoys_FeatureCollection
	-https://code.earthengine.google.com/ba1275df59cdf535b98ae9955b3479cb
* 01_VisualizeGenerateMosaic_HighTide_LowTide
	-https://code.earthengine.google.com/3b616ffc16f949217a12e83f7dbd46ce
	It generates annual mosaics cloud free to be classified
* 02_Classification (for 2014 only, previous mosaics have been deleted)
	-https://code.earthengine.google.com/7f679344b644e9138f47c8a289a0c32f
