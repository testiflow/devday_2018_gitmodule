Test project for git submodule.

Cloning this project
--------------------

To clone this project, do the following:

`git clone https://github.com/testiflow/devday_2018_gitmodule`

Note that the submodule folder will be there, but it will not be filled.  
Submodules are not cloned automatically when cloning a super project.

Initialize and update the submodule
-----------------------------------

`git submodule init`   (just the first time, for initializing)  
`git submodule update`   (update the submodule to the commit required by the super project)

Submodule update can be performed recursively for cases where a submodule contains other submodules itself.

`git submodule update --recursive`

View status of submodules
-------------------------

`git submodule status`

