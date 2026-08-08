# depth scroll

Cards on the Z axis. Scroll flies through the stack.

The physics: direct follow while scrolling, momentum with friction on release, then a critically damped spring lands on the nearest card. Velocity never jumps, that is what makes it feel physical instead of eased.

CSS 3D transforms, vanilla JS, no dependencies.

## use

Open `demo.html`. Put your content in the plates. All feel parameters sit in one `P` object at the top.

Made with Claude Code.
