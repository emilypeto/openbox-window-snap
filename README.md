## openbox-window-snap

Patch to enable window snapping by dragging the window (aero snap) for openbox.

![Demonstration](https://i.imgur.com/tGs1Y6i.gif)

Usage:

```bash
git clone https://github.com/danakj/openbox
cp openbox-window-snap.diff openbox
cd openbox
git apply openbox-window-snap.diff
```

Then build openbox according to the instructions [here.](http://openbox.org/wiki/Help:Installing)

This works with multiple monitors or desktops.
