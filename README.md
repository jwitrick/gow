Description
===========
This cookbook is designed to install the gow application on a windows machine.
Gow is an application that gives unix type commands to the windows command
line.

Requirements
============
This needs windows cookbooks.

Attributes
==========
default["gow"]["url"] = "https://github.com/bmatzelle/gow/releases/download/v0.8.0/Gow-0.8.0.exe"

Usage
=====

This works out of the box. All you need to do is add this recipe to the
servers run list.
