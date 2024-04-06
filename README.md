# Drag Scroll

[![Downloads](https://img.shields.io/github/downloads/emreyolcu/drag-scroll/total.svg)](https://github.com/emreyolcu/drag-scroll/releases)

This small utility provides a toggleable drag-to-scroll mechanism for macOS.
It is especially useful with a trackball
where you can press mouse button 4 and roll the ball
to scroll through a large website or a document.

## Supported versions

As of April 2024, this utility works on macOS versions 10.9–14.0.

## Installation

You may download the binary [here](https://github.com/emreyolcu/drag-scroll/releases/download/v0.1.0/DragScroll.zip).
It runs in the background and does not interfere until mouse button 4 is pressed.
If you want it to run automatically at boot, do the following:

1. On macOS 13.0 and later, go to `System Settings > General > Login Items`;
otherwise, go to `System Preferences > Users & Groups > Login Items`.
2. Add `DragScroll` to the list.

If you want to undo the effect you may launch Activity Monitor,
search for `DragScroll` and force it to quit.
