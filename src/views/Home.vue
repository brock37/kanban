<template>
  <div class="home bg-secondary pb-5 d-flex flex-wrap">
    <taskList></taskList>
    <taskList></taskList>
    <taskList></taskList>
    <taskList></taskList>
  </div>
</template>

<script>
// @ is an alias to /src
import taskList from '@/components/taskList.vue'


export default {
  name: 'Home',
  components: {
    taskList
  }
}
</script>
