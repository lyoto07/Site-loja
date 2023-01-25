<template>
    <div id="sidemenu">
        <nav class="navbar bg-body-tertiary fixed-top">
            <div class="container-fluid">
                <img src="../assets/img/logo2.svg" alt="Logo Casa de Rações laranjeiras" class="logo">
                <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas"
                    data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar">
                        <span class="bar"></span>
                        <span class="bar"></span>
                        <span class="bar"></span>
                </button>
                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar"
                    aria-labelledby="offcanvasNavbarLabel">
                    <div class="offcanvas-header">
                        <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Offcanvas</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                    </div>
                    <div class="offcanvas-body">
                        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Link</a>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                    aria-expanded="false">
                                    Dropdown
                                </a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">Action</a></li>
                                    <li><a class="dropdown-item" href="#">Another action</a></li>
                                    <li>
                                        <hr class="dropdown-divider">
                                    </li>
                                    <li><a class="dropdown-item" href="#">Something else here</a></li>
                                </ul>
                            </li>
                        </ul>
                        <form class="d-flex mt-3" role="search">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                            <button class="btn btn-outline-success" type="submit">Search</button>
                        </form>
                    </div>
                </div>
            </div>
        </nav>
        <!-- <button class="sidemenu __btn">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
	</button>
    <button type="button" class="btn btn-primary">Primary</button>

    <transition name="translateX">
      <nav v-show="navOpen">
        <div class="sidemenu__wrapper">
          <ul class="sidemenu__list">
            <li class="sidemenu__item"><a href="">Home</a></li>
            <li class="sidemenu__item"><a href="">Sobre nos</a></li>
            <li class="sidemenu__item"><a href="">Nossos serviços</a></li>
            <li class="sidemenu__item"><a href="">Mercado</a></li>
            <li class="sidemenu__item"><a href="">Contato</a></li>
          </ul>
        </div>
      </nav>
    </transition> -->
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
    display: flex;
    justify-content: space-between;
    background-color: #FFFFF0;
}
.navbar{
    border-bottom: solid 2px #FFB100;
    height: 95px;
    padding: 0 16px;
}

.logo {
    width: 40%;
}

.navbar-toggler,.offcanvas .offcanvas-end{
    border: none;
}

.bar{
  display: block;
  width: 25px;
  height: 3px;
  margin: 5px 0px;
  background-color: #FFB100;
}

.navbar-toggler,
.navbar-toggler:focus,
.navbar-toggler:active,
.navbar-toggler-icon:focus {
    outline: none;
    border: none;
    box-shadow: none;
    padding: 0px;
}

.container-fluid{
    padding: 0;
}
</style>