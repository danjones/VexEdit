# VexEdit#
A tool for creating and editing [Vex Flow](http://www.vexflow.com "VexFlow") music notation.

###Cloning###
The vexflow project contains 2 submodules, which need to be initialized. With version 1.6.5 of git and later, you can do this at the same time as cloning the project with:

    git clone --recursive git://github.com/danjones/VexEdit.git

For older versions of git, use:

    git clone git://github.com/danjones/VexEdit.git
    cd lib/vexflow
    git submodule update --init
    cd ../backbone
    git submodule update --init
