---
permalink: /features/
title: "mesoSPIM features"
layout: splash
excerpt: "Focus on image quality"
toc: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/headers/YCX-L5-frontal.jpg
  actions:
  - label: "Build your own"
    url: "https://github.com/mesoSPIM/mesoSPIM-hardware-documentation"
feature_row_sample_and_data:
  - image_path: /assets/images/features/sample_and_data_600.jpg
    url: /assets/images/features/sample_and_data_1600.jpg
    alt: "From your sample to data in less than 10 minutes"
    title: "From your sample to data in less than 10 minutes"
    excerpt: 'A mesoSPIM can provide you with isotropic overview data from a cleared
    and mounted whole mouse brain within less than 10 minutes. Typical single-color acquisitions
    in cleared mouse brains are done at 5-6 '
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_aslm:
  - image_path: /assets/images/landing/ASLM-VIP-landing-600.jpg
    url: /aslm/
    alt: "Axially scanned light-sheet microscopy"
    title: "Isotropy across large FOVs"
    excerpt: 'The mesoSPIM is an axially scanned light-sheet microscope (ASLM) for uniform z-resolution across the FOV. In ASLM,
    the waist of the light-sheet is scanned through the sample in synchrony with the rolling shutter readout of the camera.'
    btn_label: "Read more on ASLM."
    btn_class: "btn--primary"
feature_row_multiview:
  - image_path: /assets/images/features/multiview-600.jpg
    alt: "Multiview imaging"
    title: "Capable of multiview imaging"
    excerpt: 'The mesoSPIM has a vertical sample rotation axis similar to the original SPIM. This allows 360° rotation of the
    sample without changing the direction of gravity. This avoids any rotation-induced distortions of soft samples.'
    url: "/assets/images/features/multiview-3840.jpg"
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_sample_holders:
  - image_path: /assets/images/features/sample_and_data_600.jpg
    alt: "Modular sample holders"
    title: "Modular quick-exchange sample holders"
    excerpt: 'A series of quick-exchange sample holders for '
    url: "#test-link"
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_software:
  - image_path: /assets/images/features/mesospim-control-600.jpg
    alt: "placeholder image 2"
    title: "Software: mesoSPIM-control"
    excerpt: 'The mesoSPIM-control software is open-source and based on Python and PyQt5. It allows control
    of the ASLM mode and contains an acquisition manager, a table-based tool to create complex multichannel,
    multiview or tiling acquisitions.'
    url: /assets/images/features/mesospim-control-1600.jpg
    btn_label: "Visit the Github repository"
    btn_class: "btn--primary"
feature_row_sample_mounting:
  - image_path: /assets/images/features/sample_and_data_600.jpg
    alt: "Easy sample mounting"
    title: "Easy sample mounting"
    excerpt: 'Sample mounting text'
    url: "/assets/images/features/sample_mounting_1600.jpg"
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_travel_range:
  - image_path: /assets/images/landing/cns_600.jpg
    alt: "Large travel range."
    title: "Image a whole mouse central nervous system."
    excerpt: 'The latest version of the mesoSPIM (V5) has 52 x 52 x 102 mm travel range. This is sufficient to image
    a whole CLARITY-cleared mouse CNS. Using the rotation stage, multi-view imaging can be performed in
    such large samples.'
    url: "/whole_cns_imaging/"
    btn_label: "Learn more about imaging large samples"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Reduced shadowing artifacts"
    excerpt: 'Using an Olympus MVX-10 in combination with a MVPLAPO1x objective'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Uniform axial resolution across the FOV"
    excerpt: 'ASLM'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row6:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "52 x 52 x 102 mm travel range"
    excerpt: 'ASLM'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row7:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Compatible with all clearing techniques"
    excerpt: 'Switching between clearing media within seconds'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row8:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Compatible with all sample mounting in cuvettes"
    excerpt: 'ASLM'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row9:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Compatible with all sample mounting in cuvettes"
    excerpt: 'ASLM'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="feature_row_sample_and_data" type="left" %}

{% include feature_row id="feature_row_aslm" type="left" %}

{% include feature_row id="feature_row_multiview" type="left" %}

{% include feature_row id="feature_row_travel_range" type="left" %}

{% include feature_row id="feature_row_sample_mounting" type="left" %}

{% include feature_row id="feature_row_sample_holders" type="left" %}

{% include feature_row id="feature_row_software" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row6" type="left" %}

{% include feature_row id="feature_row7" type="left" %}

{% include feature_row id="feature_row8" type="left" %}

{% include feature_row id="feature_row9" type="left" %}
