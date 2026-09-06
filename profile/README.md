# Microscopy Imaging Analysis

Open methods for quantitative analysis of microscopy images, with explicit
pixel-based parameters and traceable data products from image intake to
biological interpretation.

## Start here

[`microscopy-analysis-workflows`](https://github.com/MicroscopyImagingAnalysis/microscopy-analysis-workflows)
is the visual, notebook-based entry point. Its ordered walkthrough covers image
inspection, segmentation, 2D/3D measurements, spheroid radial analysis, spatial
graphs, VAE/CVAE representations and analysis-ready feature tables.

## Method packages

- [`nuclear-imaging-core`](https://github.com/MicroscopyImagingAnalysis/nuclear-imaging-core): segmentation, measurements and spatial graph representations
- [`nuclear-spheroid-analysis`](https://github.com/MicroscopyImagingAnalysis/nuclear-spheroid-analysis): 2D/3D nucleus-to-spheroid and radial workflows
- [`nuclear-vae-embeddings`](https://github.com/MicroscopyImagingAnalysis/nuclear-vae-embeddings): VAE and conditional VAE representations of nuclear crops
- [`nuclear-table-tools`](https://github.com/MicroscopyImagingAnalysis/nuclear-table-tools): feature-table joins, filtering and preparation

Each repository keeps scientific parameters visible in code or JSON config,
separates reusable methods from workflow narrative, and uses stable object
identifiers between processing stages.
