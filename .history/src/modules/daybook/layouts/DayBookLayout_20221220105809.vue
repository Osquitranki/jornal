<template>
    <h1> DayBook Layout</h1>
    <Navbar/>
</template>


<script>
import {defineAsyncComponent} from 'vue'

export default {
     components: {
         Navbar: defineAsyncComponent(() => import('..'))
     }

}
</script>
