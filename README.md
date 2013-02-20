
Metamaquina2Beta
================

Metamaquina 2 - fully parametric 3D printer (Beta version)

[![A photo of the Metamaquina2Beta 3d printer](http://metamaquina.com.br/site/wp-content/themes/ifeaturepro/includes/landing-page/img/header.jpg)]

Manufacturing Instructions
==========================

This is a 3d printer project that is completely designed using the parametric CAD tools
 provided by OpenSCAD. In order to deal with this source code you'll need to install OpenSCAD,
following the instructions at: www.openscad.org

The main structure of the machine is built using lasercut MDF panels. The curves for lasercutting 
can be exported to DXF by rendering the lasercutter_panel*.scad files. Open each of these files 
in OpenSCAD, press F6 (to compile) and then click Design->Export DXF. The resulting DXF files
can be used to cut 6mm thick MDF sheets (or you can change the thickness in the source if you 
plan to work with some other materials).

The complete 3D model of the machine is described by the Metamaquina2Beta.scad file. Open is in 
OpenSCAD and press F5 to render it.

[![An OpenSCAD rendering of the Metamaquina2Beta 3d printer](https://github.com/Metamaquina/Metamaquina2Beta/master/img/MM2Beta.png)]

Hacking the code
================
Feel free to send us pull requests at https://github.com/Metamaquina/Metamaquina2Beta
 if you make any change to this design that you consider worth sharing with us.

happy hacking,
Felipe Sanches
R&D director at Metamaquina.com.br


