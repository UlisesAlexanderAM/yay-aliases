yay-aliases
======

Adds aliases for the yay AUR helper.

Aliases
-------

### General

  * `yconf` print current yay configuration.

### Install

  * `yi` install, sync, and upgrade packages.
  * `yu` install, sync, and upgrade packages (forcibly refresh package list).
  * `yU` install packages from pkg file.
  * `yd` install all packages in current directory.

### Remove

  * `yr` remove package and unneeded dependencies.
  * `yrm` remove package, unneded dependencies, and configuration files.

### Query

  * `yq` query package information from remote repository
  * `yQ` query package information from local repository

### Search

  * `ys` search for package in the remote repository
  * `yS` search for package in the local repository

### Orphans

  * `yol` list orphan packages
  * `yor` remove all orphan packages

### Ownership

  * `yown` list all files provided by a given package
  * `yblame` show package(s) that own a specified file

### Use

If you want to use this aliases on zsh, download the file named yay-aliases.zsh and add the next line to your .zshrc:
`source <path to the file>/yay-aliases.zsh`
  

If you use zimfw you can add the following line to your .zimrc
`zmodule https://github.com/UlisesAlexanderAM/pacman/ -b main`
  
  
## Spanish translation / Traduccion en español
If you want to see the spanish version of this file, you can do it [here](README-en-español.md).
If you want to help with the translation or you have an alias you'd to add or a new funtionality; you're 
free to open an issue or make a pull request.
  

Si quieren ver la version en español de este README, pueden hacerlo [aqui](README-en-español.md).
Si quieren ayudar con la traducción o tienes un alias que te gustaria que agregara o una nueva funcionalida; 
eres libre de abrir un issue o hacer un pull request.
