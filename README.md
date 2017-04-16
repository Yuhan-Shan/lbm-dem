# 2D/3D Lattice Boltzmann - Discrete Element Method (lbmdem)
> Cambridge Berkeley - Geomechanics

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/cb-geo/develop/license.md)
[![Documentation](https://img.shields.io/badge/docs-doxygen-blue.svg)](http://cb-geo.github.io/lbm-dem)
[![Build status](https://api.travis-ci.org/cb-geo/lbmdem.svg)](https://travis-ci.org/cb-geo/lbm-dem/builds)
[![CircleCI](https://circleci.com/gh/cb-geo/lbm-dem/tree/develop.svg?style=svg)](https://circleci.com/gh/cb-geo/lbm-dem/tree/develop)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/10011/badge.svg)](https://scan.coverity.com/projects/cb-geo-lbmdem)
[![codecov.io](http://codecov.io/github/cb-geo/lbmdem/coverage.svg?branch=develop)](http://codecov.io/github/cb-geo/lbmdem?branch=develop)
[![](https://img.shields.io/github/issues-raw/cb-geo/lbm-dem.svg)](https://github.com/cb-geo/lbm-dem/issues)


## Install dependencies

* Docker image for CB-Geo LBM-DEM code [https://hub.docker.com/r/cbgeo/lbmdem](https://hub.docker.com/r/cbgeo/lbmdem)

* Instructions for running lbmdem docker container: [https://github.com/cb-geo/docker-lbmdem/blob/master/README.md](https://github.com/cb-geo/docker-lbmdem/blob/master/README.md).

## Compile and Run

0. Run `mkdir build && cd build && cmake ..`

1. Run `make clean && make -jN` (where N is the number of cores)

3. Run lbmdem `./lbmdem`

4. Run lbmdemtest `ctest -VV -S` or `./lbmdemtest` to run test cases
