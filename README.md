# Vehicle to interface (V2I) parameters

## Overview
This is a package for managing parameters to use [v2i_interface](https://github.com/eve-autonomy/v2i_interface) easily.

This package has 4 types of parallel directories for parameter management:
- `product`
  - This directory manages the parameters as connection settings to the broadcasting device.
- `local_test`
  - This directory manages the parameters as connection settings to the dummy of the broadcasting device that runs locally.
  - It is mainly used as a criterion for testing as OSS.

The list of parameter names managed in these directories is the same, only the values are different.

## Parameter details
See the [parameter description for v2i_interface](https://github.com/eve-autonomy/v2i_interface#parameter-description).

## Extensibility of this package
This package is a template as a parameter configuration.

If you want to rewrite the values in this package and use it, fork this repository to create a new one.
