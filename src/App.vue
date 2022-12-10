<template>
  <div>
    <nav-bar/>
    <carrossel-component />
  </div>
</template>

<script>
import CarrosselComponent from '@/components/CarrosselComponent.vue'
import NavBar from '@/components/NavBar.vue'



export default {
  name: 'App',
  components: {
    NavBar,
    CarrosselComponent
    
  }
}
</script>

<style>

</style>
