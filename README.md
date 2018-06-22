# Openclassroom-pdf
## Liens pdf openclassroom (pdf pas mis à jour depuis le 08/01/2013)

https://openclassrooms.com/old-courses-pdf 

### Utilisation de l'extension google chrome "data miner" pour récupérer les liens à télécharger.

![](https://github.com/ctith/Openclassroom-pdf/blob/master/2018-06-22%2012_34_08-Anciens%20PDF%20des%20cours%20-%20OpenClassrooms.png?raw=true)

![](https://github.com/ctith/Openclassroom-pdf/blob/master/2018-06-22%2012_34_24-Anciens%20PDF%20des%20cours%20-%20OpenClassrooms.png?raw=true)

![](https://github.com/ctith/Openclassroom-pdf/blob/master/2018-06-22%2012_34_45-Anciens%20PDF%20des%20cours%20-%20OpenClassrooms.png?raw=true)

On obtient une colonne avec tous les href de la page
Exporter le résultat en fichier excel .xls
![](https://github.com/ctith/Openclassroom-pdf/blob/master/2018-06-22%2012_35_17-Data%20Miner.png?raw=true)

### Sur excel
Faire ctrl+H (remplacement de caractère) et mettre "* " pour supprimer tous les caractères qui se situent avant le "http://user" qui nous intéresse

Enregistrer les liens à télécharger dans un fichier texte [pdf.txt](https://github.com/ctith/Openclassroom-pdf/blob/master/pdf.txt)

### Sur une console linux

se mettre dans le répertoire où se trouve le fichier texte et taper la commande :
```shell
wget --no-check-certificate -i pdf.txt
```
