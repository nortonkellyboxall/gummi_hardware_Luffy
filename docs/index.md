<a href="#package layout">Click here to learn about the file layout in the package</a>
------

<a href="#construction">Click here to navigate to the assembly instructions</a>
------

# Introduction
Gummi_hardware_luffy is a package that contains the files that need to be used for printing, creating the urdf. It also contains the Fusion 360 f3z document that will download the top level assembly and all the parts into your project. The current version contains the parts as of the 4th of February 2019. This package is one of many packages used for the Luffy version of the Gummi Arm. 

The packages are as follows:
- [gummi_base_luffy](https://nortonkellyboxall.github.io/gummi_base_luffy/)
- [gummi_ee_luffy](https://nortonkellyboxall.github.io/gummi_ee_luffy/)
- [gummi_head_twodof](https://nortonkellyboxall.github.io/gummi_head_twodof/)
- [gummi_interface](https://nortonkellyboxall.github.io/gummi_interface/)
- [gummi_moveit](https://github.com/nortonkellyboxall/gummi_moveit)
- [gummi_hardware_luffy](https://nortonkellyboxall.github.io/gummi_hardware_Luffy/)

Each of these packages are connected and required to be cloned or forked.

<a id = "package layout"> Package layout </a>
======

## Fusion 360 File

This folder contains the f3z document for the top level assembly. Fusion 360 was used since it is powerful enough as well as being free for students. If you prefer using another software I would recommend that you download fusion 360 and then export the assembly as a STEP file. This will be able to be opened on all CAD software.

## Luffy_STL_Files

This folder contains the individual STL files that need to be printed in order to construct the arm. If any updates are implemented on the arm, the files must be added here to replace the old files. When printing these files it is recommended that it is printed in nylon at an infil percentage of at least 20%. These parts can be printed in other materials, however, the materials properties will dictate how well it is able to handle collisions etc.

## URDF

This folder contains the specific STL files required to be used in the gummi_base_luffy, gummi_ee_luffy, and gummi_head_twodof. These STL files are sub assemblies that correspond to the links in the kinematic model. If any parts are created or updated for the arm then this folder needs to be updated and also the corresponding folders in the other packages.

<a id = "construction"> Luffy Assembly </a>
For assembly instructions go [here](http://htmlpreview.github.io/?https://github.com/mstoelen/GummiArm/blob/master/media/instructions/homepage.html) and [here](https://github.com/GummiArmCE/docs/wiki). Whilst this is an older resource it provides enough information on how to build and configure the Gummi Arm.
======


