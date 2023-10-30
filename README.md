# docker-exe1
Dans une commande docker run

* vous devez etre en interactif et avec un tty pour le display

* le container doit etre nommé myalpes

* dans cette commande creer un volume /MountPoint
* image doit etre alpine

* passer la commande /bin/ash
  
` docker -it --name myalpes -v /MountPoint alpine /bin/ash`

Ensuite a l'interieur du container  
* creer un fichier test.py
* et inserez le texte "WARNING: ret pointer is null"

  `touch test.py`
  
  `echo "WARNING: ret pointer is null" > test.py`

A partir de ce container créer une image nommée  myalpine:v12.
