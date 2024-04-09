<template>
 <body>
    <img :src="image" alt="sfondo">
 </body>
    
 
</template>

<script>
    export default {
      name: "AppHero",
        data(){
            return {
               image: "/img/image.jpg"
                
                

            }
        }
    }
</script>

<style scoped>
body {
    width: 1000px;
    margin: 0 auto;
   
}
img {
    width: 100%;
}

</style>