# Vehicle to interface (V2I) parameters

## Overview
This is a package for managing parameters to use [v2i_interface](https://github.com/eve-autonomy/v2i_interface) easily.

This package has 4 types of parameter set in each directory depending on purposes.
- `product` directory
  - This is for connection settings to the broadcasting device.
- `local_test` directory
  - This is for test connection settings of the broadcasting device that runs locally.
  - This is used as a criterion for test before `v2i_interface` is released as OSS.

The list of parameter names managed in these directories is the same, only the values are different.

## Parameter details
See the [parameter description for v2i_interface](https://github.com/eve-autonomy/v2i_interface#parameter-description).

## Extensibility of this package
This package is a template as a parameter configuration.

If you want to rewrite the values in this package and use it, fork this repository to create a new one.
