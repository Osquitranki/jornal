<template>
    <Navbar/>
    <div class="d-flex">
    <div class="col-4">
       eNTYlIST
    </div>
    <div class="col">
      <router-view />
    </div>
  </div>
</template>


<script>
import {defineAsyncComponent} from 'vue'

export default {
     components: {
         Navbar: defineAsyncComponent(() => import('../components/Nav-bar.vue'))
         Navbar: defineAsyncComponent(() => import('../components/Nav-bar.vue'))
     }

}
</script>
