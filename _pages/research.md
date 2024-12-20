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

<figure style="float: left; margin-right: 20px; max-width: 30%; margin-top: 5px; margin-bottom: 1px; ">
  <a href="/assets/images/tess_valid.jpeg" class="image-popup" title="AI generated figure.">
    <img src="/assets/images/tess_valid.jpeg" alt="this is a placeholder image" style="width: 100%; height: auto;">
  </a>
  <figcaption>AI generated figure. Do you like it? Yes? Then you might like my paper as well &#128521; <a href="https://ui.adsabs.harvard.edu/abs/2022MNRAS.516.4432M/abstract">(Mantovan et al. 2022)</a>.</figcaption>
</figure>

<div class="post-content">
<p>One of the main methods of detecting an extrasolar planet - and determining its radius - is the <strong>transit method</strong>. This technique is an indirect method by which we observe a periodic dip in the host star's luminosity caused by the transit of a planet in front of the stellar disk. However, the geometric probability of finding such transit is low and requires us to monitor many stars in the sky <a href="https://ui.adsabs.harvard.edu/abs/2010exop.book...55W/abstract">(Winn 2010)</a>. We can overcome this limit thanks to space-based surveys, such as the CoRoT mission, the Kepler mission, or the Transiting Exoplanet Survey Satellite (TESS), which respectively began and continued the era of statistical analysis enabling thousands of exoplanet detections. </p><p>Despite the unstopping growth of detections, almost fifty per cent of objects initially identified as exoplanet <strong>candidates</strong> by the Kepler mission <i>before</i> and by TESS <i>now</i> turned out to be <strong>false positives</strong> (FPs). An FP is an astrophysical object that mimics a planetary transit, such as a binary star system in which the two components undergo mutual eclipses - also known as eclisping binary (EB). In this context, the <strong>validation</strong> process is hence the fundamental procedure that aims to identify and exclude false positives, pushing toward final confirmation of an exoplanet candidate thanks to the contribution of other techniques like the radial velocity (RV), which allows us to obtain the mass of an exoplanet.  </p></div>

## Young planets

<figure style="float: left; margin-right: 20px; max-width: 30%; margin-top: 5px; margin-bottom: 1px;">
  <a href="/assets/images/young_planet.jpeg" class="image-popup" title="This is a figure caption.">
    <img src="/assets/images/young_planet.jpeg" alt="this is a placeholder image" style="width: 100%; height: auto;">
  </a>
  <figcaption>This is a nice AI generated figure. It might be nice my paper as well &#128521; <a href="https://ui.adsabs.harvard.edu/abs/2024A%26A...682A.129M/abstract">(Mantovan et al. 2024a)</a>.</figcaption>
</figure>

<div class="post-content">
<p>The mass of an exoplanet, combined with the radius from transit, allows us to precisely measure an exoplanet's inner bulk density and opens the door for subsequent in-depth characterisation. </p><p>An interesting subject of study are <strong>systems younger than 1 Gyr</strong>, which are crucial for understanding the early stages of planetary formation and evolution processes, including orbital migration, atmopsheric evaporation, and planetary impacts <a href="https://ui.adsabs.harvard.edu/abs/2019NatAs...3..416B/abstract">(e.g., Bonomo et al. 2019)</a>. However, it is challenging to identify and model such systems because of the strong magnetic <strong>activity</strong> of the host star that hides planetary signals. The substantial starspot activity on the stellar surface - typical of stars younger than 1 Gyr - generates intense periodic variations in the stellar flux and shape of the spectral lines, affecting both photometric and spectroscopic time series. Therefore, it is essential to mitigate stellar eﬀects, solve the degeneracy, and isolate the planetary signal. </p><p> Among the different approaches and techniques in this rapidly evolving ﬁeld, the <strong>Gaussian Process</strong> (GP) regression <a href="https://link.springer.com/book/10.1007/978-0-387-45528-0">(Bishop 2006)</a> can be used as a flexible model for correlated noise typically caused by the variability of the host star. Of particular importance in the context of young stars is the availability of additional indicators, obtained during RV extraction, that give information on the characteristics of spectral lines (e.g., width, asymmetry), which are also aﬀected by active regions, as well as spectral activity indicators which trace chromospheric emission in the cores of strong lines. In my work, I adopted the <strong>multidimensional GP framework</strong> proposed by <a href="https://ui.adsabs.harvard.edu/abs/2015MNRAS.452.2269R/abstract">Rajpaul et al. (2015)</a>, a powerful approach for modelling activity indicators simultaneously with RVs, disentangling them from planetary signals. The advent of space transit surveys has revolutionised the study of young planets, making it easier to discover exoplanets around young stars by ﬁrst identifying transiting signals <a href="https://ui.adsabs.harvard.edu/abs/2019A%26A...630A..81B/abstract">(e.g., Benatti et al. 2019)</a>. However, only a small sample of young exoplanets have well-constrained ages, radii, and masses.</p></div>

## Compact systems

