#plugin 
## What is the HydroMT-SFINCS plugin?[](https://deltares.github.io/hydromt_sfincs/latest/#what-is-the-hydromt-sfincs-plugin "Permalink to this heading")

[[core|Hydromt]] (Hydro Model Tools) is an open-source [[python]] package that facilitates the process of building and analyzing spatial geoscientific models with a focus on water system models. It does so by automating the workflow to go from raw data to a complete model instance which is ready to run and to analyse model results once the simulation has finished. This plugin provides an implementation of the model API for the [SFINCS](https://sfincs.readthedocs.io/en/latest/) model.

## What is SFINCS?

SFINCS is Deltares’ new open-source reduced-complexity model designed for super-fast modelling of compound [[flooding]] events in a dynamic way! What HydroMT-SFINCS does provide is a powerful Python based set of tools to help you build and analyse the best possible SFINCS models! This HydroMT-SFINCS plugin does not include the SFINCS model or executable itself, for that see the [SFINCS download portal](https://download.deltares.nl/en/download/sfincs/) or the source code repository on [[Github]]. For general documentation about the model, how to run it and what the input files are see the [SFINCS documentation](https://sfincs.readthedocs.io/en/latest/).

## Why HydroMT-SFINCS?[](https://deltares.github.io/hydromt_sfincs/latest/#why-hydromt-sfincs "Permalink to this heading")

Setting up hydrodynamic models typically requires many (manual) steps to process input data and might therefore be time consuming and hard to reproduce. Especially improving models based on global geospatial datasets, which are rapidly becoming available at increasingly high resolutions, might be challenging. HydroMT-SFINCS aims to make the model building process **fast**, **modular** and **reproducible** and to facilitate the analysis of SFINCS model results

## How to use HydroMT-SFINCS?[](https://deltares.github.io/hydromt_sfincs/latest/#how-to-use-hydromt-sfincs "Permalink to this heading")

The HydroMT-SFINCS plugin can be used as a **command line + configuration file** application, which provides commands to _build_, _update_ the SFINCS model with a single line, or **from python** to exploit its rich interface. You can learn more about how to use HydroMT-SFINCS in its [online documentation.](https://deltares.github.io/hydromt_sfincs/latest/getting_started/intro) For a smooth installing experience we recommend installing HydroMT-SFINCS and its dependencies from conda-forge in a clean environment, see [installation guide.](https://deltares.github.io/hydromt_sfincs/latest/getting_started/installation)
