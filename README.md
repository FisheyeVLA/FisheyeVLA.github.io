# FisheyeVLA.github.io

Project page for **Fisheye-VLA: Decoupling Coverage and Acuity for Manipulation with a Single Fisheye Camera**.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Add the eight short videos

1. Put optimized MP4 files in `static/videos/` as `demo-01.mp4` through `demo-08.mp4`.
2. In `index.html`, replace the corresponding `.demo-slot` with:

```html
<video controls muted loop playsinline preload="metadata">
  <source src="static/videos/demo-01.mp4" type="video/mp4" />
</video>
```

For widest browser support, export H.264 video with AAC audio and the `yuv420p` pixel format.

## Update release links

- Replace the disabled **Paper soon** button in `index.html` when the paper is public.
- Replace the disabled **Code soon** button in `index.html` when the repository is public.
- Update the BibTeX journal/arXiv fields after the preprint is posted.

## Credits

The layout follows common academic project-page conventions and is visually inspired by the open-source [Academic Project Page Template](https://github.com/seemandhar/paper-template) and [Nerfies](https://nerfies.github.io/). Site-specific design and implementation are customized for Fisheye-VLA.
