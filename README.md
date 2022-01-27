
# ModOAP - Conversion de fichiers txt ou pdf vers json (segmentation des blocs de texte) 

Ce carnet propose de convertir le texte de fichiers TXT ou PDF (océrisés) contenus dans un dossier source en fichiers structurés au format JSON.

Pour chaque fichier, le résultat est un fichier au format JSON créé dans le dossier de destination, comportant le texte du fichier initial segmenté en blocs. 

Ce carnet nécessite de synchroniser un compte Google Drive.


## Utilisation

1. Ouvrir le carnet dans l'interface Google Colab [![Open In Colab](colab.svg)](https://colab.research.google.com/github/paulbin501/t1/blob/main/t1.ipynb) et se connecter à un compte Google Drive ?????????????????????

2. Lancer la première cellule et cliquer sur le lien généré pour synchroniser un compte Drive si demandé.
Cette cellule importe les bibliothèques nécessaires à l'utilisation du carnet, et connecte un compte Drive.

3. Dans la seconde cellule : 
	- spécifier le chemin vers le dossier Google Drive contenant les fichiers txt ou pdf à convertir 
	- spécifier le chemin vers un dossier Google Drive où sauvegarder le résultat
	- lancer la cellule


Consulter un tutoriel sur l'utilisation générale des carnets Colab (?????????????????????????)

