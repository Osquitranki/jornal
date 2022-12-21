<template>
    <h1> DayBook Layout</h1>
    <Nav-bar/>
</template>


<script>
import {defineAsyncComponent} from 'vue'

export default {
     components: {
         Nav-bar: defineAsyncComponent(() => import('../components/Nav-bar.vue'))
     }

}
</script>
