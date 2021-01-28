<template>
  <div id="app" class="container">
    <variable-width-columns />
  </div>
</template>

<script>
  //import TwoColumnLayout from '@/components/TwoColumnLayout'
  //import ThreeColumnLayout from '@/components/ThreeColumnLayout'
  //import AutoLayout from '@/components/AutoLayout'
  //import ColumnWrapping from '@/components/ColumnWrapping'
  //import ResponsiveLayout from '@/components/ResponsiveLayout'
  import VariableWidthColumns from '@/components/VariableWidthColumns'

  export default {
    name: 'App',
    components: {
      //TwoColumnLayout,
      //ThreeColumnLayout,
      //AutoLayout,
      //ColumnWrapping,
      //ResponsiveLayout,
      VariableWidthColumns
    }
  }
</script>

<style>

</style>