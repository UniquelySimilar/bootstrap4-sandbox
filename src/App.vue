<template>
  <div id="app" class="container">
    <horizontal-align-grid-columns />
  </div>
</template>

<script>
  //import TwoColumnLayout from '@/components/TwoColumnLayout'
  //import ThreeColumnLayout from '@/components/ThreeColumnLayout'
  //import AutoLayout from '@/components/AutoLayout'
  //import ColumnWrapping from '@/components/ColumnWrapping'
  //import ResponsiveLayout from '@/components/ResponsiveLayout'
  //import VariableWidthColumns from '@/components/VariableWidthColumns'
  //import VerticalAlignGridColumns from '@/components/VerticalAlignGridColumns'
  import HorizontalAlignGridColumns from '@/components/HorizontalAlignGridColumns'

  export default {
    name: 'App',
    components: {
      //TwoColumnLayout,
      //ThreeColumnLayout,
      //AutoLayout,
      //ColumnWrapping,
      //ResponsiveLayout,
      //VariableWidthColumns,
      //VerticalAlignGridColumns
      HorizontalAlignGridColumns
    }
  }
</script>

<style>

</style>