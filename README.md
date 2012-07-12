# git-flow-clone

Clone a git repo with support for the gitflow branching model.
    git flow clone <repo> [<dir>]

Everyone who ever clones a git repo that uses the gitflow model will immediately
want to:
* setup a remote tracking 'develop' branch
* remotely track all other published branches (probably)
* checkout 'develop'

## Installation

./git-flow-clone install

## Example

    $ git flow clone git@hostname.example.com:projectname
    Cloning into 'projectname'...
    Branch develop set up to track remote branch develop from origin.
    Branch feature/feat1 set up to track remote branch
    feature/feat1 from origin.
    Switched to branch 'develop'

    $ cd projectname
    $ git branch
    * develop
      feature/feat1
      master

## Todo

Handle a Gitflow repo with non-default branch names.
