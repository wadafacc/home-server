<template>
  <div class="container-view">
    <div v-if="state == 0">
      <Statistics />
    </div>
    <div v-if="state == 1">
      <Containers />
    </div>
    <div v-if="state == 2">
      <Drives />
    </div>
  </div>
</template>

<style scoped src="~/styles/container.css">
</style>

<script>
export default {};
</script>