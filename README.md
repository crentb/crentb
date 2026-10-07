## Cameron Renteria, PhD

**Engineer | AI/ML-accelerated computational science | CI/CD and DevSecOps for research software**

AI/ML-accelerated pipelines for experimental and imaging data, from synchrotron tomography and computer vision to multimodal materials measurements and finite-element design optimization, delivered as tested, secure, citable software.

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/crentb/agentic-bioinspired-cad"><img src="https://raw.githubusercontent.com/crentb/agentic-bioinspired-cad/main/docs/figures/generator_families.png" alt="agentic-bioinspired-cad: a Bouligand coupon, a woven cubic lattice and an enamel decussation lattice from its three generator families"></a><br><sub><b>agentic-bioinspired-cad</b>: text-to-CAD design loop with print, FEA and fracture checks</sub></td>
    <td width="50%" valign="top"><a href="https://github.com/crentb/ct-segmentation-toolkit"><img src="https://raw.githubusercontent.com/crentb/ct-segmentation-toolkit/main/docs/figures/ct_segmentation_pipeline.png" alt="ct-segmentation-toolkit pipeline: an image stack, optional Noise2Inverse denoising, three segmentation routes chosen by label availability, and per-pixel labels"></a><br><sub><b>ct-segmentation-toolkit</b>: denoising and segmentation of CT image stacks</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/crentb/biomimetic-lattice-pipeline"><img src="https://raw.githubusercontent.com/crentb/biomimetic-lattice-pipeline/main/docs/figures/pipeline_overview.png" alt="biomimetic-lattice-pipeline overview: synchrotron micro-CT and deep-learning PIV of enamel mapped to CAD, finite-element analysis and a printed lattice, with an Optuna optimization loop"></a><br><sub><b>biomimetic-lattice-pipeline</b>: synchrotron micro-CT of enamel to printed lattices</sub></td>
    <td width="50%" valign="top"><a href="https://github.com/crentb/som-multimodal-datareduction"><img src="https://raw.githubusercontent.com/crentb/som-multimodal-datareduction/main/docs/figures/jmbbm2022_fig6_som_heat_maps.jpg" alt="Self-organizing-map heat maps of the chemical and mechanical properties of old human enamel, with k-means zones (Figure 6 of Renteria et al., JMBBM 2022)"></a><br><sub><b>som-multimodal-datareduction</b>: self-organizing maps of multimodal materials data, from <i>J. Mech. Behav. Biomed. Mater.</i> 129, 105147 (2022), Special Issue: New Frontiers in Applications of Artificial Intelligence and Machine Learning in Biomaterials, Organs and Tissues</sub></td>
  </tr>
</table>

### Research software

| Package | Scope | Archive and release |
|:--|:--|:--|
| [**ct-segmentation-toolkit**](https://github.com/crentb/ct-segmentation-toolkit) | Supervised (U-Net), unsupervised, and label-free (self-organizing map) segmentation of scientific image stacks, with self-supervised Noise2Inverse denoising | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21148567.svg)](https://doi.org/10.5281/zenodo.21148567) [![PyPI](https://img.shields.io/pypi/v/ct-segmentation-toolkit)](https://pypi.org/project/ct-segmentation-toolkit/) |
| [**biomimetic-lattice-pipeline**](https://github.com/crentb/biomimetic-lattice-pipeline) | Synchrotron micro-CT of tooth enamel to biomimetic lattices: parametric CAD, finite-element analysis, and closed-loop design optimization | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21148570.svg)](https://doi.org/10.5281/zenodo.21148570) [![PyPI](https://img.shields.io/pypi/v/biomimetic-lattice-pipeline)](https://pypi.org/project/biomimetic-lattice-pipeline/) |
| [**som-multimodal-datareduction**](https://github.com/crentb/som-multimodal-datareduction) | Self-organizing-map reduction of multimodal materials data (nanomechanics, Raman, fracture) | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21148597.svg)](https://doi.org/10.5281/zenodo.21148597) [![PyPI](https://img.shields.io/pypi/v/som-multimodal-datareduction)](https://pypi.org/project/som-multimodal-datareduction/) |
| [**agentic-bioinspired-cad**](https://github.com/crentb/agentic-bioinspired-cad) | Fully local agentic loop from a text prompt to a certified, single-material, 3D-printable bioinspired architecture, with printability, finite-element, and phase-field fracture checks | [![CI](https://github.com/crentb/agentic-bioinspired-cad/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/crentb/agentic-bioinspired-cad/actions/workflows/ci.yml) |

Every change to these packages passes one continuous-integration gate: multi-version tests, secret scanning, static analysis, dependency and container vulnerability scans, and a signed software bill of materials. Releases publish to PyPI through Trusted Publishing and to the GitHub Container Registry as signed images with SLSA build provenance, and each version is archived on Zenodo with a DOI.

### Links

[Google Scholar](https://scholar.google.com/citations?user=kLYnhl8AAAAJ) · [LinkedIn](https://www.linkedin.com/in/cameron-renteria) · [cameronrenteria.com](https://cameronrenteria.com)
