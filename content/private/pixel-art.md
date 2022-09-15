# Pixel art

- Grass
    
    - [x] Basic grass
    - [x] Flowers
    - [x] Instance materials
    - [ ] Different shades
    - [ ] Wind
    - [ ] Shading → better shading position
    - [ ] Multithread → heightmap texture !


- [ ] Shadow dithering …
- [ ] Linear additive lught
- [ ] Normal direction manipulation via shader (coherent noise)
- [ ] New models and materials
- [ ] Better palettes
- [ ] float4 to fixed4

   
- Water
    - [ ] Edges - normals
    - [ ] Waves
    - [ ] Specular / lighting
    - [ ] Refraction
- Edge highlights
    - impl
        haha welcome to the struggle :) yes the coveted single pixel outline shader is quite a challenge to reign in. I think one key insight I can give is that since the models are low poly and faces are flat, each pixel can predict neighbour pixel depths based on its own depth and normal, the threshold you want to set for external outlines is for points whose depth is greater than the depth and normals their neighbours extrapolate to.
        The internal convex outlines are just black magic unfortunately. I developed the filter on cubic objects (90 degree edges) oriented in various angles and tweaked numbers and added factors until it stabilized. it's not a symmetric filter.
        i originally also had a filter for internal concave outlines but never got them to play nice. It was eventually dropped entirely.

    - [ ] Depth and normals
    - [ ] Lighting
    - [ ] Colour

- Clouds
    - [ ] Coverage
    - [ ] cutoff
    - [ ] Day/night cycle

- General shader work
- Emission lighting
- Moonlight
    - Moon rays
- Models
    - [ ] Lots
    - [ ] Textures materials
        - [ ] Mapping
        - [ ] Lighting
- Character
    - [ ] Material/textutres
    - [ ] Model
    - [ ] Animations
    - [ ] Camera controller
        - [ ] Movement
        - [ ] Rotation via mouse tooo
- Dirt
    - [ ] Material
    - [ ] Texuture
    - [ ] Normal texture
- Special shaders
    - [ ] HDR + bloom
    - [ ] specular reflection, brdf
    - [ ] fog
- Terrain authoring
- Godrays
- Trees
- Line shader
- Orthographic vs perspective
- Render pipeline code maintenance