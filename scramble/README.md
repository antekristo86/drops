# scramble scroll

Text resolves out of flickering glyphs on the way into the viewport and
dissolves back into them on the way out. A directional front sweeps each
line: ahead the original, at the front a scrambling glyph, behind it
nothing. Fully reversible, the scroll position is the only clock.

Glyphs keep their slot via non-breaking spaces, so nothing ever reflows.
No libraries.

## Use

```
npx degit antekristo86/lab/scramble scramble
open scramble/demo.html
```

Swap the lines in `LINES`.

Made with Claude Code.
