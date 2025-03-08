---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Assessing regional melt patterns for improved projections of Alaskan glacier change
======
*2025-ongoing*\
Synthetic aperture radar (SAR) satellite systems offer a promising avenue to monitor sub-seasonal glacier changes at high spatial resolution on a global scale. Unlike optical sensors, SAR is uniquely robust and reliable, as it penetrates clouds and functions independently to sunlight. This capability is especially crucial in mountainous regions in Alaska, where persistent cloud cover and long, dark winters limit optical observations. Particularly promising are the two Sentinel-1 satellites, which have yielded a continuous SAR record (12-day repeat) since 2016. We seek to process all Sentinel-1 SAR data for glaciers in Alaska to estimate glacier melt extents over time, which are ultimately crucial towards improving projections of glacier mass loss and the subsequent downstream effects associated with these changes throughout the 21st century. In addition to investigating the spatiotemporal melt patterns of glaciers across Alaska, we will utilize these observations in large-scale glacier evolution model calibration schemes to refine projections of modeled glacier change.


A framework for deriving mountain glacier climatic mass balance gradients leveraging remote sensing, modeled, and in-situ data
======
*2024-ongoing*\
The climatic mass balance gradient refers to how the sum of accumulation, refreeze, and melt varies with elevation. The climatic mass balance gradient provides insight into the dominant processes driving glaciers’ response to climate change, which, if known, can enable the isolation of the ice flux: a key component in understanding glacier response times. These response times are crucial for forecasting glacier committed mass loss and changes to current mass imbalances. Mass balance gradients are therefore a simple yet powerful indicator of glaciers’ long-term health and response to climate change. The primary objective of this project is to develop robust approaches to estimate the climatic mass balance gradient for a few well-studied glaciers in Alaska. We will use global, publicly available remote sensing-derived glacier surface velocities, elevation, and ice thickness products in conjunction with velocity and flux divergence estimates from a finite element glacier flow model. We will calculate the climatic mass balance in a portion of the lower ablation area–where we identify data to be the most accurate–and use new melt extent and snowline datasets to determine the equilibrium-line altitude, enabling us to derive the climatic mass balance gradient. Ultimately, we aim to develop a framework to derive the climatic mass balance gradient that has the potential to scale more broadly to glaciers around the region.


Historical glacier reconstruction for enhanced understanding of past changes and impacts on modeled projections
======
*2022-2025*\
Long-term historical records of glacier mass change are key to advancing our understanding of how glaciers are responding to climate change and improving predictions of their future. We use historical aerial photographs and new bed topography measurements to obtain an 85-year record of glacier change on Kennicott and Root Glaciers in Alaska. We observe a clear shift from a likely near-equilibrium state before 1957, to ongoing and accelerating mass loss throughout the late 20th and into the 21st century. Stark differences in the timing and pattern of thinning on the terminus of Kennicott and Root Glaciers emphasize the impact of debris cover on surface mass balance and ice fluxes. Under heavy debris on Kennicott Glacier, the timing of thinning aligns with reduced surface velocities, while thinning on Root Glacier corresponds to changes in the surface mass balance. Projections from a glacier evolution model that leverage these data predict accelerating rates of mass loss through at least 2050 before leveling out or trending back toward equilibrium by the end of the century. While the detailed pattern of mass loss varies between the two glaciers, these improved projections ultimately suggest that 38 to 60% of Kennicott and Root Glaciers’ total mass in 2000 will be lost by 2100, depending on the emissions scenario. Not only does such analysis enhance our understanding of glaciers’ response to climate change, but also better prepares society for the adverse impacts accompanying glacier mass loss. Thus, by leveraging historical data, we can better plan for future changes including developing adaptation and mitigation strategies for the corresponding impacts on sea-level rise, ecosystems, water resources, and the communities that rely on these glaciers.


GNSS reflectometry from low-cost sensors for continuous in-situ contemporaneous glacier mass balance and flux divergence
======
*2021-2024*\
Recent advances in remote sensing have produced global glacier surface elevation change data. Parsing these elevation change signals into contributions from the climate (i.e. climatic mass balance) and glacier dynamics (i.e. flux divergence) is critical to enhancing our process-based understanding of glacier change. We evaluated three approaches for direct, continuous measurements of the climatic mass balance, flux divergence, and elevation change at a site on Gulkana Glacier in Alaska using low-cost global navigation satellite system (GNSS) sensors, GNSS interferometric reflectometry (GNSS-IR), banded ablation stakes with time-lapse cameras and combinations thereof. We showed that contemporaneous climatic mass balance, flux divergence, and elevation change can be obtained from a single GNSS system fixed atop an ablation stake. Thus, the data provide critical high-temporal resolution calibration and validation data for modeled and remote sensing-derived products alike, especially for efforts that seek to separate flux divergence signals from total elevation change. As one of the first studies leveraging GNSS-IR on a mountain glacier, we see potential in GNSS-IR for future in situ investigations of mountain glaciers, as it reduces the barrier for otherwise difficult simultaneous climatic mass balance and flux divergence measurements. While our study deployed systems during the ablation season, we see the potential for year-round observations on mountain glaciers in the future.\
[publication](https://doi.org/10.1017/jog.2024.54)


<div style="text-align: center;">
  <video id="video" width="640" height="360" controls>
    <source src="[https://github.com/](https://raw.githubusercontent.com/albinwwells/albinwwells.github.io/images/projects/gnss/mb_timelapse_animation_site_ab_2023.mp4)" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <img src="https://raw.githubusercontent.com/albinwwells/albinwwells.github.io/main/images/projects/gnss/fixed_gnss_schematic.png" width="640" height="360" style="display: none;">
  
  <img src="https://raw.githubusercontent.com/albinwwells/albinwwells.github.io/main/images/projects/gnss/fixed_gnss_spring-fall.png" width="640" height="360" style="display: none;">

  <br>

  <button onclick="toggleMedia()">⬅️➡️</button>
</div>

<script>
  function toggleMedia() {
    var video = document.getElementById("video");
    var image = document.getElementById("image");

    if (video.style.display === "none") {
      video.style.display = "block";
      image.style.display = "none";
    } else {
      video.style.display = "none";
      image.style.display = "block";
    }
  }
</script>

