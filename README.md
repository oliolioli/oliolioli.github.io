# 3D model of Bern, Switzerland

The altitude profile was sourced from [OpenStreetMap](https://www.openstreetmap.org) and integrated into a [Blender](https://www.blender.org) model. 
Additionally, building height data was included, allowing the 3D structures to be accurately placed on the terrain.

To enhance realism, [satellite images from NASA](https://worldview.earthdata.nasa.gov) were mapped onto the 3D model and carefully scaled to align as accurately as possible.

The entire 3D model was exported from Blender in a format compatible with [Three.js](https://threejs.org), ensuring smooth rendering in a web environment.

Can you find the seagull? 🕊️


### How to run this code??

The module responsible for automatically publishing your local content to GitHub Pages is .

```
.\npx serve
```

### How to publish automatically to GitHub Pages?
```
npm install gh-pages --save-dev
```
(Keeping it in devDependencies keeps the production build clean and lightweight.)

```
npm run deploy
```

Builds your project (if a build step exists) and pushes the necessary files to GitHub Pages.

## Inspiration / materials
Adding a [3D model](https://youtu.be/lGokKxJ8D2c) to a website using THREE.JS
