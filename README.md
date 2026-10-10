# EDUmetaverse People Maker

Single-file, offline low-poly person generator for building characters for worlds.

- **index.html** – the People Maker. Pose with draggable joints (IK), pick a preset, male/female,
  12 hair styles, clothing colours and an EDUmetaverse shirt logo, then export a rigged, skinned GLB
  (about 0.3 MB, limit 1 MB) with optional **Idle, Walk, Run and Wave** animation clips.
- **viewer.html** – the Character Viewer, built on the [PlayCanvas engine](https://github.com/playcanvas/engine).
  Drop in a GLB to check it in a second engine: triangles, skin joints, size, clip list, and
  crossfaded idle / walk / run playback.

Open either file in a modern browser. No build step. `viewer.html` loads the bundled engine from `vendor/`
(PlayCanvas v2.22.4, MIT licence in `vendor/PLAYCANVAS_LICENSE.txt`).

`edumetaverse_logo_atlas.png` is the logo texture embedded in the maker, kept here for reference.
