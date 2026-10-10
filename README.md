# AR models

3D models for my AR coursework, hosted here so the Babylon.js Playground can load them over HTTPS.

## majestic_sword.glb

"The Majestic Sword of Golden Blood (Game-Ready)" by nodgerty
(https://sketchfab.com/3d-models/the-majestic-sword-of-golden-blood-game-ready-d30c32d54aca476a8e817345580c6aaa),
licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/).

Modified from the Sketchfab download: root rotation reset so the sword stands upright, textures resized from
4096 to 2048 px and stored as WebP, material alpha mode changed from BLEND to MASK.

Load it in Babylon.js with:

```js
BABYLON.SceneLoader.LoadAssetContainerAsync(
    "https://raw.githubusercontent.com/VivekRnx/ar-models/main/", "majestic_sword.glb", scene);
```
