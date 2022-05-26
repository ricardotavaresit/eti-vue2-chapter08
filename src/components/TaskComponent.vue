<template>
  <div>
    <table>
      <tr>
        <th>Name</th>
        <th>Status</th>
      </tr>
      <tr v-bind:key="index" v-for="(task, index) in tasks" >
        <td> {{ task.name}}</td>
        <td> {{ task.completed}}</td>
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
              ]
      }
    }
  }
</script>

<style scoped>

</style>
