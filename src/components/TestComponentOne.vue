<template>
  <div class="comp">
    <p>Test One - {{ msg }}</p>
  </div>
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

  .comp{
    border: 1px solid yellow;
    margin: 5px;
    padding: 5px;
  }
</style>
