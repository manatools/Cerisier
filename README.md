# Cerisier
This tool is intended to render a graphical representation of the dependencies of a set of packages of a distribution using the DNF API.

You can enter the name of a package as the root of the graph. You also click on one of the labels to set its package as the new root.

The slider allows one to set the depth of the relations.

Tool-tips are provided on hover and display information about the packages.

One needs to install Python modules bokeh using `pip3 install bokeh` or similar and `networkx`.

Launch by running `./cerisier` in the root directory of the repository.

![Browser screenshot](screen.jpg)
