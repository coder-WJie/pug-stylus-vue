<template>
  <div id="app">
    <!-- <TestPug></TestPug> -->
    <TestStylus></TestStylus>
  </div>
</template>

<script>
import TestPug from './components/testpug/TestPug'
import TestStylus from './components/test-stylus/TestStylus.vue'

export default {
  name: 'App',
  components: {
    TestPug,
    TestStylus
}
}
</script>

<style>

</style>
