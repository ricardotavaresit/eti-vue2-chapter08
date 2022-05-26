<template>
  <p>Test One - {{ msg }}</p>
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
    color: red;
  }
</style>
