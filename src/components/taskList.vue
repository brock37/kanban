<template lang="html">
  <div class="container bg-light mx-auto mt-1 pb-2">
    <h3 class="bg-primary text-light mx-0">{{ title }}</h3>
    <task></task>
    <task></task>
    <task></task>

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
h3{
  font-size: 14px;
}
</style>
