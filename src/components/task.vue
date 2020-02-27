<template lang="html">
  <div class="container my-2 rounded">
    <label for="completed"> {{ text }}</label>
    <input type="checkbox" name="completed" v-bind:value="completed">
  </div>

</template>

<script>
export default {
  data(){
    return{
      text : "Ma tache a accomplir",
      completed : false,
    }
  }
}
</script>

<style lang="css" scoped>
.container{
  background: #EFE6D8;
}
</style>
