<template>
    <Navbar/>
    
</template>


<script>
import {defineAsyncComponent} from 'vue'

export default {
     components: {
         Navbar: defineAsyncComponent(() => import('../components/Nav-bar.vue'))
     }

}
</script>
