<!-- Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->
<template>
 <h1>{{ title }}</h1>
</template>

<script>
  export default {
    data(){
      return {
       title: 'Hello World'
      }
    },
    
  }
</script>

<style scoped>

</style>