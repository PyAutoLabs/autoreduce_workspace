# PyAutoReduce Workspace

Example scripts for preparing telescope observations for modeling with **PyAutoLens** and **PyAutoGalaxy**. Start with an introduction to data reduction, then explore the examples for your instrument.

## Getting Started

- **[Start with the introduction](https://github.com/PyAutoLabs/autoreduce_workspace/blob/main/scripts/start_here.py)** — follow an HST imaging reduction, from archival exposures to a dataset ready for modeling.
- **[Explore PyAutoReduce](https://github.com/PyAutoLabs/PyAutoReduce)** — find the library and installation information.
- **[Read the guides](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/guides)** — learn about target settings, noise maps and the files a reduction produces.

See [Find Your Examples](#find-your-examples) below to choose where to start.

You can read the examples without running them. Running a reduction requires the instrument’s software, network access and space for downloaded exposures; the first run can take minutes to hours.

## Find Your Examples

Examples live in `scripts/`, grouped by instrument.

| I want to… | Start here |
|---|---|
| Reduce Hubble ACS imaging | [HST ACS](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/hst_acs) |
| Reduce Hubble WFC3 ultraviolet or visible imaging | [HST WFC3 UVIS](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/hst_wfc3_uvis) |
| Reduce Hubble WFC3 infrared imaging | [HST WFC3 IR](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/hst_wfc3_ir) |
| Reduce James Webb NIRCam imaging | [JWST NIRCam](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/jwst_nircam) |
| Reduce Keck adaptive-optics imaging | [Keck NIRC2](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/keck_nirc2) |
| Prepare ALMA interferometer data | [ALMA](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/alma) |
| Download survey images for visual context | [Survey cutouts](https://github.com/PyAutoLabs/autoreduce_workspace/tree/main/scripts/surveys) |

Each instrument folder has a README explaining its examples. Reduced datasets are written to `output/`; downloaded exposures and reference files are stored in `cache/`.

Survey cutouts provide visual context around a target; they are not prepared for scientific model fitting.

## Understand Your Results

For imaging reductions, the main outputs are a science image, a noise map and a point spread function (PSF), which describes how the telescope blurs the image. A reduction record stores the settings and processing details.

The [output guide](https://github.com/PyAutoLabs/autoreduce_workspace/blob/main/scripts/guides/output_contract.py) explains these files, the different outputs for individual exposures and interferometer data, and how to load them for modeling.

## Community and Contributing

Ask questions, suggest improvements and share your work in [PyAutoLabs Discussions](https://github.com/orgs/PyAutoLabs/discussions), or chat with us on [Slack](https://join.slack.com/t/pyautolens/shared_invite/zt-2cufp4eyf-fXfgMxRGuvg~bMrI3uOAxg).

## License

See the [PyAutoReduce license](https://github.com/PyAutoLabs/PyAutoReduce/blob/main/LICENSE).
