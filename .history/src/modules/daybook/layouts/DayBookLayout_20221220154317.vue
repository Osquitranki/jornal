<template>
    <Navbar/>
    <div class="d-flex">
    <div class="col-4">
      <
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
         Navbar: defineAsyncComponent(() => import('../components/Nav-bar.vue')),
         EntryList: defineAsyncComponent(() => import('../components/Entry-list.vue'))
     }

}
</script>
