# Glyph Matter

A browser tool for generative, three-dimensional type. Open `index.html` in any modern browser (it needs an internet connection for Three.js and Google Fonts).

The text is drawn with a Google Font, sampled into a distance field, and that field drives six forms:

- **Inflate**: the letters as a pressurised balloon
- **Relief**: an embossed or debossed sheet (use negative depth to deboss)
- **Voxels**: instanced cubes, spheres, columns, rings or spikes
- **Particles**: a volumetric point cloud
- **Contours**: scanline terrain
- **Slices**: stacked, rotated layers

On top of the forms you get noise, waves, twist, bend, shear, scatter and tumble; physically based materials (chrome, gold, glass with dispersion, iridescent, clay, gloss plastic, velvet, toon, normals, wireframe); and scene controls for the backdrop, key light, exposure, and a lens slider that does a dolly zoom.

**Texture.** Map your own image onto the letters (choose a file or drop one on the stage), or use a generated pattern: marble, holographic, halftone, stripes or cells. A texture can colour the surface, raise it as a bump map, or do both.

**Motion.** Every animation loops seamlessly over the loop length you set. Letters can animate one by one (ripple, depth march, swing, spin, flip, pulse, burst apart), each delayed slightly after the last.

**Sound.** Load a short clip (music, dialogue, or a video with sound) and the type reacts to it. The tool tracks loudness, bass, mids, highs and beats, and each can drive depth, size, noise, wave, twist, bend, scatter, tumble, letter motion, bloom, colour fringe, grain or brightness. On each beat it can flash, kick the camera, make the letters jump, step the animation, or switch to the next word from a list you write. Presets cover the common setups: Pulse, Liquid, Glitch, Speech and Word cycle. A credit line (for example "Music: Artist — Track") shows on screen and is burned into every export. Choose "Whole sound clip" under Export to record a video of the full clip with its audio.

The **Simple** view at the top of the panel hides the advanced controls.

**Effects.** Bloom, depth of field, chromatic aberration, film grain and vignette.

**Export.** Save a PNG, a looping GIF (encoded in the browser) or an MP4/WebM video of exactly one loop, framed as 16:9, 1:1, 4:5 or 9:16. With Orbit speed on, the camera makes one full turn per loop.

You can browse any Google Font by name. "Settings JSON" lets you copy and paste a design, and "Snapshot" renders a PNG.
