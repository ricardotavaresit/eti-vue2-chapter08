<template>
  <div class="comp">
    <h2>{{ title }}</h2>
    <p>Test One - {{ msg }}</p>
  </div>
</template>

<script>
  export default {
    data(){
      return{
        msg: "Course Vue JS",
        title: "Test One Component"
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
