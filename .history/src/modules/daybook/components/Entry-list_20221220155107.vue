<template>
  <div class="entry-list-container">
    <div class="px-2 pt-2">
        <input type="text" class="form-control" placeholder="Buscar entrada" />
    </div>

  <div class="entry-scrollarea">
    <Entry v-for="item in 100"
        :key="item">
        <h2>Entry</h2>
        
  </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
