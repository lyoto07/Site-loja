<template>
    <menuMobile />
    <menuDesktop/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import menuMobile from './MenuMobile.vue';
import menuDesktop from './MenuDesk.vue'

export default defineComponent({
    name: 'menuPrincipal',
    components: {
        menuMobile,
        menuDesktop
    }

});
</script>

<style scoped>
</style>