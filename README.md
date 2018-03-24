# GALEX_transit

The [gPhoton](https://archive.stsci.edu/prepds/gphoton/) database enables timeseries analysis of GALEX data for sources, at arbitrary cadence.

There is *some* overlap of the Kepler field and the main GALEX/gPhoton database (this does not currently include the GALEX-CAUSE Kepler survey).

## Question
Did GALEX serendipitously observe a transit in the Kepler field? Each GALEX visit is not very long, so if we're lucky we'll catch ingress or egress (the most interesting parts).

## Why
UV observations of transits are interesting! e.g. see [Llama & Shkolnik (2015)](https://arxiv.org/abs/1501.04963) and [Schlawin et al. (2010)](https://arxiv.org/abs/1008.1073)

## How
- Get list of all confirmed KOIs with Depth > 1000ppm. 
- Use gFind to find any times of overlap. 
- If any overlaps are near Phase=0 or Phase=1, keep the overlap.
- Make plots of each at 2-min cadence

## Results
Nothing amazing so far... maybe enough for a AAS Research Note?

## Future
This a good exercise to repeat with GALEX + TESS to try and find UV transits
