<template>
   <h1>{{ Title }}</h1> 

  
</template>

<script>
    export default {
        name: "AppTitle",
        data(){
            return{
                Title: 'Hello World'
                
            }
        }
        
    }
</script>

<style scoped>
h1 {
    text-align: center;
}

</style>