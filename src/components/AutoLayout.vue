<template>
  <div class="auto-layout">
    <!--Row with two equal columns-->
    <div class="row">
      <div class="col border">Column one</div>
      <div class="col border">Column two</div>
    </div>

    <!--Row with three equal columns-->
    <div class="row">
      <div class="col border">Column one</div>
      <div class="col border">Column two</div>
      <div class="col border">Column three</div>
    </div>

    <!-- Set the width of one column and let the sibling columns automatically resize around it equally -->
    <!-- You may use the predefined grid classes or inline widths -->

    <!--Row with two equal columns-->
    <div class="row">
      <div class="col border">Column one</div>
      <div class="col border">Column two</div>
    </div>

    <!--Row with three columns divided in 1:2:1 ratio-->
    <div class="row">
      <div class="col border">Column one</div>
      <div class="col-sm-6 border">Column two</div>
      <div class="col border">Column three</div>
    </div>

  </div>
</template>
