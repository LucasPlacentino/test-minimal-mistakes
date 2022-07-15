---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#30e3ca"
  overlay_image: /assets/images/homepage-image.png
  actions:
    - label: "<i class='fas fa-keyboard'></i> Get Started"
      url: "/docs/quick-start/"
excerpt: >
  A DIY 75% hotswap ISO mechanical keyboard, with rotary encoder and vertical USB A port.<br /> {::nomarkdown}<a class="github-button" href="https://github.com/ObsiLab/Quanta" data-size="large" aria-label="Quanta on GitHub"> Github repository</a>{:/nomarkdown}
feature_row:
  - image_path: /assets/images/keyboard-photo.jpg
    alt: "keyboard photo"
    title: "<i class='fas fa-keyboard'></i> The Quanta"
    excerpt: "The Quanta is a 75%, hotswap, ISO layout, mechanical keyboard."
    url: "/keyboard/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/firmware-code.png
    alt: "firmware code"
    title: "<i class="fas fa-code"></i> RMK Firmware"
    excerpt: "Fully open-source customizable firmware written in Rust."
    url: "/docs/firmware/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/pcb.png
    alt: "PCB"
    title: "<i class="fas fa-microchip"></i> Open Hardware"
    excerpt: "Fully Open-Source hardware, get access to the KiCad Project PCB files. CERN-OHL-P v2 license"
    url: "/hardware/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
intro:
  - excerpt: 'Explore everything about the Quanta'
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
