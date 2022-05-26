<template>
  <div class="comp">
    <p>Test Component Two - {{ msg }} </p>
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
    color: blue
  }

  .comp{
    border: 1px solid orangered;
    margin: 5px;
    padding: 5px;
  }
</style>
