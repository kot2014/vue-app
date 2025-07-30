<template>
  <button @click="handleClick">{{ label }}</button>
</template>

<script>
export default {
  name: 'MyButton',
  props: {
    label: {
      type: String,
      default: 'Натисни мене'
    }
  },
  methods: {
    handleClick() {
      alert('Ти натиснув кнопку!')
    }
  }
}
</script>

<style scoped>
button {
  background-color: #42b983;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 6px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #369d70;
}
</style>
