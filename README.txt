IMAGES�: Contient tous les images utilis�s dans les Markdownindex : liste des index utilis� pour les comparer � nos portfolio choisi (par industrie)PROJET.ipynb�: Le fichier .ipynb qui devrait �tre �valu�RAPPORT: Le dossier qui enregistrera tout les rapports excel que l'utilisateurs veut enregistrer (voir PROJET.ipynb pour plus d'infromation)secteur.csv�: Tableau du nom des actions par secteur extrait de Yahoo Ticker Symbols - September 2017.xlsx (utilis� dans T�L�CHARGEUR_DE_DONN�ES.ipynb)STOCKS�: Tous les fichiers de donn�es .csv sous-divis�s par secteursT�L�CHARGEUR_DE_DONN�ES.ipynb�: Le fichier pour recr�er les op�rations de t�l�chargement de donn�es � l�aide de YFINANCEYahoo Ticker Symbols - September 2017.xlsx�: Fichier qui a aid� avec la s�lection d�actions


Informations suppl�mentaires:

Toutes les actions s�lectionn�es sont transig�es sur les march�s am�ricains et furent t�l�charg�s � l'aide du module yfinance cr�� par Ran Aroussi https://pypi.org/project/yfinance/

Les variables ind�pendantes utilis�s pour produire le test de r�gression lin�aire proviennent de la banque f�d�rale am�ricaine https://fred.stlouisfed.org/



Voici les t�l�chargements n�cessaires

pip install pandas
pip install seaborn
pip install matplotlib
pip install numpy
pip install pandas-datareader
pip install statsmodels
pip install XlsxWriter
pip install urllib
pip install beautifulsoup4
pip install fredapi

pip install -i https://pypi.anaconda.org/ranaroussi/simple yfinance
pip install yfinance --upgrade --no-cache-dir