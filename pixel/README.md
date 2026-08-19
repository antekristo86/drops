# pixel scroll

Images materialise out of pixel blocks at the bottom of the viewport.
Each cell pops in as an opaque block, then sharpens as it rises, with
per-cell jitter so the wavefront stays organic. The scroll is the
animation, nothing is keyframed.

One fullscreen WebGL canvas draws every image; the DOM only provides
the scroll and the layout. No libraries.

## Use

```
npx degit antekristo86/drops/pixel pixel
open pixel/demo.html
```

Swap the images in `img/`.

Made with Claude Code.
