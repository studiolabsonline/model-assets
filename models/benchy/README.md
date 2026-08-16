# 3DBenchy

The most printed 3D model there is, and a calibration boat by design, which makes it a
recognizable subject that nobody has to be introduced to.

## Source

Unmodified upstream STLs in [`source/`](source/), with license and retrieval date in
[`source/UPSTREAM.md`](source/UPSTREAM.md). Public domain (CC0) as of February 2025.

## What we made

STL carries no color at all. The 16 upstream parts are separate meshes, so each becomes one
3MF object carrying its own color, and the resulting file is genuinely multi-color rather
than a gray model painted at render time.

The color assignments are **ours**, authored by Studio Labs. They are not read from any
upstream file, because there was nothing to read.

| File | Colorway | Embedded thumbnail |
| --- | --- | --- |
| `dist/benchy-vibrant.3mf` | vibrant | yes |
| `dist/benchy-vibrant-nothumb.3mf` | vibrant | no |
| `dist/benchy-brand.3mf` | brand | yes |
| `dist/benchy-brand-nothumb.3mf` | brand | no |

The thumbnail pair is the same geometry and the same colors, differing only in whether the
package embeds a preview image. A 3MF thumbnail is optional in the format.

## A note on the colors

The vibrant colorway resembles the familiar 3DBenchy promotional look. It is our own
palette applied to a public-domain hull, and is **not** an official color scheme.
