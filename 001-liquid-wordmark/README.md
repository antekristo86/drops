# liquid wordmark

A wordmark that liquefies under the cursor. Plain WebGL, one file, no dependencies.

The SVG paths become a texture. A fragment shader pushes pixels along the cursor's velocity trail. At rest it breathes. Chromatic split only under motion.

## use

Open `demo.html`. Swap the `paths` array for your own SVG path data, adjust the viewBox numbers in `drawWordmark`.

Made with Claude Code.
