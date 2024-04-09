<!-- Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->
<template>
  <body>
    <AppTitle />
   <AppHero />
  </body>
 
</template>

<script>
import  AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
export default {
  components:{
      AppTitle,
      AppHero
    },
  data() {
 
    return {
      
    }
  },

}
</script>

<style scoped></style>