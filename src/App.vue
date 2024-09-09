<script>
/* 
export default:
mi permette di espotare il file, in questo caso il file si chiama App.
Lo ritrovo collegato in main.js --> "createApp(App)"
*/
export default {
  data() {
    return {
      message: 'Hello world'
    }
  },
}

</script>

<template>

  <div>
    <h1>
      {{ message }}
    </h1>
  </div>

</template>

<style scoped>

</style>
