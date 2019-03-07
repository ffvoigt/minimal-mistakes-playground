---
title: "The mesoSPIM Initiative"
layout: splash
permalink: /
date: 2019-03-04
header:
  overlay_image: /assets/images/headers/embryo_multiview_1600.jpg
  actions:
    - label: "Build your own"
      url: "https://github.com/mesoSPIM/mesoSPIM-hardware-documentation"
excerpt: "Open-source light-sheet microscopes for imaging cleared tissue."
intro:
  - excerpt: "The mesoSPIM (mesoscale selective plane illumination microscopy) project creates open-hardware microscopy platforms for imaging cleared tissue. "
feature_row0:
  - image_path: assets/images/landing/mesoSPIM_1.jpg
    alt: "placeholder image 1"
    title: "mesoSPIM features"
    excerpt: "Compatible with all clearing methods, simple and quick sample mounting
    and exchange, reduced shadowing artifacts and many more..."
    url: "/features/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/ASLM-VIP-landing-600.jpg
    alt: "Axially scanned light-sheet microscopy"
    title: "Isotropy across large FOVs"
    excerpt: "The mesoSPIM is an axially scanned light-sheet microscope (ASLM) for uniform z-resolution across the FOV."
    url: "/aslm/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/whole_cns/cns3_600.jpg
    title: "Image large Samples"
    excerpt: "Fits a whole mouse CNS with 52 x 52 x 102 mm travel range - a larger
    sample volume than any other available light-sheet microscope."
    url: "/whole_cns_imaging/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row1:
  - image_path: /assets/images/landing/mesoSPIM_V5_lowres.jpg
    alt: "placeholder image 2"
    title: "Open Hard & Software"
    excerpt: "The mesoSPIM is an open hardware project."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/geneva_2018_lowres.jpg
    title: "Meetings and Workshops"
    excerpt: "Members of the mesoSPIM initiative organize a variety of workshops for the community."
    url: "/meetings_and_workshops/"
    btn_label: "Upcoming meetings"
    btn_class: "btn--primary"
  - image_path: /assets/images/landing/mesoSPIM-Wyss-lowres.jpg
    alt: "Wyss mesoSPIM"
    title: "Find a mesoSPIM near you."
    excerpt: "Currently, there are 5 mesoSPIM setups in operation."
    url: "/setups/"
    btn_label: "Existing setups"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row0" %}

{% include feature_row id="feature_row1" %}
