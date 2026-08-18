# liquid glass

Four glass bodies in one fragment shader. A button and, on click, three
droplets that separate from it like liquid and get swallowed back.

Everything is one spring system. Hover swells the jelly, pressing sinks
it, dragging fights an anchor spring that stiffens with distance, release
snaps back with overshoot. The droplets tear off through a smooth-union
neck that stretches and rips on its own — no keyframes anywhere.

The light is an interference field running the outline: pools that morph
while they travel. Each body shimmers on its own phase, throws its light
onto the neighbours, and the rim facing a glowing body catches exactly
the hue sent its way.

No textures, no sprites, no libraries. One shader, one file.

## Use

```
npx degit antekristo86/drops/glass glass
open glass/demo.html
```

Press D for the tuning panel.

Made with Claude Code.
