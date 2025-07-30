<template>
  <div>
    <HeaderComponent />
    <slot />
  </div>
</template>

<script>
import HeaderComponent from '../components/HeaderComponent.vue'
// import Footer from '../components/Footer.vue'

export default {
  components: {
    HeaderComponent,
    // Footer
  }
}
</script>
