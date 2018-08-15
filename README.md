# submodule-test

## Configuration

### Ajout des sous-modules

> Dans le repertoire du projet

Ajout du sous-module 1
> git submodule add https://github.com/ng-galien/submodule-1.git

Ajout du sous-module 2
> git submodule add https://github.com/ng-galien/submodule-2.git

Commit de l'ajout
> git commit -am 'added modules 1&2'

Enregistrement des configurations
> git push origin master

### Clone

Clone du projet avec tous les sous-modules
> git clone --recurse-submodules https://github.com/ng-galien/submodule-test.git