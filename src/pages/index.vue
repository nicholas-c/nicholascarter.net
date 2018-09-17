<template>
  <div>
    <HelloWorld />
    <About />
    <Work />
  </div>
</template>

<script>
import HelloWorld from './../components/HelloWorld.vue'
import About from './../components/About.vue'
import Work from './../components/Work.vue'

export default {
  components: {
    HelloWorld,
    About,
    Work
  }
}
</script>

<style>
.container {
  width: 100%;
  max-width: 1440px;
  margin: 0 auto;
  padding-right: 1rem;
  padding-left: 1rem;
}
.container-lg {
  width: 100%;
  max-width: 1100px;
  margin: 0 auto;
  padding-right: 1rem;
  padding-left: 1rem;
}
.container-md {
  width: 100%;
  max-width: 850px;
  margin: 0 auto;
  padding-right: 1rem;
  padding-left: 1rem;
}
.container-sm {
  width: 100%;
  max-width: 568px;
  margin: 0 auto;
  padding-right: 1rem;
  padding-left: 1rem;
}
</style>
