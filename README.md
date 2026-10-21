# HelioFITS suite

Desktop software for looking at solar and heliospheric imagery, by Chris R. Gilly
(NorthWest Research Associates). This repository is the suite's umbrella: it holds no
code of its own. It describes the programs, says how to cite them, and gives the suite a
citable DOI on Zenodo that links to each program's own DOI.

## Programs

| Program | What it does | Repository | License |
|---|---|---|---|
| HelioFITS | Teaches macOS Finder and Quick Look to read solar FITS files: thumbnails in the right colormap, an interactive spacebar preview with pixel values and helioprojective coordinates, and Spotlight-searchable header fields. | [GillySpace27/HelioFITS](https://github.com/GillySpace27/HelioFITS) | BSD-2-Clause |
| HelioFITS Studio | A desktop viewer for coronagraph and wide-field imagery: an unofficial fork of JHelioviewer that adds PUNCH and native LASCO loading, the Helioradial projections, the RHEF filter, CME tracking and point cloud layers. | [GillySpace27/HelioFITS-Studio](https://github.com/GillySpace27/HelioFITS-Studio) | MPL-2.0 |
| Heliogram | A companion app for public outreach, museums and displays. It shares the suite's imagery but depends on none of the other programs, and none depend on it. | not yet public | |

Each program is released, versioned and archived on its own. Each has its own Zenodo
DOI, and this suite record lists them as its parts.

## Citing

Please cite:

- **The suite**, with the DOI on this repository's Zenodo record. [CITATION.cff](CITATION.cff)
  has the details, and GitHub's "Cite this repository" button turns it into APA or BibTeX.
- **Each program you used, at the version you used.** Every program's README has its own
  Citing section and version DOI.
- **The methods behind what you show.** HelioFITS Studio is built on JHelioviewer
  (Müller et al. 2017, *Astronomy & Astrophysics* 606, A10,
  https://doi.org/10.1051/0004-6361/201730893). The RHEF filter is described in
  Gilly & Cranmer (2025), *Solar Physics* 300, 174,
  https://doi.org/10.1007/s11207-025-02578-x.

## License

The text and metadata in this repository are under [CC-BY-4.0](LICENSE). Each program
keeps its own license, listed above and in its repository.
