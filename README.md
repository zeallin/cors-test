# cors-test


<a href="tree1.glb">File Test</a>


Well you can test A-Frame dynamic GLB loading with CORS using followng code:


```

      const frame = document.createElement('a-entity');
      frame.id = 'frame';
      frame.setAttribute('gltf-model', 'https://zeallin.github.io/cors-test/tree1.glb');

      frame.object3D.scale.set(3, 3, 3);
      frame.setAttribute('place-on-wall', '');
      scene.appendChild(frame);

```
