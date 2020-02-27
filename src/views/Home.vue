<template>
  <div class="home bg-secondary">
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
