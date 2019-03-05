---
permalink: /aslm/
title: "Axially scanned light-sheet microscopy"
layout: splash
excerpt: "The key to mesoSPIM performance."
toc: false
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: /assets/images/headers/aslm_vip_1600.jpg
  actions:
  - label: "Main page"
    url: "/"
feature_row0:
  - image_path: /assets/images/aslm/ASLM-1_600.jpg
    alt: "Standard light-sheet illumination"
    title: "Varying light-sheet thickness leads to varying axial resolution."
    excerpt: 'In a standard light-sheet microscope with Gaussian illumination,
    the varying thickness of the lightsheet leads to axially blurred features
    at the edges of the field of view.'
feature_row1:
  - image_path: /assets/images/aslm/ASLM-2_600.jpg
    alt: "Concept of axially scanned light-sheet microscopy (ASLM)"
    title: "Axially scanned light-sheet microscopy (ASLM)"
    excerpt: 'In axially scanned light-sheet microscopy (ASLM), the waist of
    the light-sheet is translated through the sample in synchrony with
    the rolling shutter of the camera. The concept was published in 2015 by
    Dean et al.'
    url: "https://www.sciencedirect.com/science/article/pii/S0006349515004981"
    btn_label: "ASLM paper"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/aslm/ASLM-VIP-bad-600.jpg
    url: "/assets/images/aslm/ASLM-VIP-bad-1600.jpg"
    alt: "Typical XZ view of a whole mouse brain."
    title: "XZ view of a slice of a whole mouse brain with standard light-sheet illumination."
    excerpt: 'Here, a XZ view of a VIP-tdTomato mouse brain (cleared using passive
      CLARITY) shows the axial
    blurring of neurons gradually increasing from the center to the edges
    of the FOV. Cells in the center are well resolved in z as they are close to the
    waist locatation of the light-sheet. Cells at the edges, however, are blurred
    and indistinguishable due to the thicker light-sheet.'
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/aslm/ASLM-VIP-good-600.jpg
    url: "/assets/images/aslm/ASLM-VIP-good-600.jpg"
    alt: "Sample mounting"
    title: "XZ view of a slice of a whole mouse brain with ASLM mode enabled"
    excerpt: 'After switching the ASLM mode on, cells can be resolved in the axial direction across the whole FOV.'
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
---
{% include feature_row id="feature_row0" type="left" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}
