<script setup>
//import router view
import { useRouter, useRoute } from 'vue-router'
</script>

<template>
    <nav>
        <div class="nav-logo">
        <img src="../public/images/Logo.png" alt="Ziezo Logo">
        </div>
        <div class="nav-menu">
        <ul>
            <li><img src="../public/images/icon_home.png" alt="Ziezo Home"> Thuispagina</li>
            <li><img src="../public/images/icon_comment.png" alt="Ziezo Berichten">Berichten</li>
            <li><img src="../public/images/icon_wrench.png" alt="Ziezo Klusjes">Mijn Klusjes</li>
            <li><img src="../public/images/icon_user.png" alt="Ziezo Profiel">Profiel</li>
        </ul>
        </div>
        <div class="nav-details">
        <ul>
          <li><img src="../public/images/icon_question-circle.png" alt="Ziezo Hulp">Hulp Nodig?</li>
          <li><img src="../public/images/icon_info-circle.png" alt="Ziezo Contact">Contact Info</li>
          <li><img src="../public/images/icon_cog.png" alt="Ziezo Instellingen">Instellingen</li>
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
  position: relative;
  top: -304px;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  width: 180px;
  height: 172px;
  order: 1;
  flex-grow: 0;
}

.nav-details {
  position: relative;
  left: 0;
  top: -100px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px;
  width: 179px;
  height: 108px;
  flex: none;
  order: 2;
  flex-grow: 0;
}
</style>