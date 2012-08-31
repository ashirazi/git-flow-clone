# git-flow-clone

Clone a git repo with support for the gitflow branching model.

    git flow clone [-p] <repo> [<dir>]

Everyone who ever clones a git repo that uses the gitflow model will immediately
want to:
* setup a remote tracking "develop" and "master" branches
* initialize the repository as a Gitflow repo

## Installation

Working on a homebrew installation. Otherwise

    $ make install

## Example

    $ git flow clone git@hostname.example.com:projectname
    Cloning into 'projectname'...
    ...
    Branch develop set up to track remote branch develop from origin.
    Using default branch names.
    ...
    Gitflow repo cloned to projectname

    $ cd projectname
    $ git branch
    * develop
      master

## Todo

Let me know how it's working for you.
