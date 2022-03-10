<link rel="stylesheet" href="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.css">
<script src="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.js"></script>

# Awesome/Automatic SDR

Just another Software-defined radio (SDR) project and page.

``sdr - radio - signal - classification - machine learning - python - rtl - gnuradio``

[![shields.io](https://img.shields.io/badge/license-Apache2-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.txt)

Author: [Maximilian Bundscherer](https://bundscherer-online.de)

- Please use project page [A-SDR](https://maxbundscherer.github.io/a-sdr/)

## Overview

Welcome to my [Software-defined radio (SDR)](https://en.wikipedia.org/wiki/Software-defined_radio) page.

Normally I am a computer scientist with a focus on data science and software engineering located in Germany near Munich (QTH JN58). Today I want to **share my radio signal hobby** with all of you. I currently have no amateur radio license, but I am on it.

Instead of learning for the amateur radio license, I am dealing with **automatic signal identification, classification, monitoring, demodulation & decoding of voice, data & natural radio signals**. I am using traditional methods and machine learning (ml) / artificial intelligence (ai) techniques for these points.

**This page is about automatic (live) monitoring/reporting of different radio signals and sdr related topics**. Unfortunately, this page is under construction and is not complete. This page has started on 04-Mar-2022 and there are a lot of things to publish and do. So check back from time to time.

I am starting with publishing ft8-signal maps received with my loop antenna. At the moment I am waiting for the ordered server hardware. Currently, I am using a Raspberry Pi, GNU Radio & self-developed tools/software in Python and C++. Because my setup is currently based on a Raspberry Pi I can not do all steps automatically in time. **So until the server hardware is delivered I publish new stuff from time to time**.

## FT8

There are three sections: **Default Map**, **Filtered Map**, **Info**. Timestamps are specified in UTC.

### Default Map

<p>
Please select one of these modes:<br />
<ul>
  <li>Dark map visualizing influence of different radio amateurs</li>
  <li>Dark map visualizing all signals equal</li>
  <li>Bright map visualizing influence of different radio amateurs</li>
  <li>Bright map visualizing all signals equal</li>
</ul>
</p>

<div class="accordion-container" id="ac-static">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Dark map with influence</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/dark-size.html">Go</a> to full size<br />
      <iframe src="output/dark-size.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

   <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Dark map without influence</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/dark-no-size.html">Go</a> to full size<br />
      <iframe src="output/dark-no-size.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Bright map with influence</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/bright-size.html">Go</a> to full size<br />
      <iframe src="output/bright-size.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

   <!-- Item START -->
   <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Bright map without influence</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/bright-no-size.html">Go</a> to full size<br />
      <iframe src="output/bright-no-size.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

</div>

<script>
  new Accordion("#ac-static", {openOnInit: [0]});
</script>

### Filtered Map

<p>
Please select one of these modes:<br />
<ul>
  <li>By radio band</li>
  <li>By time</li>
</ul>
</p>

<div class="accordion-container" id="ac-filtered">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">By radio band</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/animation-band.html">Go</a> to full size<br />
      <iframe src="output/animation-band.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

   <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">By time</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/animation-time.html">Go</a> to full size<br />
      <iframe src="output/animation-time.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

</div>

<script>
  new Accordion("#ac-filtered", {openOnInit: [0]});
</script>

### Info

<iframe src="output/ov-specs.html" width="100%" frameborder="0"></iframe>

### Stats

<div class="accordion-container" id="ac-stats">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Frequent callsigns</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/ov-callsigns.html">Go</a> to full size<br />
      <iframe src="output/ov-callsigns.html" width="100%" height="400" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

   <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Frequent grids</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/ov-grids.html">Go</a> to full size<br />
      <iframe src="output/ov-grids" width="100%" height="400" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

</div>

<script>
  new Accordion("#ac-stats", {openOnInit: [0]});
</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-72DH61K0HZ"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-72DH61K0HZ');
</script>