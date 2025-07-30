<template>
  <div>
    <h2>Головна сторінка</h2>

<MyButton label="Ласкаво просимо!"/>
  </div>
</template>

<script>
import MyButton from '../components/MyButton.vue'
export default {
  name: 'HomeView',
  components:{
    MyButton}
}
</script>
