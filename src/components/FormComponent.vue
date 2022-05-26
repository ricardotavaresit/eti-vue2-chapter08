<template>
  <div>
    {{ msg }}
  </div>
</template>


<script>
  export default {
    data(){
      return {
        msg: "I'm a green Form"
      }
    }
  }

</script>

<style scoped>
  div{
    background: green;
  }
</style>
