# splash-theme-bolo 
Thème du musée Bolo lors du démarrage du noyau.

## Installation
(Pour RPi)
Il faut avoir les paquets suivant installé:
```bash
$ sudo apt-get install plymouth plymouth-themes
```

Télécharger le thème dans le dossier /usr/share/plymouth/themes/:
```bash
$ git clone https://github.com/museebolo/splash-theme-bolo
$ sudo mv splash-theme-bolo /usr/share/plymouth/themes/bolo
```

Pour sélectionner le thème:
```bash
sudo plymouth-set-default-theme bolo
```
