<link rel="stylesheet" href="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.css">
<script src="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.js"></script>

# Awesome/Automatic SDR

Just another sdr project.

``awesome - automatic - sdr``

[![shields.io](https://img.shields.io/badge/license-Apache2-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.txt)

Author: [Maximilian Bundscherer](https://bundscherer-online.de)

- Please use project page [A-SDR](https://maxbundscherer.github.io/a-sdr/)

## Overview

Welcome to my [Software-defined radio (SDR)](https://en.wikipedia.org/wiki/Software-defined_radio) page.

Normally I am a computer scientist with a focus on data science and software engineering located in Germany near Munich (QTH JN58). Today I want to **share my radio signal hobby** with all of you. I currently have no amateur radio license, but I am on it.

Instead of learning for the amateur radio license, I am dealing with **automatic signal identification, classification, monitoring, demodulation & decoding of voice, data & natural radio signals**. I am using traditional methods and machine learning (ml)/ artificial intelligence (ai) techniques for these points.

**This page is about automatic (live) monitoring/reporting of different radio signals and sdr related topics**. Unfortunately, this page is under construction and is not complete. This page has started on 04-Mar-2022 and there are a lot of things to publish and do. So check back from time to time.

I am starting with publishing ft8-signal maps received with my loop antenna. At the moment I am waiting for the ordered server hardware. Currently, I am using a Raspberry Pi, GNU Radio & self-developed tools/software in Python and C++. Because my setup is currently based on a Raspberry Pi I can not do all steps automatically in time. **So until the server hardware receives I publish new stuff from time to time**.

## FT8

### Static

<p>
Please select one of these modes:<br />
<ul>
  <li>Dark with sizes</li>
  <li>Dark without sizes</li>
  <li>Bright with sizes</li>
  <li>Bright without sizes</li>
</ul>
</p>

<div class="accordion-container" id="ac-static">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Dark with sizes</button>
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
      <button class="ac-trigger">Dark without sizes</button>
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
      <button class="ac-trigger">Bright with sizes</button>
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
      <button class="ac-trigger">Bright without sizes</button>
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

### Filtered

<p>
Please select one of these modes:<br />
<ul>
  <li>By Band</li>
  <li>By Time</li>
</ul>
</p>

<div class="accordion-container" id="ac-filtered">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">By Band</button>
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
      <button class="ac-trigger">By Time</button>
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
  new Accordion("#ac-filtered");
</script>