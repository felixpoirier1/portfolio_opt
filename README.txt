IMAGES : Contient tous les images utilisés dans les Markdownindex : liste des index utilisé pour les comparer à nos portfolio choisi (par industrie)PROJET.ipynb : Le fichier .ipynb qui devrait être évaluéRAPPORT: Le dossier qui enregistrera tout les rapports excel que l'utilisateurs veut enregistrer (voir PROJET.ipynb pour plus d'infromation)secteur.csv : Tableau du nom des actions par secteur extrait de Yahoo Ticker Symbols - September 2017.xlsx (utilisé dans TÉLÉCHARGEUR_DE_DONNÉES.ipynb)STOCKS : Tous les fichiers de données .csv sous-divisés par secteursTÉLÉCHARGEUR_DE_DONNÉES.ipynb : Le fichier pour recréer les opérations de téléchargement de données à l’aide de YFINANCEYahoo Ticker Symbols - September 2017.xlsx : Fichier qui a aidé avec la sélection d’actions


Informations supplémentaires:

Toutes les actions sélectionnées sont transigées sur les marchés américains et furent téléchargés à l'aide du module yfinance créé par Ran Aroussi https://pypi.org/project/yfinance/

Les variables indépendantes utilisés pour produire le test de régression linéaire proviennent de la banque fédérale américaine https://fred.stlouisfed.org/



Voici les téléchargements nécessaires

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