<figure style="float: left; margin-right: 20px; max-width: 30%; margin-top: 5px; margin-bottom: 1px;">
  <a href="/assets/images/compact.png" class="image-popup" title="This is a figure caption.">
    <img src="/assets/images/compact.png" alt="this is a placeholder image" style="width: 100%; height: auto;">
  </a>
  <figcaption>Another amazing AI generated figure. And another nice paper of mine &#128521; <a href="https://ui.adsabs.harvard.edu/abs/2024A%26A...684L..17M/abstract">(Mantovan et al. 2024b)</a>.</figcaption>
</figure>

<div class="post-content">
<p>The precise measurement of the orbital architecture and bulk composition of exoplanets is essential to fully characterise multi-planet systems. Their architecture exhibits signiﬁcant diversity, with planets that span the whole range of masses and that are grouped in a wide variety of dynamical conﬁgurations (e.g., diﬀerent multiplicity, orbital spacings, mutual inclinations, see <a href="https://ui.adsabs.harvard.edu/abs/2011ApJS..197....8L/abstract">Lissauer et al. 2011</a>; <a href="https://ui.adsabs.harvard.edu/abs/2015ARA%26A..53..409W/abstract">Winn & Fabrycky 2015</a>). However, it is noteworthy that short-period giant planets (P ≲ 10 days) are more frequently isolated planets compared to other classes of exoplanets (<a href="https://ui.adsabs.harvard.edu/abs/2016ApJ...825...98H/abstract">Huang et al., 2016</a>). When they have companions, these tend to be massive (≥ 1 MJup) long-period planets with P > 200 days (<a href="https://ui.adsabs.harvard.edu/abs/2014ApJ...785..126K/abstract">Knutson et al., 2014</a>). The only known exceptions so far are WASP-47 (<a href="https://ui.adsabs.harvard.edu/abs/2015ApJ...812L..18B/abstract">Becker+2015</a>), Kepler-730 (<a href="https://ui.adsabs.harvard.edu/abs/2019ApJ...870L..17C/abstract">Cañas+2019</a>), TOI-1130 (<a href="https://ui.adsabs.harvard.edu/abs/2020ApJ...892L...7H/abstract">Huang+2020</a>), WASP-132 (<a href="https://ui.adsabs.harvard.edu/abs/2022AJ....164...13H/abstract">Hord+2022</a>), TOI-2000 (<a href="https://ui.adsabs.harvard.edu/abs/2023MNRAS.524.1113S/abstract">Sha+2023</a>), and TOI-5398 (<a href="https://ui.adsabs.harvard.edu/abs/2024A%26A...682A.129M/abstract">Mantovan+2024a</a>). </p><p> The lack of nearby, low-mass, small companions initially supported the idea that short-period gas giants form beyond the snow line and then migrate inwards via high-eccentricity migration (HEM). In this scenario, the eccentricity of a gas giant is excited by close encounters with other giants (<a href="https://ui.adsabs.harvard.edu/abs/1996Sci...274..954R/abstract">Rasio & Ford 1996</a>) or by Kozai's interaction with a distant stellar companion (<a href="https://ui.adsabs.harvard.edu/abs/2001ApJ...562.1012E/abstract">Eggleton & Kiseleva-Eggleton 2001</a>). If the periastron distance is small enough, the orbit circularises and shrinks due to star-planet tidal interaction. Such dynamical instability is expected to be destructive for low-mass bodies in the path of the migrating giant (<a href="https://ui.adsabs.harvard.edu/abs/2015ApJ...808...14M/abstract">Mustill+2015</a>), inevitably leaving short-period giants in loneliness. However, some short-period giants have inner companions and an alternative mechanism may explain their formation. Under disc migration, tidal interactions with the protoplanetary disc move the cold giant to its present location (<a href="https://ui.adsabs.harvard.edu/abs/1996Natur.380..606L/abstract">Lin+1996</a>), sweeping material along its resonances to form inner planets (<a href="https://ui.adsabs.harvard.edu/abs/2006Sci...313.1413R/abstract">Raymond+2006</a>).</p> 
</div>

## RM effect

<div class="post-content">
<p> The two migration mechanisms can imprint different signatures in the obliquity -- the angle between a planet's orbital axis and its host star spin axis -- that can be detected with in-transit RVs through the Rossiter-McLaughlin eﬀect (RM, see <a href="https://ui.adsabs.harvard.edu/abs/2018haex.bookE...2T/abstract">Triaud et al. 2018</a> for a review). As the star rotates, one portion of the photosphere is seen coming towards the observer (blue-shifted), while the other one is moving away (red-shifted). When the planet passes in front of the star, it blocks some of the blue- and red-shifted light, causing the stellar radial velocity to vary. The shape of this variation changes for diﬀerent conﬁgurations, depending on the alignment/misalignment of the orbital plane and also on the spin direction of the planetary orbit (prograde/retrograde). Scattering encounters (HEM scenario) tend to randomise orbital alignments, while disc-planet interactions typically keep planetary orbits coplanar. </p><p> The obliquity is hence a key diagnostic for the mechanisms of formation and orbital migration of exoplanets (e.g. <a href="https://ui.adsabs.harvard.edu/abs/2011Natur.473..187N/abstract">Naoz et al. 2011</a>), and it also plays a key role in atmospheric characterisation (<a href="https://ui.adsabs.harvard.edu/abs/2015ApJ...814L..24L/abstract">Louden & Wheatley, 2015</a>).</p>


</div>

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
