# Crayon
wip poc of something like ms paint

## Justification
Even though I have a suite of better Tools installed, (gnu imp, krita, paint.net, adobe ps, and one or two I've forgotten,) I almost always start up paint when I want to quickly make something, because paint starts up in <1s and the other tools take several times as long (with gnu imp and krita sometimes taking 20 seconds each), drops me in with a canvas, presents me with an uncluttered interface, and is intuitive to use.
But it lacks a few tools (ruler, transparency, editing selection), is kinda bad in a few spots(color palette, selecting from canvas edge, continue editing in x) and generally feels like it's a step from abandonware.
## Goals
A drawing application
- use flipchart & collage metaphor
  - casual user needs no extra thought
  - no right-click menu on canvas
  - rulers like screen scetch
  - balloon help for universal access?
- dive right in
  - startup time strictly under 5 seconds
  - no unprompted welcome dialog
  - defer loading necessary ballast
- tight scope => continue editing in x
  - slightly more useful doesn't justify slower startup or more confusing
- suitable for kids, inexperienced elders, ideally case everyone who can move a pointer around the screen
  - maybe add easy-save button for defined location and timestamp added to entered name
- may look like KidPix Free for Mac Plus if that's in line with the previous goals
- configurable via command-line parameters? (e.g. open as copy, save to location)
  - maybe also configure profiles via companion software?
  - make suitable for public installations?
- ideally for most desktop os, tablet and web, but windows has priority rn
