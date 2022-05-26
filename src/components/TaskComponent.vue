<template>
  <div class="comp">
    <h2>{{ title }}</h2>
    <table>
      <tr>
        <th>Name</th>
        <th>Status</th>
      </tr>
      <tr v-bind:key="index" v-for="(task, index) in tasks" >
        <td> {{ task.name}}</td>
        <td> {{ task.completed ? "Yes" : "No"}}</td>
      </tr>
    </table>
  </div>
</template>


<script>
  export default {
    data(){
      return{
            tasks: [
                { name: "Task 1", completed: true },
                { name: "Task 2", completed: false },
                { name: "Task 3", completed: true },
                { name: "Task 4", completed: false}
              ],
            title: "Tasks Component"
      }
    }
  }
</script>

<style scoped>
  .comp{
    border: 1px solid red;
    margin: 5px;
    padding: 5px;
  }

</style>
