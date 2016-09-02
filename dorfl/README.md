# dorfl 

This container template builds a basic python environment over the phusion/baseimage container. 
It installs a python2 and python3 interpreter via pyenv and sets up pip, setuptools and virtualenv for 
each python installed. It also creates a default virtualenv and installs some basic packages for each python. 

Exact versions of python and packages installed can be tweaked via the template context.json file prior to building. 
