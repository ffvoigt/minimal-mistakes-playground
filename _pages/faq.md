---
permalink: /faq/
title: "FAQ"
layout: single
classes: wide
excerpt: "Frequently asked questions"
toc: true
---

## General questions

### What are the unique features of a mesoSPIM?

### How does the mesoSPIM compare to other light-sheet instruments?

#### openSPIM

#### LaVision BioTec Ultramicroscope II

#### PhaseView Alpha 3

#### Zeiss Z.1

## Budget and installation

### How much does a mesoSPIM cost?
Depending on the configuration, a mesoSPIM Version 5 costs between 169600 to 239600 USD (Swiss prices
converted to USD at a 1:1 exchange ratio).

### Why does it cost so much?
The mesoSPIM setups are intended ([and used](/setups/)) as a multiuser-instrument for laboratories supporting many imaging projects.
As such, even the most basic realized mesoSPIM has at least 4 laser lines with high power (>50-150 mW for each line). The high
laser power is required to properly illuminate the wide (>20 mm) light-sheet which leads to the laser engines being the
most expensive part of the instrument (approx. 1/2 to 1/3 of the total budget).

### Is it possible to build it for less?
Yes, by using only a single excitation wavelength and a single illumination arm. If multiple
laser wavelengths are required, [building a custom laser combiner](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0173879)
could be an option.

### What is the difference between mesoSPIM version 5 and its predecessors?
The most recent (and recommended) Version 5 differs from Version 4 in a different
set of stages to avoid a [problem with stage roll / wobble](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki/mesoSPIM_V4_stage_wobble).
An overview of all mesoSPIM versions can be found [here](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki/mesoSPIM_history).

### How complicated is it to set up a mesoSPIM?
We recommend setting up a mesoSPIM to researchers how have previous experience in setting up
custom microscopes such as two-photon or other light-sheet instruments. If you do not have
prior experience with such instruments, please check out the [openSPIM](https://openspim.org).

## Clearing methods

### What clearing techniques is the mesoSPIM compatible with?
The mesoSPIM has been tested in combination with active & passive CLARITY, CUBIC, BABB, iDISCO,
and ECi-based clearing methods. As this list covers approaches using a hydrogel and methods
using organic solvents, we believe that the **mesoSPIM is compatible with all existing clearing
techniques**.

## Software

### Where can I find the mesoSPIM-software?
mesoSPIM-control can be found [here](https://github.com/mesoSPIM/mesoSPIM-control).

### Can the mesoSPIM-Software be used to control other light-sheet microscopes?
Basically yes, but mesoSPIM-control is tailored to control mesoSPIM setups.
If you intend to do so, please fork mesoSPIM-control on [Github](https://github.com/mesoSPIM/mesoSPIM-control)

### Can mesoSPIM-control support time-lapse acquisitions?
Currently not. The mesoSPIM is intended for cleared samples that are larger (cm-sized)
then most (mm-sized) specimens (Drosophila larvae, zebrafish embryos) in which time-lapse
acquisitions are commonly used.


### Can a mesoSPIM be controlled with other acquisition software?
Basically yes, for example, [micro-manager](https://micro-manager.org/) can control
the majority of hardware components of a mesoSPIM (cameras, lasers, stages). However, the
axially scanned light-sheet mode would require a custom GUI and the corresponding
device drivers.
