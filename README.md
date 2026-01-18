# RPi.GPIO Feedstock

This repository contains the conda recipe for `RPi.GPIO`.

## Building the package

### Using conda-build (Standard)
```bash
conda build recipe/meta.yaml
```

### Using Pixi (Recommended)
This command uses `rattler-build` installed via pixi to build the recipe.
```bash
pixi run build
```

## Installing with Pixi

Once built, you can install the local package by adding the output channel to your `pixi.toml` or using the file directly.
