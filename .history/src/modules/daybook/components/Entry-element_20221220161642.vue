<template>
  <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({name: 'entry', params: {id:10} })">
   <div class="entry-title d-flex">
    <span class="text-sucess fs-5 fw-blod">15</span>
    <span class="mx-1 fs-5">Julio</span>
    <span class="mx-2 fw-light">2021, jueves</span>
   </div>
   <div class="entry-description">
   Exercitation dolore quis dolor eiusmod incididunt occaecat eu Lorem ipsum ullamco id exercitation cillum. Adipisicing aliquip nostrud pariatur cillum tempor ad et. Consectetur sit in aliqua veniam. Duis pariatur duis laborum ipsum velit amet.
   </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2 all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2 all ease-in;
    }
}
    .entry-description {
        font-size: 12 px;
    }
</style>
