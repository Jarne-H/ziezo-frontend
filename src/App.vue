<script setup>
//import router view
import { useRouter, useRoute } from 'vue-router'
// import figtree font from url 

</script>

<template>
    <nav>
        <div class="nav-logo">
        <img src="../public/images/Logo.png" alt="Ziezo Logo">
        </div>
        <div class="nav-menu">
        <ul>
            <li>Thuispagina</li>
            <li>Berichten</li>
            <li>Mijn Klusjes</li>
            <li>Profiel</li>
        </ul>
        </div>
        <div class="nav-details">
        <ul>
          <li>Hulp Nodig?</li>
          <li>Contact Info</li>
          <li>Instellingen</li>
        </ul>
        </div>
    </nav>
    <RouterView></RouterView>
</template>

<style scoped>
nav {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-left: 0px;
  padding: 24px 16px;
  gap: 48px;
  width: 212px;
  height: 831px;
  background: #FFFFFF;
  flex: none;
  order: 0;
  flex-grow: 0;
  font-family: 'Figtree';
}

ul {
  list-style: none;
  text-align: left;
}

.nav-logo {
  width: 100%;
  height: 100%;
}

.nav-menu {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  gap: 4px;
  width: 180px;
  height: 172px;
  flex: none;
  order: 1;
  flex-grow: 0;
}

.nav-details {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0px;
  width: 179px;
  height: 108px;
  flex: none;
  order: 2;
  flex-grow: 0;
}
</style>