edge-blending-shader-three.js
=============================

Projector blending shader for perfect edge blending in three.js as postprocessing shader.

```javascript
var effect = new THREE.ShaderPass( THREE.EdgeBlendingShader ); 
```

I ported to Three.js the Openframeworks addon done by Jeffrey Crouse ( https://github.com/Flightphase/ofxProjectorBlend). To use multiple projections Three.js have a great method "setViewOffset" from PerspectiveCamera (http://threejs.org/docs/#Reference/Cameras/PerspectiveCamera). That it makes more easy to develop a software to render in a grid of screens. 

This library was develop develop for Google Devart(http://devart.withgoogle.com/) commission project together 'Wishing wall' by Varvara Guljajeva and Mar Canet.

