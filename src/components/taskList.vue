<template lang="html">
  <div class="task-list bg-light container mt-2 pb-2 px-0 mx-auto">
    <h3 class="bg-primary text-light d-flex justify-content-center align-items-center">{{ title }}</h3>
    <div class="container">
      <task></task>
      <task></task>
      <task></task>
    </div>


  </div>

</template>

<script>
import task from './task.vue'

export default {
  components :{
    task
  },
  data(){
    return{
      title : "Titre de la liste"
    }
  }
}
</script>

<style lang="css" scoped>
.task-list {

    max-width: 90%;
}
h3{
  font-size: 14px;
@media (min-width: 768px) {
  .task-list{
    max-width: 33%;
  }

}
</style>
