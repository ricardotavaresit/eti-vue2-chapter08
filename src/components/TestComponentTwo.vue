<template>
  <div class="comp">
    <h2>{{ title }}</h2>
    <p>Test Component Two - {{ msg }} </p>
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
    color: blue
  }

  .comp{
    border: 1px solid orangered;
    margin: 5px;
    padding: 5px;
  }
</style>
