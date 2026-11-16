# Sycritters 3D

Generate an 8×8 Sycritter from a seed and explore it as an interactive voxel creature. Customize its colors, shape, eyes, and accessories, then share a link to the result.

[Open the playground](https://publicknowledgestudio.github.io/sycritters-3d/)

## Run locally

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open [the playground](http://127.0.0.1:4173/). The 3D view uses WebGL 2 and loads a pinned version of Three.js from jsDelivr. The app has no build step.

- Pick a creature from **The Wall**, enter a **Seed**, or select **Surprise me**.
- Drag the 3D preview or focus it and use the arrow keys to orbit. Use **Scale** to resize the main preview.
- Select **Mic** to let the creature react to your voice. Audio is analyzed in the browser. Allow microphone access on localhost or HTTPS.
- Open **Motion** to choose an animation, preview a sound cue, or enable **Auto sounds**.
- Open **Share** to copy a link. Switch to **Pixel** to download a PNG, SVG, or sprite sheet.

## Composer demo

[Open the composer demo](https://publicknowledgestudio.github.io/sycritters-3d/critter-test/) to interact with a pixel critter that follows your cursor and reacts as you type.

## Run the tests

```sh
node --test test/*.test.mjs
```
