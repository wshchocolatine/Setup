# Setup 
Le but de ce fichier et d'expliquer comment je met en place mon set-up sur les ordinateurs et d'éviter de perdre trop de temps à chercher comment tout installer. 

### OS 
Je fonctionne souvent sous dual-boot ou uniquement sur Linux. 
La première opération à faire est d'installer `Fedora`. Pour cela, il faut installer les logiciels nécessaires sur une autre machine, puis sur un clé usb. Les instructions et les téléchargements nécessaires sont disponibles [ici](https://getfedora.org/fr/workstation/download/). 

### Thèmes 
On arrive donc sur `Fedora`. C'est un environnement Gnome donc on peut installer des thèmes personnalisés. 
Pour cela, d'abord on installe l'application "Tweaks" (disponible sur l'application "Logiciels" de base). 

[Ant](https://www.gnome-look.org/p/1099856)
[Mac Os Big Sur](https://github.com/vinceliuice/WhiteSur-gtk-theme)

### Applications 
Certaines applications sont souvent carrées à installer. 
On essaie le plus possible d'éviter d'installer avec `snap` car il y a souvent des problèmes lorsque l'on importe des fichiers et avec les polices. 

- Wikipedia : disponible sous le nom de "wike" sur le magasin d'applications de base. 
- [Notion](https://snapcraft.io/notion-snap)
- [Spotify](https://snapcraft.io/spotify)
- [Discord](https://itsfoss.com/install-discord-fedora/)
- [VSCode](https://code.visualstudio.com/docs/setup/linux)
- [Obsidian](https://flathub.org/apps/details/md.obsidian.Obsidian)
- [DBeaver](https://dbeaver.io/download/)
- [Postman](https://snapcraft.io/install/postman/fedora#install)

### Dev
- [PostgreSQL](https://doc.fedora-fr.org/wiki/Installation_et_configuration_de_PostgreSQL)
- [Redis](https://computingforgeeks.com/how-to-install-redis-on-fedora/)
- [NodeJS](https://developer.fedoraproject.org/tech/languages/nodejs/nodejs.html)

### Changement de mot de passe superutilisateur 
Attention à ne pas oublier de changer le mot de passe utilisateur du superutilisateur `root` par la commande `sudo passwd root`. 
