
<p align="center">
<img src='https://user-images.githubusercontent.com/11960872/37533324-cfa3e516-2941-11e8-99a9-96a1e20c80a3.jpg' />
</p>


## Features

Here are the main features of the library:

* face detection,
* face tracking,
* face rotation detection,
* mouth opening detection,
* multiple faces detection and tracking,
* very robust for all lighting conditions,
* video acquisition with HD video ability,
* mobile friendly,
* interfaced with 3D engines like THREE.JS, BABYLON.JS, A-FRAME,
* interfaced with more accessible APIs like CANVAS, CSS3D.




## Demonstrations

### Included in this repository

These demonstration are included in this repository. So they are released under the [FaceFilter licence](#license). You will probably find among them the perfect starting point to build your own face based augmented reality application:

* BABYLON.JS based demos:
  * Boilerplate (displays a cube on the user's head): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/babylonjs/cube/)

* THREE.JS based demos - [specific README about THREE.js based demo problems](demos/threejs/):
  * Boilerplates:
    * Boilerplate (displays a cube on the user's head): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/cube/)
    * Same boilerplate but using `dist/NNClight.json` as neural net: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/cubeNNClight/)
    * Same boilerplate but using `dist/NNCwideAngles.json` as neural net: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/cubeNNCwideAngles/)
    * Boilerplate with ES6 instead of ES5: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/cubeES6/)
    * Multiple face tracking: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/multiCubes/)
    * GLTF fullscreen demo with HD video: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/gltf_fullScreen/)
    * Boilerplate with 2 canvas: 1 for FaceFilter and 1 for THREE.JS (not recommended)
    
  
  * AR 3D demos:
    * Daft Punk (put the iconic helmet): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/daft_punk/)
    * Star Wars: Darth Vader: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/star_wars/)
    * Harry Potter (say "Lumos!"): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/harry_potter/)
    * Halloween Spiders (you've got a spider in your mouth): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/halloween_spider/)
    * Werewolf (turn yourself into a werewolf): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/werewolf/)
    * Angel/Demon (discover who of the angel or demon will win in this animated scene): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/angel_demon/)
    * Anonymous mask and video effect: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/anonymous/)
    * Rupy Motorcycle Helmet VTO: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/rupy_helmet/)
    * Dog: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/dog_face/)
    * Butterflies animation: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/butterflies/)
    * Clouds above the head: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/cloud/)
    * Casa-de-Papel mask: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/casa_de_papel/)
    * Miel Pops glasses and bees: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/miel_pops/)
    * Football makeup: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/football_makeup/)
    * Tiger face filter with mouth opening detection (strong WTF effect): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/tiger/)
    * Fireworks - particules: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/fireworks/)
  
  * face painting or deformation:
    * Face deformation: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/faceDeform/)
    * Face cel shading: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/celFace/)

  * demos linked with tutorials:
    * Luffy's Hat: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/luffys_hat_part2/)
    * Statue Of Liberty: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/multiLiberty/)
    * Matrix: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/matrix/)

  * misc:
    * Head controlled navigation: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/threejs/headControls/)
    * Glasses virtual try-on: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/threejs/VTO/)

* A-FRAME based demos:
  * Boilerplate (displays a cube on the user's head): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/aFrame/cube/)
  
* CSS3D based demos:
  * Boilerplate (displays a `<DIV>` element on the user's head): [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/CSS3D/div/)
  * Comedy glasses demo: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/CSS3D/comedy-glasses/)

* Canvas2D based demos:
  * Draw on the face with the mouse: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/canvas2D/faceDraw/)
  * 2D face detection and tracking - 30 lines of code only !: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/canvas2D/faceTrack/)
  * 2D face detection and tracking from a video file instead of webcam video: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/canvas2D/fromVideoFile/)

* CESIUM.JS based demos:
  * 3D view of the Earth with head controlled navigation: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/cesium/headControls/)

* Face replacement demos:
  * Insert your face into portrait art painting or film posters: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceFilter/demos/faceReplacement/image)
  * Insert your face into an animated gif: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceReplacement/gif)
  * The traditional faceSwap, fullscreen and with color correction: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/faceReplacement/faceSwap/)

* Head motion control:
  * PACMAN game with head controlled navigation: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/pacman/)
  * Head controlled mouse cursor: [live demo](https://bruce0418.github.io/jeelizFaceFilter/demos/headCursor/)



[comment]:![giphy-downsized-large](https://user-images.githubusercontent.com/11960872/37475622-6a602cf6-2873-11e8-83f0-134b6c1ba666.gif)






