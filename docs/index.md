<link rel="stylesheet" href="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.css">
<script src="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.js"></script>

# Awesome/Automatic SDR

Just another sdr project.

``awesome - automatic - sdr``

[![shields.io](https://img.shields.io/badge/license-Apache2-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.txt)

Author: [Maximilian Bundscherer](https://bundscherer-online.de)

- Please use project page [A-SDR](https://maxbundscherer.github.io/a-sdr/)
## FT8

### Static

<p>
Please select on of this modes:<br />
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
Please select on of this modes:<br />
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