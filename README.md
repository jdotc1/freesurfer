## Structural MRI analysis and cortical surfaces

This is a development fork of [FreeSurfer](https://github.com/freesurfer/freesurfer), the Laboratory for Computational Neuroimaging's suite for processing and visualizing brain imaging data. Upstream includes cortical and subcortical segmentation, surface reconstruction, registration, and group morphometry tools, supporting workflows that connect MRI volumes with anatomical measurements.

**Contribution to review:** [PR #1485](https://github.com/freesurfer/freesurfer/pull/1485) proposes passing SynthStrip Docker arguments without an intermediate shell.

Begin with the [official FreeSurfer wiki](https://surfer.nmr.mgh.harvard.edu/fswiki) for installation and tool documentation, or the linked build guide below for source development. Original credits, support routes, and license terms are preserved. The [branch comparison](https://github.com/freesurfer/freesurfer/compare/dev...jdotc1:dev) shows this fork's `dev` branch.

---

<div align="center">
  <img src="https://surfer.nmr.mgh.harvard.edu/pub/data/tmp/brain.png">
  <p align="center">An open-source software suite for processing human brain MRI</p>
  <img src="https://travis-ci.org/freesurfer/freesurfer.svg?branch=dev">
</div>

## Introduction

FreeSurfer is a software package for the analysis and visualization of neuroimaging data from cross-sectional and longitudinal studies. It is developed by the [Laboratory for Computational Neuroimaging](https://www.martinos.org/lab/lcn) at the [Martinos Center for Biomedical Imaging](https://www.nmr.mgh.harvard.edu).

FreeSurfer provides full processing streams for structural and functional MRI and includes tools for linear and nonlinear registration, cortical and subcortical segmentation, cortical surface reconstruction, statistical analysis of group morphometry, diffusion MRI, PET analysis, and *much more*. It is also the structural MRI analysis software of choice for the [Human Connectome Project](http://www.humanconnectomeproject.org/about).

For expansive documentation on using and understanding FreeSurfer tools, please visit the [FS Wiki](https://surfer.nmr.mgh.harvard.edu/fswiki).

## Developer

Please review the [contribution guidelines](https://github.com/freesurfer/freesurfer/blob/dev/CONTRIBUTING.md) and visit our [build guide](https://surfer.nmr.mgh.harvard.edu/fswiki/BuildGuide) for step-by-step instructions on configuring and building the source code.

## Support

If you've encountered an issue or have a question about using FreeSurfer, follow these steps to get help:

  1. **Search the archives:** It is highly likely that someone else has run into the same problem before you. The fastest way to get answers is to [search the archives](https://www.mail-archive.com/freesurfer@nmr.mgh.harvard.edu) of our mailing list.

  2. **Ask a question:** [Subscribe](http://mail.nmr.mgh.harvard.edu/mailman/listinfo/freesurfer) to the mailing list and start a discussion!

If you've found a bug in the software, feel free to open an issue or submit a patch after reviewing our [CONTRIBUTING.md](https://github.com/freesurfer/freesurfer/blob/dev/CONTRIBUTING.md) documentation.

## License

Terms and conditions for use, reproduction, distribution and contribution are found in [LICENSE.txt](https://github.com/freesurfer/freesurfer/blob/dev/LICENSE.txt).
