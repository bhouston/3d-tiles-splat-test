# 3d-tiles-splat-test

Test page for rendering Gaussian splat 3D Tiles with
[3DTilesRendererJS](https://github.com/NASA-AMMOS/3DTilesRendererJS) and three.js'
`GaussianSplatGroup` from [mrdoob/three.js#34290](https://github.com/mrdoob/three.js/pull/34290).
Requires a browser with WebGPU support.

three.js is included as a git submodule (the `gs3d-group` PR branch), so clone with
submodules and then run a static server:

```
git clone --recursive https://github.com/bhouston/3d-tiles-splat-test.git
cd 3d-tiles-splat-test
npx servez
```

A sample splat tileset is loaded by default. Load another with the query parameter:

```
?url=https://example.com/tileset.json
```
