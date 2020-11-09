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
