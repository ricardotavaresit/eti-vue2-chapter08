<template>
  <div class="comp">
    <h2>{{ title }}</h2>
    {{ msg }}
  </div>
</template>

<script>
  export default {
    data(){
      return {
        msg: "I'm a green Form",
        title: "Form Component"
      }
    }
  }

</script>

<style scoped>
  div{
    background: green;
  }
</style>
