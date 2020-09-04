# FluxTraining

[![Build Status](https://github.com/lorenzoh/FluxTraining.jl/workflows/CI/badge.svg)](https://github.com/lorenzoh/FluxTraining.jl/actions)
[![Stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://lorenzoh.github.io/FluxTraining.jl/stable)
[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://lorenzoh.github.io/FluxTraining.jl/dev)

A flexible neural net training library inspired by fast.ai

(note: package is in a very early stage and will have bugs and interface is open to change, proper docs are also a work in progress)

## Demo

see [`demo notebook`](./examples/FluxTraining.jl-demo.ipynb)

## Features

- training loop with extensible callback system
- built-in callbacks:
  - metrics
  - hyperparameter scheduling
  - logging
  - training history
  - model checkpointing

## Related packages

(all WIP, but check out if you are interested)

- [`DataAugmentation.jl`](https://github.com/lorenzoh/DataAugmentation.jl): for performant data augmentation pipelines
- [`DataLoaders.jl`](https://github.com/lorenzoh/DataLoaders.jl): for parallel data loading and batching
- [`ModelUtils.jl`](https://github.com/lorenzoh/ModelUtils.jl): for model introspection
- [`VisionDatasets.jl`](https://github.com/lorenzoh/VisionDatasets.jl): for computer vision datasets
- [`FluxModels.jl`](https://github.com/lorenzoh/FluxModels.jl): for computer vision models
