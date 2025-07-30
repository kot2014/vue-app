<template>
  <header>
    <h1>Заголовок</h1>
<MyButton label="gg"/>
  </header>
</template>

<script>
import MyButton from '../components/MyButton.vue'
export default {
  name: 'HeaderComponent',
  components:{
    MyButton
  }
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between; /* розділяє простір між елементами */
  align-items: center;            /* вирівнює по вертикалі */
  padding: 10px 20px;
  position: relative;
}

header h1 {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  margin: 0;
}

header button {
  margin-left: auto;
}
</style>
