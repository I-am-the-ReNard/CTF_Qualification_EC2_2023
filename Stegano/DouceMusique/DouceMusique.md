Le fichier à télécharger s'appelle "douce_musique.wav".

Premier réflexe, on s'assure du type de fichier dont il s'agit avec la commande ``file <nomDuFichier>`` :
![Screen de l'exécution de la commande file sur le fichier son!](assets/images/file_douce_musique.png "Exécution de la commande file sur le fichier son")

Deuxième réflexe, on regarde les métadatas du fichier pour obtenir un maximum d'informations sur celui-ci avec la commande ``exiftool <nomDuFichier>`` :
![Screen de l'exécution de la commande exiftool sur le fichier son!](assets/images/exiftool_douce_musique.png "Exécution de la commande exiftool sur le fichier son")

Qui dit fichier audio, dit souvent l'utilisation d'un outil comme sonic-visualiser pour nous permettre d'analyser le fichier :

Pour installer sonic-visualiser sur kali linux : ``apt-get install sonic-visualiser``

Ici, en affichant le spectrogramme du fichier nous obtenons le flag :
![Screen de l'exécution de l'outil sonic-visualiser!](assets/images/sonic-visualiser_douce_musique.png "Exécution de sonic-visualiser")