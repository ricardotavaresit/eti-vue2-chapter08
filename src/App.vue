<template>
  <div id="app" class="comp">
    <h2>{{ title }}</h2>
     Teste {{ msg }}
     <test-component-one />
     <test-component-two />
     <form-component />
     <task-component />

  </div>
</template>

<script>
import TestComponentOne from "./components/TestComponentOne";
import TestComponentTwo from "./components/TestComponentTwo";
import FormComponent from "./components/FormComponent";
import TaskComponent from "./components/TaskComponent"

export default {
  data() {
    return {
      msg: 'Vue.js Course',
      title: "App Component"
    }
  },
  components:{
    TestComponentOne,
    TestComponentTwo,
    FormComponent,
    TaskComponent
  }
}
</script>

<style>
.comp{
  border: 1px solid blue;
  margin: 5px;
  padding: 5px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
