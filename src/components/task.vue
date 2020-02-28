<template lang="html">
  <div class="task container-sm rounded mb-2 px-2 d-flex justify-content-end align-items-center">
    <label for="completed"> {{ text }}</label>
    <input type="checkbox" name="completed" v-bind:value="completed" class="check">
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
.task{
  background: #EFE6D8;
  min-height: 50px;
}
.check {
  height: 1rem;
  width: 1rem;
}

label{
  flex : 1;
  text-align: center;
}
</style>
