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
#sidemenu {
    display: flex;
    justify-content: space-between;
    background-color: #fdfdfd;
    border-bottom: solid 2px #FFB100;
    height: 95px;
    padding: 0 16px;
}

img{
    width: 40%;
}

@media screen AND (min-width: 1024px){ 
    .desktop{
        display: none;
    }

}

.logo {
    width: 40%;
}

.bar{
  display: block;
  width: 25px;
  height: 3px;
  margin: 5px 0px;
  background-color: #FFB100;
}



.container-fluid{
    padding: 0;
}
</style>