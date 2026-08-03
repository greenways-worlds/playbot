# Playbot

A Greenways world demonstrating PlayCanvas streamed SOG loading through
`lod-meta.json` and its repository-relative resources.

Open it in Hodos with:

```text
https://github.com/greenways-worlds/playbot
```

## Studio touchpoint

The world declares an `Open Studio` touchpoint near Playbot using the Hodos
`:ui/dom-surface` protocol. Activating it opens the trusted browser-native music
Studio while the Hara session carries project, track, clip, transport, history,
and active-surface state.

From Studio, local recordings can be imported, arranged and edited. A complete
track or individual clip can then be dragged back onto the Playbot world. Hara
creates the spatial-source record and the browser projects it through Web Audio
HRTF panning at the resolved world position.

The touchpoint is ignored safely by older viewers that only understand the SOG
layer.

## Attribution

The model “PLAYBOT” was created by Stéphane Agullo and is redistributed under
CC BY 4.0. See [`ATTRIBUTION.md`](ATTRIBUTION.md) for the pinned upstream source
and integrity information.
