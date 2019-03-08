---
permalink: /faq/
title: "Frequently asked questions"
layout: single
classes: wide
excerpt: "For users and developers"
toc: true
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: "/assets/images/headers/mesospim-red-blue-setup2.jpg"
---

## General questions

### Who is the mesoSPIM project for?
* You are looking for a versatile imaging platform for cleared tissue that can be tailored to your needs.
* Research groups and imaging facilities with experience in building and supporting custom microscopes.

### What are ideal imaging applications for a mesoSPIM?
* Screening of large numbers of samples for clearing & labeling quality.
* Visualization of sparse cell populations or other structures (blood vessels, plaques) in whole cleared organs.

### What are the mesoSPIM instruments less well suited for?
* Imaging live samples (this is the domain of classical light-sheet microscopes)
* High-resolution (<1 µm pixelsize) scans with large number of tiles across whole mouse brains
(this is better done using light-sheet instruments not based on a zoom macroscopes such as the Zeiss Z.1., the COLM)

### What are the features of a mesoSPIM?
The mesoSPIM instrument has the following features:
* large travel range (52 x 52 x 102 mm in a mesoSPIM Version 5) which can accomodate a
whole cleared mouse CNS
* axially scanned light-sheet microscopy ([ASLM](/aslm/)) excitation path allowing for
an axial resolution of 6.5 μm across at least 13.3 mm FOV which leads to near isotropic
imaging conditions at low zoom
* capable of multiview imaging (sample rotation is easy)
* fast (<10 minutes) isotropic (6.5 μm pixel size) imaging of a whole mouse brain
* easy and quick sample exchange
* compatible with sample mounting in cuvettes
* modular sample holders and modular immersion cuvettes allowing
for quick switching between different clearing media
* horizontal detection path (allows for easy sample rotation)
* macro-zoom system in the detection path with 2-20 mm FOV
* dual-sided illumination
* illumination path designed to reduce shadows
* open [hardware](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki) and software

Most existing light-sheet microscopes combine a variety of these features, but
the mesoSPIM setup is unique in combining all of them.

### How does the mesoSPIM compare to the openSPIM?
The openSPIM is most successful as an educational tool to train microscopists in how to set up
and operate a light-sheet microscope. The mesoSPIM initiative is intended to
provide the imaging community with facility-grade light-sheet setups for imaging
in cleared tissue. It is not intended to be used for long-term time-lapse
imaging such as the openSPIM. In addition, the openSPIM is based on standard
microscope optics whereas the mesoSPIM is
based on a macro-zoom setup. This means that the maximum achievable FOVs with an openSPIM
is around 5 to 10 mm. In contrast, the mesoSPIM achieves up to 20 mm FOV and has an
excitation path that can illuminate the full FOV. The mesoSPIM excitation path
is also designed to reduce shadowing and contains tunable lenses for the [ASLM mode]({{ site.url }}/aslm/)
which allows for uniform axial resolution across the FOV. In addition, the mesoSPIM
excitation path is dual-sided like a variant of the openSPIM (the T-SPIM).
All existing mesoSPIM setups have at least four laser lines to be able to image a wide variety
of fluorophores. All these additional features mean that a typical mesoSPIM is
two to five-fold more expensive as common openSPIM variants.

### Where can find a mesoSPIM to test my samples?
Please have a look in the [list of operating mesoSPIM instruments]({{ site.url }}/setups/).
Many of the labs and facilities operating a mesoSPIM are open to interested users.

### What is the difference between mesoSPIM version 5 and its predecessors?
The most recent (and recommended) version 5 differs from version 4 in a different
set of stages to avoid a [problem with stage roll / wobble](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki/mesoSPIM_V4_stage_wobble).
Compared to the 44.5 x 44.5 x 100 mm travel range of version 4, version 5 has a slightly larger range (52 x 52 x 102 mm).
An overview of all mesoSPIM versions can be found [here](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki/mesoSPIM_history).

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

### How complicated is it to set up a mesoSPIM?
We recommend setting up a mesoSPIM to researchers how have previous experience in setting up
custom microscopes such as two-photon or other light-sheet instruments. If you do not have
prior experience with such instruments, please check out the [openSPIM](https://openspim.org).

### Where can I find the instructions to set up a mesoSPIM?
Please have a look in the mesoSPIM [wiki](https://github.com/mesoSPIM/mesoSPIM-hardware-documentation/wiki).

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
