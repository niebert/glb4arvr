## 3D Models
This directory contains all 3D models as GLB files. The GLB files are embedden with HTML files in the root directory of  the `glb4arvr` repository.

### 3D Models for Aframe Scene
Beside geometric primitives like boxes, spheres, pyramids, ... an [Aframe scene](https://www.aframe.io) can have 3D models placed in the screne with the equirectangular image as sky. This folder contains a GLB file that is loaded into an [example 3D scene](https://niebert.github.io/HuginSample/spinosaurus_rieselfelder_aframe.html).
Sketchfab publishes 3D-Models as creative commons. One the CC-BY-4.0 models a dinosaur (Spinosaurus) is used as a 3D model on a marker. The model is called 
* "[primal carnage spinosaurus](https://skfb.ly/pswyN))" (URL: https://skfb.ly/pswyN) created by `seth the yutyrannus`.
* The 3D model is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* ***AR-Web-Demo:*** [Spinosaurus on AR-Marker](https://niebert.github.io/AR-Examples/spinosaurus_hiro_ar.html) - ***VR-Web-Demo:*** [Spinosaurus in VR](https://niebert.github.io/HuginSample/spinosaurus_rieselfelder_aframe.html)
* GLB-File: [model3d/primal_carnage_spinosaurus_small.glb](model3d/primal_carnage_spinosaurus_small.glb)
![Spinosaurus on AR-Marker](./img/spinosaurus_on_ar_marker.png)
* **(Print Marker)** Use Hiro-Marker as print out
* **(Display 3D Model in Browser)** Start [Web-Demo - Spinosaurus on AR-Marker - "Hiro"](https://niebert.github.io/AR-Examples/spinosaurus_hiro_ar.html)
* **(Marker in Camera Viewport)** Allow camera to record Hiro-Marker in Webcam.
* **(3D Model in Webpage displayed on Marker)** Dinosaur will be placed on Hiro-Marker in camera image.
* **(Coordinate System)** Hiro marker (and any other marker) defines in the asymmetric shape a coordinate system in which the objects are placed.
* **(Scaling of Object - Marker Size)** The size of the Hiro marker defines the unit length in the coordinate system. E.g. triple size of printed Hiro marker scales the objects by the factor 3. You can also scale the GLB file with a xyz scale factor in the embedding tag of the GLB file.
* **(Exchange a GLB File 1)** You can replace the used dinosaur by another GLB file just by replacing the reference to another GLB file e.g. "Walking With Dinosaurs 3D Female Gorgosaurus" (https://skfb.ly/psUII) by Jurassic Radassic is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* **(Exchange a GLB File 1)** This is a generic approach because you display just the 3D model in the GLB file, just by replacing the reference to GLB file. This is applicable to the Aframe and the AR.js files.
* **(Animations in GLB Files)** GLB files can have animations baked into the GLB file. Animation can be started and looped by an attribute in the HTML file that embeds the GLB file. `aframe-extras.js` are used to execute/start the animation in GLB file. The library is imported in the HTML file.
