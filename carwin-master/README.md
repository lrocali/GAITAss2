Carwin
======

A self-driving car implemented with neural networks and genetic algorithms (AI Course Project)

This project is a study (and a implementation) of neural networks potentials in a context where a 
car learns itself how to drive into a set of circuits.
Connected with the developed neural network there is a genetic algorithm based on "Darwin's natural selection law".

Requirements
------------

The entire work has been made using the Unity3D Game Engine 4.0 (http://www.unity3d.com) and Trimble Sketchup (http://www.sketchup.com).
The reason of this choice is that we needed an easy way to represent 3D models with physical properties, but there are no 
limitations to develop projects like this in other ways, languages or systems.

Usage 
-----

For non-Unity users, you can still try Carwin by opening carwin-build/carwin-build.html sample page. You only have to install the Unity Web Player.

For hackers equipped with Unity3D 4.0, open carwin-unityproj/Assets/defaultScene.unity to have full control of this project.  
The source files you are probably interested to are in Assets/Scripts/CarControl folder. 
Read __carwin-buzzoni_francesconi2012.pdf__ for more informations. Enjoy!

During the simulation you can use the following keyboard shortcuts:
* Numbers from `1` to `4` to change the track
* `UP-arrow` to enlarge the camera view

The following commands are available only through the Unity3D editor:
* `S` to save the overall best chromosome in an external file "bestchr.txt"
* `R` to restore the saved best chromosome and apply it to the current simulation (enters in SHOW MODE)

Authors
-------

We are two students at University of Bologna, Computer Science Department. 
This project belongs to the Artificial Intelligence course.

* Buzzoni Marco (marco.buzzoni2@studio.unibo.it)
* Francesconi Alessandro (alessand.francescon2@studio.unibo.it)

Credits
-------

* The original car's model and movement system was made by  Ansetfdrew Gotow (maxwelldoggums@gmail.com - http://www.gotow.net/andrew/blog/?page_id=78)
* Neural Network with Genetic Algorithm implementation is based on three main resources:
	* http://page.mi.fu-berlin.de/rojas/neural/index.html.html
	* http://www.ai-junkie.com/ann/evolved/nnt1.html
	* http://www.obitko.com/tutorials/genetic-algorithms/index.php