# HelioFITS Suite

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23524598.svg)](https://doi.org/10.5281/zenodo.23524598)
[![License](https://img.shields.io/github/license/GillySpace27/HelioFITS-suite?style=flat)](LICENSE)

> **The HelioFITS suite**
> - [HelioFITS Peek](https://github.com/GillySpace27/HelioFITS-Peek): solar FITS thumbnails and previews in macOS Finder and Quick Look.
> - [HelioFITS Studio](https://github.com/GillySpace27/HelioFITS-Studio): a desktop viewer for coronagraph and wide-field solar imagery, forked from JHelioviewer.
> - [HelioFITS Suite](https://github.com/GillySpace27/HelioFITS-suite): how the programs fit together, with one DOI to cite them all.

Desktop software for looking at solar and heliospheric imagery, by Gilly
(NorthWest Research Associates, [gilly.space](https://gilly.space/heliosoftware/)).
This repository is the suite's umbrella: it holds no code of its own. It describes the programs, says how to cite them, and gives the suite a
citable DOI on Zenodo that links to each program's own DOI.

## Programs

| Program | What it does | Repository | License |
|---|---|---|---|
| HelioFITS Peek | Teaches macOS Finder and Quick Look to read solar FITS files: thumbnails in the right colormap, an interactive spacebar preview with pixel values and helioprojective coordinates, and Spotlight-searchable header fields. | [GillySpace27/HelioFITS-Peek](https://github.com/GillySpace27/HelioFITS-Peek), [doi:10.5281/zenodo.23749496](https://doi.org/10.5281/zenodo.23749496) | BSD-2-Clause |
| HelioFITS Studio | A desktop viewer for coronagraph and wide-field imagery: an unofficial fork of JHelioviewer that adds PUNCH and native LASCO loading, the Helioradial projections, the RHEF filter, CME tracking and point cloud layers. | [GillySpace27/HelioFITS-Studio](https://github.com/GillySpace27/HelioFITS-Studio), [doi:10.5281/zenodo.23541893](https://doi.org/10.5281/zenodo.23541893) | MPL-2.0 |
| IDL_RHEF | The Radial Histogram Equalizing Filter (RHEF) for solar images, written in IDL. A library, not a desktop app. | [GillySpace27/IDL_RHEF](https://github.com/GillySpace27/IDL_RHEF), [doi:10.5281/zenodo.17226414](https://doi.org/10.5281/zenodo.17226414) | MIT |
| Heliogram | A companion app for public outreach, museums and displays. It shares the suite's imagery but depends on none of the other programs, and none depend on it. | App public at [gilly.space/heliogram](https://gilly.space/heliogram/); source private | |

Each program is released, versioned and archived on its own. Each public program has its
own Zenodo DOI, and this suite record lists the desktop programs as its parts.

## Citing

Please cite:

- **The suite**: Gilly, C. R. (2026), *HelioFITS Suite*, Zenodo,
  https://doi.org/10.5281/zenodo.23524598. [CITATION.cff](CITATION.cff) has the details,
  and GitHub's "Cite this repository" button turns it into APA or BibTeX.
- **Each program you used, at the version you used.** Every program's README has its own
  Citing section and version DOI.
- **The methods behind what you show.** HelioFITS Studio is built on JHelioviewer
  (Müller et al. 2017, *Astronomy & Astrophysics* 606, A10,
  https://doi.org/10.1051/0004-6361/201730893). The RHEF filter is described in
  Gilly & Cranmer (2025), *Solar Physics* 300, 174,
  https://doi.org/10.1007/s11207-025-02578-x.

```bibtex
@software{gilly_heliofits_suite,
  author    = {Gilly, Chris R.},
  title     = {{HelioFITS Suite}},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.23524598},
  url       = {https://doi.org/10.5281/zenodo.23524598}
}
```

## License

The text and metadata in this repository are under [CC-BY-4.0](LICENSE). Each program
keeps its own license, listed above and in its repository.
