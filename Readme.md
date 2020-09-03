# AOD Controls

This is a set of programs to drive an AOD in an optical tweezer setup. It includes an image acquisition library, a driver for a set of coils, and some scripts for different experiments. 

## Getting started 

### Prerequisites

The current version of these programs were tested with LabVIEW 17. Besides that, the AOD is driven through a CompacDAQ, which can also be used to drive the coils. For details see [Soft Matter, 2018,14, 5121-5129](https://doi.org/10.1039/C8SM00434J).

### Running

Once cloned, the main front panels can be run using main.vi. Other things that are not found in the main.vi, can be found in the specific folders and projects (e.g. CoilsControl contains a simple waveform generator to control external coils).

## Authors
* Antonio Ortiz-Ambriz designed and wrote most of the program.
* Eric Cereceda-Lopez designed and tested many of the program extras.

## Licence
This project is licensed under the MIT License