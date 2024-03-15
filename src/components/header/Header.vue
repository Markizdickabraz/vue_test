<template>
  <header class="header">
      <div class="container__fluid">
        <a class="logo__link" href="#">BrandName</a>
        <button class="mobile__menu--open nav__btn" @click="toggleMenu"> 
          <i class="pi pi-bars" aria-hidden="true"></i>
        </button>
      </div>
        <nav class="navigation" id="Home" :class="{ 'open': isMenuOpen }">
          <ul class="nav__list">
            <li class="nav__item"><a href="#Home" class="nav__link">Home</a></li>
            <li class="nav__item"><a href="#Product" class="nav__link">Product</a></li>
            <li class="nav__item"><a href="#Pricing" class="nav__link">Pricing</a></li>
            <li class="nav__item"><a href="#Contact" class="nav__link">Contact</a></li>
          </ul>
          <hr class="line">
          <div class="auth__nav">
            <a class="login nav__link" href="#Home">Login</a>
            <a class="join" href="#Home">JOIN US
                <img class="join__arrow" src="@/assets/img/vector-right_arrow.svg" alt="right arrow">
            </a>
          </div>
        </nav>
  </header>
</template>

<script>
import { ref } from 'vue';

export default {
  name: 'AppHeader',
  setup() {
    const isMenuOpen = ref(false);

    const toggleMenu = () => {
      isMenuOpen.value = !isMenuOpen.value;
    };

    return {
      isMenuOpen,
      toggleMenu
    };
  }
};
</script>

<style>
.header {
    max-width: 1440px;
}

.container__fluid {
    margin: 0 auto;
    padding-left: calc(1.5rem * 0.5);
    padding-right: calc(1.5rem * 0.5);
    width: 100%;
    display: flex;
    justify-content: space-between;
}

.logo__link {
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 32px;
    letter-spacing: 0.1px;
    color: #ffffff;
    transition: all 0.3s ease;
    text-decoration: none;
    padding-top: 0.5rem;
}

.logo__link:hover {
    color: #8d5cf6;
}

.navigation {
    display: none;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    width: 90%;
}

.navigation.open {
  display: block;
  flex-basis: 100%;
  flex-grow: 1;
  text-align: center;
}

.nav__link {
  font-style: normal;
  font-weight: 700;
  font-size: 14px;
  line-height: 24px;
  text-align: center;
  letter-spacing: 0.2px;
  color: #c5c5c5;
  transition: all 0.3s ease;
  text-decoration: none;
  padding: 0.5rem 0;
}
.nav__link:hover {
  color: #ffffff;
}

.nav__btn {
  color: #ffffff;
    margin-top: 0.5rem;
    padding-top:0.25rem;
    padding-bottom: 0.25rem;
    padding-left: 0.75rem;
    padding-right: 0.75rem;
    font-size: 1.5rem;
    line-height: 1rem;
    border-radius: 0.375rem;
    border: 1px solid rgba(0, 0, 0, 0.1);
    width: 1.5em;
    height: 1.5em;
    cursor: pointer;
}
.line {
    border: 0;
    border-top: 2px solid #fff;
    margin-top: 5px;
    margin-bottom: 5px;
    opacity: 0.25;
}

.auth__nav {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.join {
    padding: 5px 15px;
    border-radius: 5px;
    background-color: #8d5cf6;
    transition: all 0.3s ease;
    color: white;
    text-decoration: none;
}
.join:hover{
    background-color: #422a75;
}

.join_arrow {
    margin-left: 15px;
    transition: all 0.3s ease;

}.join:hover .join__arrow {
    margin-left: 20px;
}
</style>