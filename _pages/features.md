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
    excerpt: 'A mesoSPIM can provide you with isotropic data from a cleared
    and mounted whole mouse brain within 5-8 minutes. Typical single-color acquisitions in cleared mouse brains are done at 6.5 μm voxel size.'
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_aslm:
  - image_path: /assets/images/landing/ASLM-VIP-landing-600.jpg
    url: /aslm/
    alt: "Axially scanned light-sheet microscopy"
    title: "Isotropy across large FOVs"
    excerpt: 'The mesoSPIM is an axially scanned light-sheet microscope (ASLM) for uniform z-resolution across the FOV. In ASLM,
    the waist of the light-sheet is scanned through the sample in synchrony with the rolling shutter readout of the camera.
    At the refractive index of a CLARITY-cleared sample (n=1.45) and using 488 nm illumination, the mesoSPIM achieves an axial resolution of **6.55 μm
    across a 13.3 mm FOV**.'
    btn_label: "Read more on ASLM."
    btn_class: "btn--primary"
feature_row_multiview:
  - image_path: /assets/images/features/multiview-600.jpg
    alt: "Multiview imaging"
    title: "Capable of multiview imaging"
    excerpt: 'The mesoSPIM has a vertical sample rotation axis similar to the original SPIM. This allows 360° rotation of the
    sample without changing the direction of gravity. This avoids any rotation-induced distortions of soft samples.
    Shown are maximum intensity projections of a multi-color acquisition (Alexa 594 & Autofluorescence excited at 405 nm) of a 7-day old chick
    embryo stained for neurofilament and cleared using BABB. '
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
    url: "https://github.com/mesoSPIM/mesoSPIM-control"
    btn_label: "Visit the Github repository"
    btn_class: "btn--primary"
feature_row_sample_mounting:
  - image_path: /assets/images/features/sample_mounting_1600.jpg
    alt: "Sample mounting is easy"
    title: "Mounting and exchanging samples is easy"
    excerpt: 'The current generation of the mesoSPIM uses a 1x air objective (Olympus MVPLAPO1x). Samples are
    inserted from the top into an immersion cuvette (bottom) filled with a refractive index matching solution.   
    The sample holders use kinematic mounts with magnets and can be exchanged within seconds. For CLARITY,
    samples are typically inserted into a sample cuvette (shown here), whereas hard samples (i.e. with iDISCO or BABB clearing)
    are clamped in a 3D-printed holder.'
    url: "/assets/images/features/sample_mounting_1600.jpg"
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_travel_range:
  - image_path: /assets/images/landing/cns_600.jpg
    alt: "Large travel range."
    title: "Image a whole mouse central nervous system."
    excerpt: 'The latest version of the mesoSPIM (V5) has **52 x 52 x 102 mm travel range**. This is sufficient to image
    a whole CLARITY-cleared mouse CNS. Using the rotation stage, multi-view imaging can be performed in
    such large samples.'
    url: "/whole_cns_imaging/"
    btn_label: "Learn more about imaging large samples"
    btn_class: "btn--primary"
feature_row_screening:
  - image_path: /assets/images/features/sample_screening_600.jpg
    alt: "Quick screening of samples."
    title: "Quick screening of samples."
    excerpt: 'The combination of simple sample mounting and fast acquisitions allows quick screening of samples.
    For example, batches of CLARITY-cleared whole mouse brains can be prepared for screening by mounting them
    in imaging cuvettes. Thanks to the magnetic sample holders, mesoSPIM samples can be exchanged within seconds.'
    url: "/assets/images/features/sample_screening_1600.jpg"
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_shadow_reduction:
  - image_path: /assets/images/features/shadow-reduction-600.jpg
    alt: "Shadow reduction"
    title: "Reduced shadowing artifacts"
    excerpt: 'The excitation path of the mesoSPIM is designed to reduce shadowing artifacts. In a standard
    SPIM, refraction, scattering, and absorption of the excitation light-sheet leads to shadowing artifacts (left side).
    The mesoSPIM uses a scanned Gaussian beam with NA 0.15 to create the light-sheet. This NA is higher than in a typical
    large-FOV digitally scanned light-sheet microscope (DSLM) which reduces shadows: The higher illumination NA shortens
    the shadow cone behind absorbing structures such as bubbles. This leads to a very uniform illumination profile in the
    sample and simplifies data analysis.'
    url: "/assets/images/features/shadow-reduction-1600.jpg"
    btn_label: "Enlarge image"
    btn_class: "btn--primary"
feature_row_all_clearing_techniques:
  - image_path: /assets/images/gallery/mesospim_sample_1_lowres.jpg
    alt: "Compatible with all clearing techniques"
    title: "Compatible with all clearing techniques"
    excerpt: 'The mesoSPIM has been tested with a variety of methods, ranging from active and passive CLARITY, X-CLARITY,
    CUBIC-X, BABB, iDISCO, to MASH (iDISCO/ECi) in a wide selection of samples from mouse brains, whole mouse CNS, a chicken embryo, Drosophila melanogaster, to human neocortex.'
    url: "/gallery/"
    btn_label: "Check out the mesoSPIM gallery for examples"
    btn_class: "btn--primary"
feature_row_open_documentation:
- image_path: /assets/images/gallery/mesospim_sample_1_lowres.jpg
  alt: "Open documentation"
  title: "Open documentation"
  excerpt: 'The mesoSPIM parts lists, drawings, installation, and usage instructions are
  freely available on Github.'
  url: "https://github.com/mesoSPIM/mesoSPIM-hardware-documentation"
  btn_label: "Check out the mesoSPIM documentation"
  btn_class: "btn--primary"
---

{% include feature_row id="feature_row_sample_and_data" type="left" %}

{% include feature_row id="feature_row_aslm" type="left" %}

{% include feature_row id="feature_row_multiview" type="left" %}

{% include feature_row id="feature_row_travel_range" type="left" %}

{% include feature_row id="feature_row_sample_mounting" type="left" %}

{% include feature_row id="feature_row_all_clearing_techniques" type="left" %}

{% include feature_row id="feature_row_screening" type="left" %}

{% include feature_row id="feature_row_shadow_reduction" type="left" %}

{% include feature_row id="feature_row_software" type="left" %}

{% include feature_row id="feature_open_documentation" type="left" %}
