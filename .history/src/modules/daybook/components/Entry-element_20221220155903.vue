<template>
  <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params: {id:10} })">
  <div class="entry-title d-flex">
    <span class="text-sucess fs-5 fw-flod">15</span>
    <span class="mx-1 fs-5">Julio</span>
    <span class="mx-2 fw-light">2021, jueves</span>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
