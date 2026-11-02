# Kenya Land Pressure Atlas

An interactive, decade-by-decade map (1900s to the 2020s) of the directions in which Kenya's communities have pushed, been pushed, or been held in place, with the main reason for each movement.

Open `index.html` in a browser. Pick a decade or press **Play**, filter by community with the coloured chips, and use the matrix under the map to see the main direction of pressure for every community in every decade.

- Arrows: direction (north, south, east, west and diagonals) and relative strength (1–3).
- Inward rings: pressure inside a home area (eviction back home, confinement, crowding).
- Outward rings: pressure in several directions at once.

The map is schematic. Each arrow summarises documented movement by part of a community, driven mostly by colonial land policy, settlement schemes, the land market, population growth, drought and political violence. Sources are listed at the bottom of the page.

All data lives in the `G` (communities) and `D` (decades) objects in the page script, so adding or correcting a movement is a one-line edit.

## Controls

- Sticky timeline: previous / play / next buttons, a decade slider, and tappable decade ticks. Arrow keys and the space bar also work.
- **All Kenya / Rift & West** zooms the map into the crowded western highlands.
- Tap an arrow, its number, or a reason card to highlight that one movement.
- On phones, swipe the map sideways to change decade.
