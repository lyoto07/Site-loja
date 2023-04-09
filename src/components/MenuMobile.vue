<template>
    <div id="sidemenu">
        <img src="../assets/img/logo2.svg" alt="">
        <button class="buttonMenu btn " type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasWithBothOptions" aria-controls="offcanvasWithBothOptions">
            <span class="bar"></span>
            <span class="bar"></span>
            <span class="bar"></span>
        </button> 

        <div class="offcanvas offcanvas-end w-50" data-bs-scroll="true" tabindex="-1" id="offcanvasWithBothOptions" aria-labelledby="offcanvasWithBothOptionsLabel">
            <div class="offcanvas-header d-flex justify-content-end">
                <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
                <nav class="navbar navbar-expand-sm bg-body-tertiary">
                    <div class="container-fluid">
                        <div class="" id="navbarNav">
                            <ul class="navbar-nav flex-column">
                                <li class="nav-item">
                                <a class="nav-link active fs-3 fw-bolder" aria-current="page" href="#">Home</a>
                                </li>
                                <li class="nav-item">
                                <a class="nav-link fs-3" href="#">Features</a>
                                </li>
                                <li class="nav-item">
                                <a class="nav-link fs-3" href="#">Pricing</a>
                                </li>
                                <li class="nav-item">
                                <a class="nav-link fs-3">Disabled</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </nav>
            </div>
        
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'menuPrincipal',

});
</script>

<style scoped>

#sidemenu {
    font-family: 'Nunito';
}

@media screen AND (min-width: 1024px){ 
    #sidemenu{
        display: none !important;
    }
    

}

#sidemenu {
    display: flex;
    justify-content: space-between;
    background-color: #FFFFF0;
    border-bottom: solid 2px #FFB100;
    height: 95px;
    padding: 0 16px;
}

img{
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