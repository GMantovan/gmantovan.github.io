---
permalink: /research/
title: "Research"
layout: single
classes: wide
author_profile: true
header:
  image: /assets/images/st_andrews.jpeg
  image_description: "St. Andrews (Scotland)"
  caption: "Photo credit: Giacomo Mantovan, Iphone SE"
toc: true
---


<div class="post-content">
My research interests span several topics in the field of extrasolar planets, but they all focus on solving the same humankind mystery: Are we alone? </div>

## Exoplanets validation

<figure style="float: left; margin-right: 20px; max-width: 30%; margin-top: 5px; ">
  <a href="/assets/images/tess_valid.jpeg" class="image-popup" title="This is a figure caption.">
    <img src="/assets/images/tess_valid.jpeg" alt="this is a placeholder image" style="width: 100%; height: auto;">
  </a>
  <figcaption>This is a figure caption.</figcaption>
</figure>

<div class="post-content">
<p>One of the main methods of detecting an extrasolar planet - and determining its radius - is the <strong>transit method</strong>. This technique is an indirect method by which we observe a periodic dip in the host star's luminosity caused by the transit of a planet in front of the stellar disk. However, the geometric probability of finding such transit is low and requires us to monitor many stars in the sky. We can overcome this limit thanks to space-based surveys, such as the CoRoT mission, the Kepler mission, or the Transiting Exoplanet Survey Satellite (TESS), which respectively began and continued the era of statistical analysis enabling thousands of exoplanet detections. </p><p>Despite the unstopping growth of detections, almost fifty per cent of objects initially identified as exoplanet <strong>candidates</strong> by the Kepler mission <i>before</i> and by TESS <i>now</i> turned out to be <strong>false positives</strong> (FPs). An FP is an astrophysical object that mimics a planetary transit, such as a binary star system in which the two components undergo mutual eclipses - also known as eclisping binary (EB). In this context, the <strong>validation</strong> process is hence the fundamental procedure that aims to identify and exclude false positives, pushing toward final confirmation of an exoplanet candidate thanks to the contribution of other techniques like the radial velocity (RV), which allows us to obtain the mass of an exoplanet.  </p></div>

## Young planets

<figure style="float: left; margin-right: 20px; max-width: 30%; margin-top: 5px; ">
  <a href="/assets/images/young_planet.jpeg" class="image-popup" title="This is a figure caption.">
    <img src="/assets/images/young_planet.jpeg" alt="this is a placeholder image" style="width: 100%; height: auto;">
  </a>
  <figcaption>This is a figure caption.</figcaption>
</figure>

<div class="post-content">
<p>The mass of an exoplanet, combined with the radius from transit, allows us to precisely measure an exoplanet's inner bulk density and opens the door for subsequent in-depth characterisation. </p><p>An interesting subject of study are <strong>systems younger than 1 Gyr</strong>, which are crucial for understanding the early stages of planetary formation and evolution processes, including orbital migration, atmopsheric evaporation, and planetary impacts. However, it is challenging to identify and model such systems because of the strong magnetic <strong>activity</strong> of the host star that hides planetary signals. The substantial starspot activity on the stellar surface - typical of stars younger than 1 Gyr - generates intense periodic variations in the stellar flux and shape of the spectral lines, affecting both photometric and spectroscopic time series. Therefore, it is essential to mitigate stellar eﬀects, solve the degeneracy, and isolate the planetary signal. </p><p> Among the different approaches and techniques in this rapidly evolving ﬁeld, the <strong>Gaussian Process</strong> (GP) regression can be used as a flexible model for correlated noise typically caused by the variability of the host star. Of particular importance in the context of young stars is the availability of additional indicators, obtained during RV extraction, that give information on the characteristics of spectral lines (e.g., width, asymmetry), which are also aﬀected by active regions, as well as spectral activity indicators which trace chromospheric emission in the cores of strong lines. In my work, I adopted the <strong>multidimensional GP framework</strong> proposed by Rajpaul et al. (2015), a powerful approach for modelling activity indicators simultaneously with RVs, disentangling them from planetary signals. The advent of space transit surveys has revolutionised the study of young planets, making it easier to discover exoplanets around young stars by ﬁrst identifying transiting signals. However, only a small sample of young exoplanets have well-constrained ages, radii, and masses.</p></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var toc = document.querySelector('.toc');
  var header = document.querySelector('header');

  window.addEventListener('scroll', function() {
    var scrollPosition = window.scrollY;
    var headerHeight = header.offsetHeight;
    var tocTopPosition = headerHeight + 330;

    if (scrollPosition >= tocTopPosition) {
      toc.style.top = (scrollPosition - tocTopPosition) + 'px';
    } else {
      toc.style.top = '0px';
    }
  });
});
</script>
