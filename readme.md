Commands for deploying the repository: 
git init 
git clone https://github.com/ft2063/3D_GreenWebsite.git
cd 3D_GreenWebsite
npm install     
npm run dev   

Project Overview: 

This is a prototype 3d website touching the issue of global warming. It is based on three.js, a technology for developing immersive and interactive 3d websites. The aim of the website is to illustrate simply and with interactive models some of the issues related to global warming. This constitutes the first attempt with the library of 3js. The principles of 3js are similar to p5.js hence understanding 3js code was intuitive and fast. However, looking forward, more time is required to create a 3d website that is more immersive and realistic. 
Project Characteristics and Workflow: 
The following techniques were to be learned in order for me to create this project from the coding perspective. From the official documentation, I learned how to set up a basic scene with objects and a camera, and I played with some examples from the official examples by threejs.org. For the set up of the Three.js project, I learned how to import specifically 3d objects from Blender by exporting objects in glb format. In addition, the Vite project setup is a quick way to set up the threejs environment running. 
Three Js Resources: 
Threejs.org official Documentation: https://threejs.org/docs/
Threejs.org official Examples: https://threejs.org/examples/
Import gltf object from Blender into three.js: https://youtu.be/WBe3xrV4CPM
Vite project setup for three.js and deployment: https://youtu.be/2x9AuM6xpxg
Furthermore, In order to prepare the 3d models I used Blender, and especially mastered how to bake textures to the 3d object so that it is exported glb format with colors and textures and does not display black in the 3dModel Viewer. The 3d Model Viewer can test the different 3D models before importing them into 3js. I also learned how to create 3d models from an image and how to generate terrain for the purpose of model creation. Models were often modified in size (scaled down to 18px radius), and location, and many of the vertices were modified with the edit mode of Blender. The animation was added using timeframes.
Blender Resources:
Texture Baking for glb model creation: https://youtu.be/2sgKu0bKUwU
Model Viewer Testing: https://www.youtube.com/watch?v=45-mJdjE9O4&t=1s
Create 3d object from 2d image (used for graph): https://youtu.be/jRa-wfixv3w
Terrain Creation with ANT plugin, Blender: https://youtu.be/y7bH2bXKyTk
Terrain Texture Landscape by steepness: https://youtu.be/ksZbiYR3WQ4
Imported models
Camelia City: https://free3d.com/3d-model/camellia-city-38170.html
Tornado: https://3dexport.com/free-3dmodel-comet-and-hurricane-429830.html
Earth: https://3dexport.com/free-3dmodel-free-earth-planet-all-format-297833.html
