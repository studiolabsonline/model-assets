# Studio Labs model assets

Source geometry and published 3MF models used in [3MF QuickView](https://3mfquickview.com)
marketing, with the provenance of each one recorded.

This repository exists so a claim we publish can be checked rather than believed.

## Checking a render yourself

1. Download a `.3mf` from `models/<name>/dist/`.
2. Open it in 3MF QuickView, or any 3MF viewer you already trust.
3. Compare it to the render we published.

Your own viewer is the verification. Nothing about how the file was produced needs to be
taken on trust for that comparison to mean something.

## Models

| Model | Upstream source | License | Retrieved |
| --- | --- | --- | --- |
| [benchy](models/benchy/) | [CreativeTools/3DBenchy](https://github.com/CreativeTools/3DBenchy) | CC0 1.0 | 2026-08-16 |

## Layout

    models/<name>/source/   unmodified upstream geometry, plus UPSTREAM.md
    models/<name>/dist/     the files we publish and render from

The split is the point: `source/` is what we received, `dist/` is what we made.

## Adding a model

See [CONTRIBUTING.md](CONTRIBUTING.md). Provenance is not optional here.

## License

Upstream geometry keeps its own license, recorded per model in `source/UPSTREAM.md`.
Studio Labs' contributions in this repository, including color assignments and derived
files, are released under [CC0 1.0](LICENSE).
