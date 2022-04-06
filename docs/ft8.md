### Maps

There are two sections: **Default Map** and **Filtered Map**.

#### Default Map

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

#### Filtered Map

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

There are two sections: **Time plots** and **Stats**.

<iframe src="output/time-stats-count.html" width="100%" height="400" frameborder="0"></iframe>

<iframe src="output/ov-specs.html" width="100%" frameborder="0"></iframe>

#### Time plots

<p>
Please select one of these modes:<br />
<ul>
  <li>By radio band</li>
  <li>By frequency</li>
</ul>
</p>

<div class="accordion-container" id="ac-time-plots">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">By radio band</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/ov-band-by-time.html">Go</a> to full size<br />
      <iframe src="output/ov-band-by-time.html" width="100%" height="400" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

   <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">By frequency</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/ov-frequency-by-time.html">Go</a> to full size<br />
      <iframe src="output/ov-frequency-by-time.html" width="100%" height="600" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

</div>

<script>
  new Accordion("#ac-time-plots", {openOnInit: [0]});
</script>

#### Radio Bands Plots

<p>
Please select one of these modes:<br />
<ul>
  <li>Time series</li>
  <li>All</li>
</ul>
</p>

<div class="accordion-container" id="ac-time-band-plots">

  <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">Time series</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/animation-counts-band.html">Go</a> to full size<br />
      <iframe src="output/animation-counts-band.html" width="100%" height="400" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

   <!-- Item START -->
  <div class="ac">
    <h2 class="ac-header">
      <button class="ac-trigger">All</button>
    </h2>
    <div class="ac-panel">
    <p class="ac-text">
      <a href="output/global-stats-band.html">Go</a> to full size<br />
      <iframe src="output/global-stats-band.html" width="100%" height="400" frameborder="0"></iframe>
    </p>
    </div>
  </div>
  <!-- Item STOP -->

</div>

<script>
  new Accordion("#ac-time-band-plots", {openOnInit: [0]});
</script>

#### Stats

<p>
Please select one of these modes:<br />
<ul>
  <li>Frequent callsigns</li>
  <li>Frequent grids</li>
</ul>
</p>

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
