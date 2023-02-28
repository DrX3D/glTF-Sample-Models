<p align="center">
<img src="2.0/glTF_RGB_June16.svg" height="100">
</p>

# glTF V2.0 Sample Models

[![glTF Validation](https://github.com/KhronosGroup/glTF-Sample-Models/workflows/glTF%20Validation/badge.svg?branch=master)](https://github.com/KhronosGroup/glTF-Sample-Models/actions)

- Obsolete references
  - [glTF 1.0](1.0) - _needs to be update to new ARCHIVED repo_
  - [glTF 2.0](2.0) - See [the full list](2.0).

Sample glTF 2.0 models are provided in one or more of the following forms of glTF:

* glTF (`.gltf`) with separate resources: `.bin` (geometry, animation, skins) and `.jpg` or `.png` image files.  The supporting files are easily examined when separated like this, but must be kept together with the parent glTF file for the model to work.
* glTF (`.gltf`) with embedded resources (as Data URIs).  This form tends to be larger than the others, but Data URIs do have their uses.
* Binary glTF (`.glb`) using the [binary container format](https://github.com/KhronosGroup/glTF/blob/master/specification/2.0/README.md#glb-file-format-specification).  These are easily shared due to the bundling of all the textures and mesh data into a single file.

There are multiple lists provided for simplifying your access and review of the models. All lists include the model name, screen shot, link to display the model in Sample Viewer, a short description, and the license/credits for the model.

The available lists are:
* [Showcase](./Models-showcase.md) for models that are showcased in Khronos publicity. These are usually complex models with high visual quality.
* [Full](./Models.md) for all models.
* [Testing](./Models-testing.md) for models intended to be used for testing of viewers, converts, and other software systems.
* [Core Only](./Models-core.md) for models that only use glTF Core V2.0 features and capabilities.
* [Video Tutorials](./Models-videos.md) for models used in any glTF Tutorial video.
* [Written Tutorials](./Models-written.md) for models used in a written glTF Tutorial.

A summary of the model license is shown in each display, but see the `README.md` in each model's directory for detailed license information.

Sample models help the glTF ecosystem, if you are able to contribute a model, see the [contributing section](./SubmittingModels.md) below.

## Model Publishing Services with glTF Download Capability

* [Sketchfab](https://sketchfab.com/features/gltf) offers auto-conversion of all of its downloadable models, including PBR models, to glTF format.
* [Poimandres Market](https://market.pmnd.rs/) offers 3D assets for download in glTF format.
* [Poly Haven](https://polyhaven.com/) offers CC0 (public domain equivalent) HDRIs, PBR textures, and glTF models.

## Other glTF Models

For addition glTF models, see:

* [Khronos glTF Asset Generator](https://github.com/KhronosGroup/glTF-Asset-Generator) offers an extensive suite of test models to exercise each part of the glTF specification.
* Cesium's [demo models](https://github.com/AnalyticalGraphicsInc/cesium/tree/master/Apps/SampleData/models) and [unit test models](https://github.com/AnalyticalGraphicsInc/cesium/tree/master/Specs/Data/Models).
* Flightradar24's [GitHub repo](https://github.com/kalmykov/fr24-3d-models) of aircrafts.
* [Kenney • Assets](https://kenney.nl/assets?q=3d) hundreds of themed low-poly assets (nature, space, castle, furniture, etc.) provided by Kenney under CC0 licenses, including [30+ pirate themed models](https://kenney.nl/assets/pirate-kit).
* [Smithsonian open access 3D models](https://3d.si.edu/cc0?edan_q=*:*&edan_fq[]=online_media_type:%223D+Images%22)

If you have any questions, submit an [issue](https://github.com/KhronosGroup/glTF-Sample-Models/issues).
