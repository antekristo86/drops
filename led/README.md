# led panel

The off-state of an LED wall. Uniform dim dot grid, per-LED shimmer, the wall wakes up near your cursor.

One fragment shader. No textures, no dependencies.

## use

Open `demo.html`. `uLed` sets the pixel pitch. The wake radius lives in the `exp(-d * d * 26.0)` falloff.

Made with Claude Code.
