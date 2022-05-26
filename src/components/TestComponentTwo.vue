<template>
  <p>Test Component Two - {{ msg }} </p>
</template>

<script>
  export default {
    data(){
        return{
          msg: "Course Vue JS"
        }
    }
  }
</script>

<style scoped>
  p{
    color: blue
  }
</style>
