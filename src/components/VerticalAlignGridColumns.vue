<template>
  <div class="vertical-align-grid-columns">
    <!-- align the grid columns vertically at the top, middle and bottom of a container -->
    <div class="row align-items-start">
      <div class="col border">Column one</div>
      <div class="col border">Column two</div>
      <div class="col border">Column three</div>
    </div>
    <div class="row align-items-center">
      <div class="col border">Column one</div>
      <div class="col border">Column two</div>
      <div class="col border">Column three</div>
    </div>
    <div class="row align-items-end">
      <div class="col border">Column one</div>
      <div class="col border">Column two</div>
      <div class="col border">Column three</div>
    </div>

    <!-- Individual columns inside a row can also be aligned vertically -->
    <div class="row">
      <div class="col align-self-start border">Column one</div>
      <div class="col align-self-center border">Column two</div>
      <div class="col align-self-end border">Column three</div>
    </div>
  </div>
</template>